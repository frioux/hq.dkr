# `hq` Container

## Usage

```
curl -sL frew.co | docker run -i --rm frew/hq '//head/title/text()'
```

### Description

[`hq`](https://github.com/rbwinslow/hq) is a commandline tool built in the
spirit of [`jq`](https://stedolan.github.io/jq/) but for HTML.  Use this
container if you don't like having to deal with pip and whatnot.

There are no volumes or environment variables expected.  While the `-f` `hq`
flag is unsupportable without a volume, you can just implement that with `<`,
which is fewer characters and simpler anyway.
