check-poodle
============

[![Project Status: Concept – Minimal or no implementation has been done yet, or the repository is only intended to be a limited example, demo, or proof-of-concept.](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept)

This script checks your server for SSLv3 support. It uses `openssl` to check if SSLv3 supported. This is important for the POODLE attack against SSL 3.0.

http://googleonlinesecurity.blogspot.de/2014/10/this-poodle-bites-exploiting-ssl-30.html

usage
============
./poodle.sh yourServer.foo[:Port]

example
============

$ ./poodle.sh www.google.com

$ ./poodle.sh pop.gmail.com:995
