# void-mirror-manager

Manage mirrors for xbps

## Purpose

Remove the learning curve and hassle for users when swicthing to a mirror closer to home.

## Todo

It should default to tier 1 mirrors, and allow users to select from tier 2 mirrors.

It should query the packages available and create a diff of versions between all mirrors.

When a mirror is ammended, it should be updated using `xbps -S`. A flag to prevent this behaviour will be available.

Check which mirrors hold certain files. for example, many repos will not query for debug files. diff architectures may not be on there either

ADD CUSTOM MIRROR
