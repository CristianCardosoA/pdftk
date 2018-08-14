# pdftk

Install

I was able to get pdftk working on CentOS 7 by using these two repos.

https://copr.fedorainfracloud.org/coprs/robert/gcj/
https://copr.fedorainfracloud.org/coprs/robert/pdftk/
These commands will get you fully up and running.

wget https://copr.fedorainfracloud.org/coprs/robert/gcj/repo/epel-7/robert-gcj-epel-7.repo -P /etc/yum.repos.d

wget https://copr.fedorainfracloud.org/coprs/robert/pdftk/repo/epel-7/robert-pdftk-epel-7.repo -P /etc/yum.repos.d

yum install pdftk
