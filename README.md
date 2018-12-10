---
nav_exclude: true
---
# ddp
Data for Disaster Preparation Workflows


This site is configured to push to AWS S3 and is served by CloudFront at nethope.info/ddp

To push an update to S3:

* Install s3_website: `gem install s3_website`
Run `bundle exec jekyll serve` to generate current static pages in _site (and to test before deployment)
* Add your S3 ID and secret as environment variables: 
```
export ddp_s3_key=ABCDEF
export ddp_s3_secret=XYZ
```
* run `s3_website push`