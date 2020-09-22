# scoop-devtools
A [Scoop](https://scoop.sh/) repository that contains developer tools that may not fit the [main scoop bucket](https://github.com/ScoopInstaller/Main).

# Getting Started

## Install `scoop`

You'll need to install [Scoop](https://scoop.sh/) first if you haven't already.

## Adding `scoop-devtools` bucket

You can add this bucket to your Scoop Bucket list with:

```shell
$ scoop bucket add devtools https://github.com/thushan/scoop-devtools
```

You can verify it was added with - with an example package:

```shell
$ scoop bucket list
$ scoop search avr-gcc
```

Installing packages from this bucket will be just like any other bucket thereafter.

# Update schedule

Updates to the bucket will be automatically run for any packages that have `autoupdate` set in [the manifest](https://github.com/lukesampson/scoop/wiki/App-Manifest-Autoupdate).

Manual updates will be done when required to packages.