# CHANGELOG

All notable changes to this project will be documented in this file. This project adheres to [Semantic Versioning](http://semver.org/).
In order to read more about upgrading and BC breaks have a look at the [UPGRADE Document](UPGRADE.md).

## 1.5.0 (27. July 2021)

+ [#15](https://github.com/luyadev/luya-aws/pull/15) Added new method to read files as stream in order to support LUYA admin 4.0

## 1.4.0 (7. January 2021)

+ [#9](https://github.com/luyadev/luya-aws/pull/9) AssetManager which stores the asset files into the S3 bucket.

## 1.3.0 (1. December 2020)

+ [#11](https://github.com/luyadev/luya-aws/issues/11) The upload object have a default max-age cache control header of 30 days, this can be turned of by setting `maxAge=false`.

## 1.2.1 (19. November 2020)

+ [#10](https://github.com/luyadev/luya-aws/pull/10) Fix issue where content type was not provided correctly, also ensure the disposition is set correctly when uploading or updating and object.

## 1.2.0 (27. August 2020)

+ [#6](https://github.com/luyadev/luya-aws/pull/6) Add new option to update bucket policy, add command to update policy, add helper method with policies as JSON.

## 1.1.0 (18. June 2020)

+ [#5](https://github.com/luyadev/luya-aws/pull/5) Ensure Minio Server compatibility, therfore introduce `endpoint` and `usePathStyleEndpoint` config option.

## 1.0.2 (28. May 2019)

+ [#2](https://github.com/luyadev/luya-aws/issues/2) Use s3 method to check whether a file exists or not.

## 1.0.1 (7. July 2018)

+ [#1](https://github.com/luyadev/luya-aws/issues/1) Store resolved file paths in variable in order to prevent multiple requests, this increases the speed.

## 1.0.0 (22. May 2018)

+ First stable release
