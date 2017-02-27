[![Build Status](https://travis-ci.org/wtanaka/ansible-role-m4.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-m4)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-m4.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-m4)

wtanaka.m4
============

This ansible role installs GNU M4, an implementation of the
traditional Unix macro processor. It is mostly SVR4 compatible
although it has some extensions (for example, handling more than 9
positional parameters to macros). GNU M4 also has built-in functions
for including files, running shell commands, doing arithmetic, etc.

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.m4

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
