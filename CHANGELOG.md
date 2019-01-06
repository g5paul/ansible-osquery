# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- review options based on auditd - testing limited inside containers/travis
- testing: add multiple patterns for excluded_path
- cgroups restriction
- custom variable for keyserver (PR#8)
- Jenkinsfile
- test/default-fleetmanager: test options with kolide fleet
- Centos/RHEL7 selinux: experimental support [TODO]
- Ubuntu apparmor: initial policy
- Gitignore
- include simple travis, kitchen and vagrant tests

### Changed
- Heavy lint following galaxy new rules following adoption of ansible-lint
https://groups.google.com/forum/#!topic/ansible-project/ehrb6AEptzA
https://docs.ansible.com/ansible-lint/rules/default_rules.html
https://github.com/ansible/ansible-lint
- Galaxy dependency naming evolution (juju4.redhat_epel...)

### Removed
- kbrebanov.osquery unmaintained/archived since Sep 2018

## [v0.8] - 2018-06-24 (juju4.osquery)

### Added
- Support expressing an OSQuery secret (PR#5)
- Allow multiline ansible_managed (PR#4)
- testing: load tests (fallocate, split)
- process and sockets auditing
- exclude_paths support
- testing per logger_plugin: filesystem, syslog, filesystem+syslog
- update of osquery apt repository - support trusty, xenial
- Initial fork on Github

### Changed

## [v1.0.0] - 2016-02-18 (kbrebanov.osquery)