# This is Fork of https://github.com/docker-library/php

## The Original Is Maintained by: [the Docker Community](https://github.com/docker-library/php)

This Git repo is a fork of the official Docker Image for PHP 7.4 running on Apache/buster. There are two packages which are no longer supplied as part of the official PHP release that must be compiled in:

-   mysqli
-   pdo-mysql

The Dockerfile has been updated to include these modules in the build. Also, I have included the vi and nano editors in the image so tha testing of changes can be enabled on from the shell.

Once built, this image should be pushed to: 247756923940.dkr.ecr.us-east-1.amazonaws.com/server-labspot and tagged as **PHP7.4**
