Install rbenv as user mode to centos and install specific ruby version.

Example:

```
---
host: all
vars:
  rbenv:
    ruby_version: 2.2.0
roles:
  - rbenv
```
