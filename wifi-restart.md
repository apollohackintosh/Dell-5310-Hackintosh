#!/bin/bash

# Turn off Wi-Fi
networksetup -setairportpower en0 off

# Wait 5 seconds
sleep 5

# Turn on Wi-Fi
networksetup -setairportpower en0 on