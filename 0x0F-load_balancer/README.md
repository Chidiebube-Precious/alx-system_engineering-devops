## Concepts

For this project, we expect you to look at these concepts:

. <a href="https://www.thegeekstuff.com/2016/01/load-balancer-intro/">Load balancer</a>

. <a href="https://intranet.alxswe.com/concepts/68">Web stack debugging</a>

## Background Context

You have been given 2 additional servers:

gc-[STUDENT_ID]-web-02-XXXXXXXXXX

gc-[STUDENT_ID]-lb-01-XXXXXXXXXX

Let’s improve our web stack so that there is <a href="https://en.wikipedia.org/wiki/Redundancy_%28engineering%29"> redundancy</a> for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

## Resources

Read or watch:

. <a href="https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts">Introduction to load-balancing and HAproxy</a>

. <a href="https://www.techopedia.com/definition/27178/http-header">HTTP header</a>

. <a href="https://haproxy.debian.net/">Debian/Ubuntu HAProxy packages</a>

## Requirements

## General

Allowed editors: vi, vim, emacs

All your files will be interpreted on Ubuntu 16.04 LTS

All your files should end with a new line

A README.md file, at the root of the folder of the project, is mandatory

All your Bash script files must be executable

Your Bash script must pass Shellcheck (version 0.3.7) without any error

The first line of all your Bash scripts should be exactly #!/usr/bin/env bash

The second line of all your Bash scripts should be a comment explaining what is the script doing

