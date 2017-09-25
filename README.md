# Symbiote Thrive

This provides a set of modules for building sites in AWS.

## Requirement

* SilverStripe 3.1 → **3.6**
* The S3 CDN patch.

## What's Included?

### [Restricted CMS](https://github.com/nyeholt/silverstripe-restrictedcms/)

This provides load balancing support, specifically for the CMS.

### [S3 CDN](https://github.com/symbiote/silverstripe-s3cdn/)

This provides storage of assets in S3.

_**NOTE:** There's a framework patch that's required for this._

### [SES Mailer](https://github.com/symbiote/silverstripe-sesmail/)

This provides support for sending emails using SES, rather than your own mail server.

### [Mail Capture](https://github.com/nyeholt/silverstripe-mailcapture/)

This provides mail capture and logging (primarily) when using SES.

### [SQS Job Queue](https://github.com/nyeholt/silverstripe-sqs-jobqueue/)

This provides SQS support for running tasks from a queue (with support for the queued jobs module).
