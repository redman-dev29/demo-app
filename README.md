# demo-app
#### Several manifests have been created for quick deployment of pods, jobs, applications and manipulation of cluster resources.

|NAME                   |PROMPT                                              |DESCRIPTION                                        |EXAMPLE                                                 |
|:---                   |:---                                                |:---                                               |:---                                                    |
|app.yaml               |Crate a minimal working app.yaml file               |Deploying the app                                  |[app.yaml](/yaml/app.yaml)                              |
|app-cronjob.yaml       |Crate a minimal working app-cronjob.yaml file       |Creating job for Cron                              |[app-cronjob.yaml](/yaml/app-cronjob.yaml)              |
|app-job.yaml           |Crate a minimal working app-job.yaml file           |Creating job synchronize content of two directories|[app-job.yaml](/yaml/app-job.yaml)                      |
|app-livenessProbe.yaml |Crate a minimal working app-livenessProbe.yaml file |Creating liveness probe pod                        |[app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml)  |
|app-multicontainer.yaml|Crate a minimal working app-livenessProbe.yaml file |Creating pod with two containers inside            |[app-multicontainer.yaml](/yaml/app-multicontainer.yaml)|
|app-readinessProbe.yaml|Crate a minimal working app-readinessProbe.yaml file|Creating readiness probe pod                       |[app-readinessProbe.yaml](/yaml/app-readinessProbe.yaml)|
|app-resources.yaml     |Crate a minimal working app-resources.yaml file     |Creating pod with requests and limits resources    |[app-resources.yaml](/yaml/app-resources.yaml)          |
|app-secret-env.yaml    |Crate a minimal working app-secret-env.yaml file    |Creating pod with redis image                      |[app-secret-env.yaml](/yaml/app-secret-env.yaml)        |
|app-volumeMounts.yaml  |Crate a minimal working app-volumeMounts.yaml file  |Creating pod with mounting volume                  |[app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml)    |
