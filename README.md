# elistone.github.io

This is the source code for my personal website. 
It is built using [Vue.js](https://vuejs.org/).

## Contents
- [Setup](#setup)
- [Deployment](#deployment)
  - [Automatic](#method-1-automatic-deployment)
  - [Manual](#method-2-manual-deployment-for-testing-purposes)
- [Playwright](#playwright)

## Setup
1. Install the dependencies: `pnpm install`
2. Run the development server: `pnpm dev`

## Deployment

There are two methods to deploy the project:

### Method 1: Automatic Deployment
1. Apply tag to commit on the `main` branch: `git tag -a v1.0.0 -m "Version 1.0.0"`
2. Push the tag to the remote repository: `git push origin v1.0.0`
3. The deployment will be triggered automatically

### Method 2: Manual Deployment (for testing purposes)
1. Build the project: `pnpm build`
2. Deploy the project: `pnpm deploy`

## Playwright
1. Run the tests: `pnpm install`
2. Build the project: `pnpm build`
3. Run the tests: `pnpm test:e2e`