# gcp-cloudbuild-gae-angular

A sample Angular project to be deployed to Google Cloud App Engine Standard Environment using Cloud Build.

## Deploy with a few commands

```bash
gcloud auth login
gcloud config set project <YOUR-PROJECT-ID>
gcloud builds submit --config cloudbuild.yaml .
```

## Understand the concepts and automate more

[Continuous Delivery in Google Cloud Platform — Cloud Build with App Engine](https://medium.com/google-cloud/continuous-delivery-in-google-cloud-platform-cloud-build-with-app-engine-8355d3a11ff5) @ Google Cloud Community / Medium

## App Engine Flexible Environment setup

In case you need to use a flexible environment, please refer to the [gcp-cloudbuild-gae-flex-angular repository](https://github.com/ricardolsmendes/gcp-cloudbuild-gae-flex-angular).
The main changes are described in its `README.md` file.
