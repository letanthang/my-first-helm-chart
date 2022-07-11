$ helm create mychart
$ helm package mychart
$ mv mychart-0.1.0.tgz docs

$ helm repo index docs --url https://letanthang.github.io/my-first-helm-chart/