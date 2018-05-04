# NGINX with AWS Authentication Module and ZIP Module

This is a custom version of the upstream `nginx:1.12.2-alpine` Docker image,
with the following modules added:

- [AWS Authentication Module](https://github.com/anomalizer/ngx_aws_auth)
- [ZIP Module](https://github.com/evanmiller/mod_zip)

Other than these added modules, the Docker image completely matches the upstream
version and build process.
