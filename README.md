# archie-test-site

Tiny Vite vanilla template, used as a test repo for Archie's App Delivery flow.

## Build

```sh
npm install && npm run build
```

Outputs to `dist/`.

## Used by

Archie [Cloud Discovery + App Delivery](https://app.askarchie.io) — connects this repo,
runs the build above in a Fargate worker, and uploads `dist/` to an S3+CloudFront
blueprint deployed via Archie. Verifies the end-to-end "infra + app, one click"
flow.
