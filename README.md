[![librtlsdr version](https://img.shields.io/github/tag/librtlsdr/librtlsdr.svg?style=flat&label=librtlsdr)](https://github.com/librtlsdr/librtlsdr/releases)
[![Build Status](http://circleci-badges-max.herokuapp.com/img/librtlsdr/librtlsdr/master?token=:circle-ci-token)](https://circleci.com/gh/librtlsdr/librtlsdr/tree/master)
[![GPLv2 License](http://img.shields.io/badge/license-GPLv2-brightgreen.svg)](https://tldrlegal.com/license/gnu-general-public-license-v2)

# Description

rtl-sdr turns your Realtek RTL2832 based DVB dongle into a SDR receiver

# Updates by Who8MyLunch

I'm going to try cherry picking interesting commits from [`kerel-fs/librtlsdr/pvb/rebased`](https://github.com/kerel-fs/librtlsdr/tree/pvb/rebased) branch into my own copy of [`librtlsdr/librtlsdr/development`](https://github.com/librtlsdr/librtlsdr/tree/development) which I've named `modernize`.  Let's see how this goes.

Relevant histories:
- kerel-fs pvb/rebased: https://github.com/kerel-fs/librtlsdr/commits/pvb/rebased
- librtlsdr development: https://github.com/librtlsdr/librtlsdr/commits/development/src

Commits:
- why no worky: https://github.com/kerel-fs/librtlsdr/commit/e7a5b03ef50853d3f59b37233603f87db5594a31


# For more information see:

http://sdr.osmocom.org/trac/wiki/Rtl-sdr


# Contributing

Pull requests are always welcome but please make changes to, and pull request from, the development branch.

Initial setup:

- fork the main librtlsdr repo via github
- clone your fork locally and cd to the cloned repo's folder
- add the upstream development repo:
    * git remote add upstream git@github.com:librtlsdr/librtlsdr.git
- track the development branch:
    * git branch --track development origin/development

Normal workflow:

- checkout the development branch and make your changes
- commit your changes
- sync your local development branch with the upstream development branch:
    * git fetch upstream
    * git merge upstream/development
- push your commit/s to your forked repo
- do a pull request via github
