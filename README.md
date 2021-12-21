# gcp-cloudbuild-gae-angular

A sample Angular project to be deployed to Google Cloud App Engine Standard Environment using Cloud
Build.

## Deploy from your machine with a few commands

- Clone/fork the repository.
- Edit `cloudbuild.yaml` and remove the `--version=$SHORT_SHA` option. It will work only for Cloud
  Build triggered builds.
- Then:

  ```sh
  gcloud auth login
  gcloud config set project <YOUR-PROJECT-ID>
  gcloud builds submit --config cloudbuild.yaml .
  ```

## Get to know the concepts behind this code

[Continuous Delivery in Google Cloud Platform — Cloud Build with App
Engine](https://medium.com/google-cloud/continuous-delivery-in-google-cloud-platform-cloud-build-with-app-engine-8355d3a11ff5)
@ Google Cloud Community / Medium

## App Engine Flexible Environment setup

In case you need to use a flexible environment, please refer to the [gcp-cloudbuild-gae-flex-angular
repository](https://github.com/ricardolsmendes/gcp-cloudbuild-gae-flex-angular). The main changes
are described in its `README.md` file.

## How to contribute

Please make sure to take a moment and read the [Code of
Conduct](https://github.com/ricardolsmendes/gcp-cloudbuild-gae-angular/blob/master/.github/CODE_OF_CONDUCT.md).

### Report issues

Please report bugs and suggest features via the [GitHub
Issues](https://github.com/ricardolsmendes/gcp-cloudbuild-gae-angular/issues).

Before opening an issue, search the tracker for possible duplicates. If you find a duplicate, please
add a comment saying that you encountered the problem as well.

### Contribute code

Please make sure to read the [Contributing
Guide](https://github.com/ricardolsmendes/gcp-cloudbuild-gae-angular/blob/master/.github/CONTRIBUTING.md)
before making a pull request.
