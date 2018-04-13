#!/bin/sh

# Returns global ip address

ifconfig | grep '[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}' | head -n 1 | awk '{print $2}'
