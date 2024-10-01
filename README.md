# Can YOU Deploy Migrations?

Go [here](https://can-i-deploy-a-migration-to-chuck.netlify.app/) to find out.

This is a static website that pulls from a public config [bucket](https://us-east-1.console.aws.amazon.com/s3/buckets/funnel-public-config?region=us-east-1&bucketType=general&tab=objects) to identify whether we are in a restricted window (i.e. a time when we should not be running migrations against the production database). The same file is used by rules in CI/CD.
