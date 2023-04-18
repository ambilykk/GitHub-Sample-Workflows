## GitHub Sample Workflows
Repository to explain various concepts associated with the GitHub Actions workflow. This repository contains a set of sample workflows that you can use as a reference for your own workflows.

> **Note:** This repository is a work in progress. We will be adding more workflows to this repository over time.

> **Note:** The workflows in this repository are not meant to be used as-is in your own repositories. They are meant to be used as a reference for your own workflows.

> **Note:** All workflows are triggered manually. You can trigger a workflow by clicking the **Actions** tab in your repository and then clicking the **Run workflow** button.

## Workflows
Name | Type | Description
--- | --- | ---
[**`Hello World`**](./.github/workflows/1.1-hello-world.yml) | Concept | Sample workflow to display "Hello World" 
[**`Deployment Summary`** ](./.github/workflows/1.2-deployment-summary.yml) | Concept | Sample workflow explaining how to display deployment summary
[**`Run Name`** ](./.github/workflows/1.3-run-name.yml) | Concept | Defining run name for a workflow instead of commit/event context
[**`Reusable Workflow`** ](./.github/workflows/1.4.1-reusable-wf1.yml) | Concept | How to define a reusable workflow (not a workflow)
[**`Caller Workflow`** ](./.github/workflows/1.4.2-caller-wf.yml) | Concept | Call the reusable workflow using various input parameters
[**`Caller Workflow with Matrix`** ](./.github/workflows/1.4.3-caller-matrix.yml) | Concept | Matrix strategy along with Reusable workflow
[**`Sequential execution of Jobs`** ](./.github/workflows/1.4.4-caller-sequestial.yml) | Concept | Sequential execution of reuable workflow 
[**`Sequential execution of Jobs with Error`** ](./.github/workflows/1.4.5-caller-sequestial.yml) | Concept | Skipping jobs based on dependent job failure
[**`Sequential execution of Jobs with error bypass`** ](./.github/workflows/1.4.6-caller-sequestial.yml) | Concept | Continue execution of jobs, even if there is dependent job failures
[**`Publishing NPM Module to GitHub Package`** ](./.github/workflows/3.1-publish-npm-module-gh-package.yml) | Concept | Publish npm module to GitHub Packages registry
[**`Publishing Maven Package to GitHub Package`** ](./.github/workflows/3.2-publish-maven-pkg-gh-package.yml) | Concept | Publish Maven package to GitHub Packages registry
