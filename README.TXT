
A tool to stress test the SSL handshake by triggering processor intensive
RSA_encrypt() calls on the server side.

See more documentation and paper at:


                    http://www.thc.org/thc-ssl-down

COMPILE
=======

# ./configure
# make all
# src/thc-ssl-down -h


Yours sincerly,

The Hackers Choice
http://www.thc.org

更改之后的可以绕过SSL－Renegtiation 和 SSL-Accelerator 策略，因为有些原因暂不更新此版本源码，需要请联系说明用途。
