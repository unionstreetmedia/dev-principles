# Engineering Principles

Main landing page is at [./usm-engineering-principles/docs/index.md](./usm-engineering-principles/docs/index.md)

Inspired from:

- https://github.com/daftlabs/creed
- http://engineering-principles.onejl.uk/

## How To Contribute

1. Create a branch and make your changes.
2. Submit a PR to this repo explaining your change
3. Get input from all team members in the PR
    1. Agree aka hell yeah!
    2. Disagree aka Hard no and here's why I won't commit to this
    3. Disagree but commit aka I'm not convinced but I'll try it. To revisit

## Running Locally

#### Prerequisites

- [MkDocs](https://www.mkdocs.org/#installation)

```
cd usm-engineering-principles
mkdocs serve
```

## Deployment

The static website is automatically generated and deployed when merged into master. The `buildspec.yml` file contains the definition of the build process. The deployment is orchestrated in the [CodePipeline project](https://console.aws.amazon.com/codesuite/codepipeline/pipelines/eng-principles/view?region=us-east-1).

The website is deployed as a [static S3 website](https://s3.console.aws.amazon.com/s3/buckets/usm-dev-principles/?region=us-east-1&tab=properties) and is available at [http://usm-dev-principles.s3-website-us-east-1.amazonaws.com/](http://usm-dev-principles.s3-website-us-east-1.amazonaws.com/).

### Building locally

The following script will run the CodeBuild process locally and generate artifacts in `.codebuild_output/`. 

```
. local/run_build.sh
```

#### Prerequisites

Ensure you have the `aws/codebuild/standard:2.0` CodeBuild image built locally. You can follow the instructions [here](https://github.com/aws/aws-codebuild-docker-images#how-to-build-docker-images) 