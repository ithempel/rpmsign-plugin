# Jenkins RPM Sign Plugin

[![Build Status](https://buildhive.cloudbees.com/job/jenkinsci/job/rpmsign-plugin/badge/icon)](https://buildhive.cloudbees.com/job/jenkinsci/job/rpmsign-plugin/)

This plugin adds a post-build step to sign rpms using GPG.

## Dependencies

This plugin depends on both **gpg** and **expect** being installed on the host machine.
Make sure your Locale is set to en_US, otherwise the expect script wont work as desired.

## Usage

