htpc-common
===========

[![Build Status](https://travis-ci.org/denics/ansible-role-htpc-common.svg?branch=master)](https://travis-ci.org/denics/ansible-role-htpc-common)

An ansible role to perform common tasks on HTPC.

Overview
--------

1. Install ssh server to allow remote management.
2. Configure Zerconf networking and avahi-alias service.
3. Create htpc_user if user doesn't exist.
4. Enable sudo access for htpc user.
5. Create htpc media and downloads folders.