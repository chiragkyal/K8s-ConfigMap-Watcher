# K8s-ConfigMap-Watcher

We would like to watch if some change happens in `ConfigMap` and/or `Secret`; then perform a rolling upgrade on relevant `DeploymentConfig`, `Deployment`, `Daemonset`, `Statefulset` and `Rollout`

References 
* https://github.com/stakater/Reloader
* https://github.com/spf13/viper#watching-and-re-reading-config-files
* https://itnext.io/working-with-kubernetes-configmaps-part-2-watchers-b6dd0e583d71
