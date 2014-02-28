---
layout: post
title: linux ssh login
categories: [tool]
tags: [linux, ssh]
---

linux_ssh_login

#!/usr/local/bin/expect
#dependency
#tcl8.5.12-src.tar.gz, expect5.45.tar.gz
#meet ‘$’ need transform ‘\$’


#host
if {$argc != 1} {
    puts “input hostname”
    puts “run command:”
    puts “1: (./linux_ssh server_a)(ip_a)”
    puts “2: (./linux_ssh server_b)(ip_b)”
    exit
}
set host [lindex $argv 0]


#/********************get host-name-info begin************************/
if {$host == “server_a”} {
    set host “ip_a”
    set passwd “passwd_a”
} elseif {$host == “server_b”} {
    set host “ip_b”
    set passwd “passwd_b”
} else {
    puts “error hostname”
    exit
}
puts “host: $host”
#/********************get host-name-info end************************/


set timeout 10

spawn ssh “root@$host”
expect “password:”
send “$passwd\r”
interact


