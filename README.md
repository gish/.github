# .github

## Workflow templates

### Deploy static page

Deploys static page by

1. Applying Terraform configuration
1. Building the page with `npm run build`
1. Deploying the page to S3 bucket with content in `./dist`

#### Configuration

Set env variables `AWS_S3_BUCKET_URL` and `AWS_ClOUDFRONT_DISTRIBUTION_ID`.

