# Deploy

This repository is just to hold the Deploy action for Production and Preview environments for the actual blog.

The Vercel integration at [blog](https://github.com/LR-Tech-Blog/blog) is to deploy the development build on a different Vercel project.

## Status

[![Vercel Deploy Production](https://github.com/LR-Tech-Blog/deploy/actions/workflows/vercel_deploy_production.yaml/badge.svg)](https://github.com/LR-Tech-Blog/deploy/actions/workflows/vercel_deploy_production.yaml) [![Vercel Deploy Preview](https://github.com/LR-Tech-Blog/deploy/actions/workflows/vercel_deploy_preview.yaml/badge.svg)](https://github.com/LR-Tech-Blog/deploy/actions/workflows/vercel_deploy_preview.yaml)

## Preview URLs

When the [Vercel Deploy Preview](https://github.com/LR-Tech-Blog/deploy/blob/main/.github/workflows/vercel_deploy_preview.yaml) is triggered, it will create a new deployment with a unique URL. This link is exposed as Annotation in the actual action run as `Notice`.

### Remarks

For now, the production deploy is triggered manually.
