xen-tools-roles
===============

Basic xen-tools roles for creating basic Xen paravirtualized containers.

These templates are roles which you can use with xen-create-image with
the --role= option.

Templates
=========

* base-server: basic Debian GNU/Linux Server

Installation
============

- Copy templates to /etc/xen-tools/role.d directory
- make executable (chmod +x)

Usage
=====

Create a Xen paravirtualized container with --role option:

xen-create-image --hostname=vm1 --role=base-server

Author: 
======

Jesus Lara jesuslarag at gmail dot com 
version: 0.1 Copyright (C) 2010 Jesus Lara
