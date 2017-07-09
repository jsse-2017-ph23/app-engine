# app-engine
App engine for publishing periodic pub-sub event

See [this](https://firebase.googleblog.com/2017/03/how-to-schedule-cron-jobs-with-cloud.html) for details

## Deployment
This project does NOT comes with travis integration. Manual deployment is required.

Deployment command:
```shell
gcloud app deploy app.yaml cron.yaml
```

