# unzipper

This is an _extremely_ simple implementation of the shutil Python library to unzip files within a target folder. As a simple command-line program, this has no options or API, and will clobber files that already exist in the target folder. 

Errors are printed to stdout when observed, otherwise, output is shown as a progress indicator denoting the number of files unzipped.

```
$ unzip_all <path to unzip>
```

*Tip: stick this in your favorite PATH location to make it an environment variable accessible from anywhere!*

```
$ sudo cp unzip_all usr/local/bin/unzip_all
$ sudo chmod +x usr/local/bin/unzip_all
```

Enjoy!