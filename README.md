# 概要

オラクルDBへのアクセスに必要なoracleClientをインストールするためのheroku-buildpack



## Usage

Either add `https://github.com/featurist/oracle-client-buildpack` to `.buildpacks` or set `BUILDPACK_URL=https://github.com/featurist/oracle-client-buildpack`
You also need API buildpack, preceding this one. And an `Aptfile` in the root of your app containing:

```
libaio1
```

## Testing

### Setup

```
heroku create --buildpack https://github.com/heroku/heroku-buildpack-testrunner
```
