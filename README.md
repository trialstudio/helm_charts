This is a repository created to store personal helm charts.

This repo is set as a github page to serve the index file with the helm packages referenced those in AWS s3.
It is set up this way as an experiment.

Github action has been set up to watch for Chart.yaml file changes. 
Once triggered, the updated chart will be packaged and uploaded to s3 and update the index file.

To use this repo
```
helm repo add my-repo https://trialstudio.github.io/helm_charts/
```
