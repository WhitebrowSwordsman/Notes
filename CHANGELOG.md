# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.0.0] - 2021-05-27
### Changed
- Config current git repo:
  ```bash
  git config --local user.name "user_name"
  git config --local user.email "user_email" 
  ```
- Force git to always ask for a password:
  ```
  git config --local credential.helper ''
  ``` 
- Username and password in command for git push:
  ```
  git push https://username:password@github.com/myrepository/myproject.git --all
  ```
