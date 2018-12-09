# gcp-cloudbuild-gae-angular

A sample Angular project to be deployed to Google Cloud App Engine Standard Environment using Cloud Build.

## Deploy with a few commands

```bash
gcloud auth login
gcloud config set project <YOUR-PROJECT-ID>
gcloud builds submit --config cloudbuild.yaml .
```

## Understand the concepts and automate more

<a href="https://medium.com/google-cloud/continuous-delivery-in-google-cloud-platform-cloud-build-with-app-engine-8355d3a11ff5" target="_blank">Continuous Delivery in Google Cloud Platform — Cloud Build with App Engine</a> @ Google Cloud / Medium
