# AWS Infrastructure Repositories

In this repository, you will find links to various Terraform modules that implement different infrastructure components in AWS. You can use these modules in your projects to quickly deploy the required infrastructure in the cloud.

## Static Site Module with S3 in Terraform

This module allows you to create a static website on Amazon S3. It utilizes Amazon S3's object storage service to host and distribute your static website files. Additionally, it automatically configures the site to be available on the internet using Amazon CloudFront.

This module includes:

- Creation of an S3 bucket to store the website files.
- Configuration of the bucket to host a static website.
- CloudFront setup to distribute the site and provide SSL.
- Optional custom domain name configuration.

You can find the source code and detailed instructions in the corresponding repository:

🔗 [Static Site Module with S3 in Terraform](https://github.com/jcescobarn/tf_s3_static_site)



