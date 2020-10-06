# TODO

- [ ] Finish up threading from compose.yml -> app_config via env vars
  - Make sure not to miss setting defaults in .envrc.sample for future reference
  - Make sure to copy/pasta heavily from our existing running instance configuration
  - We may need a hack to load env vars from secret paths (ask @3wordchant)
    - https://github.com/3-w-c/docker-adaptauthoring/blob/master/docker-entrypoint.sh
