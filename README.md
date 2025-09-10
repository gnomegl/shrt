# shrt

[![basher install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/package/)

gray hat warfare api client for exposed file search

## install

```bash
basher install gnomegl/shrt
```

## usage

```bash
shrt [keywords] [page] [size]
```

search exposed s3 buckets and files.

## options

- `-e, --ext` - file extensions (comma-separated)
- `-o, --order` - sort by size or timestamp
- `-d, --direction` - asc or desc
- `-r, --regexp` - treat keywords as regex
- `-u, --urls-only` - output urls only
- `-j, --json` - raw json output

## config

set api key:
```bash
export GRAYHAT_API_KEY="your_token"
```

## requirements

- curl
- jq