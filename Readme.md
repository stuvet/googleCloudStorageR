# googleCloudStorageR

R library for interacting with the Google Cloud Storage JSON API ([api docs](https://cloud.google.com/storage/docs/json_api/)).

## Setup

Please refer to the [googleCloudStorageR](http://code.markedmondson.me/googleCloudStorageR/) website for most up to date documentation:

https://cloudyr.github.io/googleCloudStorageR/

## Installation

[![CRAN](http://www.r-pkg.org/badges/version/googleCloudStorageR)](http://cran.r-project.org/package=googleCloudStorageR)
[![Build Status](https://travis-ci.org/cloudyr/googleCloudStorageR.png?branch=master)](https://travis-ci.org/cloudyr/googleCloudStorageR)
[![codecov.io](http://codecov.io/github/cloudyr/googleCloudStorageR/coverage.svg?branch=master)](http://codecov.io/github/cloudyr/googleCloudStorageR?branch=master)
![CloudBuild](https://badger-ewjogewawq-ew.a.run.app/build/status?project=mark-edmondson-gde&id=b645a814-94ae-4154-90fb-dad20f815ad9)

This package is on CRAN:

```R
# latest stable version
install.packages("googleCloudStorageR")
```

Or, to pull a potentially unstable version directly from GitHub:

```R
if(!require("remotes")){
    install.packages("remotes")
}
remotes::install_github("cloudyr/googleCloudStorageR")
```

---
[![cloudyr project logo](http://i.imgur.com/JHS98Y7.png)](https://github.com/cloudyr)
