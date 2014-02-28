---
layout: post
title: mysql ssh login
categories: [tool]
tags: [mysql, ssh]
---

{% highlight bash %}
mysql_ssh_login

#!/usr/local/bin/expect
#dependency
#tcl8.5.12-src.tar.gz, expect5.45.tar.gz
#meet ‘$’ need transform ‘\$’


#host
if {$argc != 1} {
 puts “input hostname”
    puts “run command:”
    puts “1: (./mysql_ssh mysql_a)(ip_a)”
    puts “2: (./mysql_ssh mysql_b)(ip_b)”
 exit
}
set host [lindex $argv 0]


#/********************get host-name-info begin************************/
if {$host == “mysql_a”} {
 set host “ip_a”
 set port port_a
 set user “user_a”
 set passwd “passwd_a”
} elseif {$host == “mysql_b”} {
 set host “ip_b”
 set port port_b
 set user “user_b”
 set passwd “passwd_b”
} else {
 puts “error hostname”
 exit
}
puts “host: $host”
#/********************get host-name-info end************************/


set timeout 10

spawn /usr/local/mysql/bin/mysql -h $host -P $port -u $user -p
expect “password:”
send “$passwd\r”
interact
{% endhighlight %}

