# GIT - Pre-Commit check for certain words

#### Table of Contents

1. [Description](#module-description)
2. [Setup](#setup)
3. [Usage](#usage)
4. [Development](#development)
5. [Contributors](#contributors)

## Description

GIT pre-commit hook for checking the existence of certain words/phrases/functions 
in the code to be committed. 

## Setup

To install hook, copy pre-commit file to your project .git/hooks/pre-commit:

```sh
$ cp pre-commit .git/hooks/pre-commit;
$ chmod +x .git/hooks/pre-commit;
```

## Usage

The hook comes with the `die`, `print_r` and `dump` functions as the strings to
be checked prior to the commit. You can add more strings to be checked if you wish 
by modifying the checks array

## Development

[uTip](https://www.utip.io)'s repositories are open projects, and community contributions are essential for keeping them great.


[Fork this repo on GitHub](https://github.com/utipteam/Git-Pre-Commit-Hook-for-certain-words/fork)

## Contributors

The list of contributors can be found at: https://github.com/utipteam/Git-Pre-Commit-Hook-for-certain-words/graphs/contributors
