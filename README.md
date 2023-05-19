# gl-inet-hacks

My repository of scripts, `init.d` services and other foo to make
my GL-iNet hotspots work better!

## Why?

I bought a Mudi (GL-E750) as a replacement for my Slate (AX-1800), since it had
a battery and a 4G modem onboard.

I usually don't need the modem to be on. I found some instructions on how to
turn it off through GPIO, but it would always turn on after a reboot.

Since I didn't want to run this command every time I started my hotspot, I added
an `init.d` service to ensure that it doesn't turn on at boot.

I thought "this should be in a Git repo!"

This is that repo.

## How to use

Simply run the script in the folder for the device being configured.
