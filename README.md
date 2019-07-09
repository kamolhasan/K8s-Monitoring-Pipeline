# K8s-Monitoring-Pipeline

References:

- [Kubernetes monitoring architecture](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/instrumentation/monitoring_architecture.md)
- [Kubernetes metrics server](https://github.com/kubernetes-incubator/metrics-server)
    - [Kubernetes metrics-server Installation](https://medium.com/@cagri.ersen/kubernetes-metrics-server-installation-d93380de008)
- Prometheus
    - [Prometheus operator](https://github.com/coreos/prometheus-operator/blob/master/Documentation/user-guides/getting-started.md)
    - [Grafana](https://github.com/appscode/third-party-tools/tree/master/monitoring/grafana)
    - [Prometheus node exporter](https://github.com/prometheus/node_exporter)
        - [Helm chart](https://github.com/helm/charts/tree/master/stable/prometheus-node-exporter)

- [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics)
    - [Deployment, service and necessary rbac yamls](https://github.com/kubernetes/kube-state-metrics/tree/master/kubernetes)
    
- [k8s-prometheus-adapter](https://github.com/DirectXMan12/k8s-prometheus-adapter/blob/master/docs/walkthrough.md)
- [Aggregation](https://github.com/kubernetes-incubator/apiserver-builder-alpha/blob/master/docs/concepts/aggregation.md)

- Blog Post
    - [Guide to Kubernetes Metrics](https://medium.com/@congliu.thu/complete-guide-to-kubernetes-metrics-24a8782c34cd)
    - [Get Kubernetes Cluster Metrics with Prometheus in 5 Minutes](https://akomljen.com/get-kubernetes-cluster-metrics-with-prometheus-in-5-minutes/)
    - [Monitoring Kubernetes Clusters with Grafana](https://medium.com/htc-research-engineering-blog/monitoring-kubernetes-clusters-with-grafana-e2a413febefd)
    - Kubernetes Monitoring with prometheus - The ultimate guide
        - [part 1](https://sysdig.com/blog/kubernetes-monitoring-prometheus/)
        - [part 2](https://sysdig.com/blog/kubernetes-monitoring-with-prometheus-alertmanager-grafana-pushgateway-part-2/)
        - [part 3](https://sysdig.com/blog/kubernetes-monitoring-prometheus-operator-part3/)
    - [Prometheus Blog Series](https://blog.pvincent.io/tags/prometheus/)
        - [Metrics and Labels](https://blog.pvincent.io/2017/12/prometheus-blog-series-part-1-metrics-and-labels/)
        - [Metric types](https://blog.pvincent.io/2017/12/prometheus-blog-series-part-2-metric-types/)
        - [Exposing and collecting metrics](https://blog.pvincent.io/2017/12/prometheus-blog-series-part-3-exposing-and-collecting-metrics/)
        - [Instrumenting code in Go and Java](https://blog.pvincent.io/2017/12/prometheus-blog-series-part-4-instrumenting-code-in-go-and-java/)
        - [Alerting rules](https://blog.pvincent.io/2017/12/prometheus-blog-series-part-5-alerting-rules/)
    - [Prometheus and StackDriver as Sidecar](https://medium.com/google-cloud/prometheus-and-stackdriver-fb8f7524ece0)
