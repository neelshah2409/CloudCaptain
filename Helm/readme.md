Welcome to our comprehensive collection of learning resources for **Helm**! Here, you'll discover a curated list of the best learning materials we've assembled just for you.

Take a moment to explore these valuable resources, handpicked to enhance your understanding of **Helm**. We strive to provide the most up-to-date and informative content available.

# Contents
<!-- TOC -->

- [Guides](#guides)
- [Repositories / hubs](#repositories--hubs)
- [Application repositories](#application-repositories)
- [Plugins](#plugins)
- [Tools, extras](#tools-extras)
- [Community](#community)


Guides
------
* [How to create your first helm chart](https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/) - Bitnami guide on authoring your first chart
* [Authoring awesome charts](https://github.com/helm/helm-classic/blob/master/docs/awesome.md) - official Helm guide on authoring Awesome Charts
* [Kompose](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/) - how to translate a docker-compose file into a Helm chart

Repositories / hubs
-------------------
Official Kubernetes Helm repositories

* [Kubernetes Helm charts stable repo](https://github.com/helm/charts/tree/master/stable)
* [Kubernetes Helm charts incubating repo](https://github.com/helm/charts/tree/master/incubator)
* [Helm Hub](https://hub.helm.sh) - Official Helm Hub

3rd party repositories / hubs

* [Cloudsmith](https://cloudsmith.io/l/helm-repository/) - A fully managed package management SaaS, with first-class support for public and private Kubernetes registries (Docker + Helm Charts, plus many others). Has a generous free-tier and is also completely free for open-source.
* [Fabric8](https://fabric8.io/helm/) - chart repository by Fabric8
* [Kubeapps](https://hub.kubeapps.com/) - Kubeapps helm chart hub by Bitnami
* [Fairwinds](https://hub.helm.sh/charts/fairwinds-stable) - Chart hub by Fairwinds
* [ChartCenter](https://chartcenter.io) - Central repository of Helm charts by JFrog

Application repositories
------------------------
These usually hold a single chart or a group of connected charts. Can be more up to date than the mainstream Kubernetes repos.

* [Gitlab Omnibus](https://charts.gitlab.io) - an All-In-One chart for deploying Gitlab in Kubernetes
* [Jupyterhub and Binderhub](https://jupyterhub.github.io/helm-chart/) - charts for deploying services to run Jupyter notebooks
* [Harbor](https://github.com/goharbor/harbor-helm) - Harbor is a container and Helm registry with built-in security
* [OpenStack](https://github.com/openstack/openstack-helm) - various charts by the OpenStack project
* [Fn Project](https://github.com/fnproject/fn-helm) - Fn serverless platform charts
* [Lenses](https://github.com/Landoop/kafka-helm-charts) - charts for Lenses, Apache Kafka, Kafka Connect and other components for data streaming and data integration
* [Zalenium](https://github.com/zalando/zalenium/tree/master/charts/zalenium) - flexible and scalable container based Selenium Grid with video recording, live preview, basic auth & dashboard
* [Elasticsearch Fluentd Kibana](https://github.com/cdwv/efk-stack-helm) - chart to deploy a full EFK stack for Kubernetes monitoring
* [Bitwarden](https://github.com/cdwv/bitwarden-k8s) - Helm chart for deploying bitwarden-rs - unofficial Bitwarden-compatible server
* [Elastic](https://github.com/elastic/helm-charts/) - Official helm charts for [Elatic.co](https://www.elastic.co/)'s open source products (ElasticSearch, Kibana & filebeat)
* [Mocktail](https://github.com/Huseyinnurbaki/mocktail) - Helm chart for deploying the free, tiny mock api server Mocktail

Plugins
-------

* [Helm Blob](https://github.com/C123R/helm-blob) - Plugin that allows you to manage helm repositories on the blob storage like Azure Blob, GCS, S3, etc.
* [Helm Diff](https://github.com/databus23/helm-diff) - Plugin that shows a diff explaing what a `helm upgrade` and `helm rollback` would change. It can also compare two separate revisions of the release.
* [Helm Env](https://github.com/adamreese/helm-env) - Plugin to show the environment variables available to a helm plugin.
* [Helm Last](https://github.com/adamreese/helm-last) - Plugin that shows the latest release interacted with. This is useful for chaining commands together like `helm status $(helm last)`.
* [Helm Local](https://github.com/adamreese/helm-local) - Plugin to run Tiller (helm 2's server-side component) as a local daemon.
* [Helm Nuke](https://github.com/adamreese/helm-nuke) - Plugin that deletes and purges all releases stored by Tiller.
* [Helm Secrets](https://github.com/jkroepke/helm-secrets) - Plugin to manage and store secrets safely.
* [Helm Monitor](https://github.com/ContainerSolutions/helm-monitor) - Plugin to monitor a release and rollback based on Prometheus/ElasticSearch query.
* [Helm S3](https://github.com/hypnoglow/helm-s3) - Plugin to fetch charts from S3.
* [Helm Starter](https://github.com/salesforce/helm-starter) - Plugin that simplifies working with helm chart starter packs.
* [Helm GCS](https://github.com/hayorov/helm-gcs) - Plugin that manages chart repos on Google Cloud Storage privately.
* [Helm GitHub](https://github.com/web-seven/helm-github) - Plugin that detects and install Helm Charts from GitHub Public/Private Repository Releases.
* [Helm Schema Gen](https://github.com/karuppiah7890/helm-schema-gen) - So that you don't have to write `values.schema.json` by hand from scratch for your Helm 3 charts
* [Helm Datree](https://github.com/datreeio/helm-datree) - Plugin to prevent Kubernetes misconfigurations by ensuring that Helm charts follow best practices as well as your organization’s policies
* [Helm Teller](https://github.com/SpectralOps/helm-teller) - Plugin that allows you to manage deployment configuration and secrets from multiple providers securely with [Teller](https://github.com/SpectralOps/teller)
* [Helm Release](https://github.com/JovianX/helm-release-plugin) - Plugin that pulls(re-creates) Helm charts from deployed releases, also allows update values of deployed releases without supplying the chart(for modified or custom charts, or when there's no access to the chart)


Tools, Extras
-------------
Helm-related tools
* [Keel.sh](https://keel.sh) - Continuous delivery for Kubernetes - enhances Helm with auto upgrades and other cool features
* [Helmfile](https://github.com/roboll/helmfile) - Helmfile is a declarative spec for deploying helm charts, supports flexible templating scenarios
* [Helmsman](https://github.com/Praqma/helmsman) - Helmsman provides a declarative way of installing charts, features terraform-like desired state file approach and security enhancements
* [Reckoner](https://github.com/FairwindsOps/reckoner) - Reckoner is a tool to simplify management and installation of multiple Helm chart releases
* [Monocular](https://github.com/helm/monocular) - A web-based application that enables the search and discovery of charts from multiple Helm Chart repositories
* [Ship](https://github.com/replicatedhq/ship) - A tool that makes it easy to watch and apply updates to Helm charts and integrates [Kustomize](https://kustomize.io) patches and overlays
* [Brigade](https://github.com/brigadecore/brigade) - A tool for running scriptable, automated tasks in the cloud — as part of your Kubernetes cluster
* [Helm-Starter-Istio](https://github.com/salesforce/helm-starter-istio) - A helm starter for creating [Istio](https://istio.io/) managed services
* [Helm Broker](https://github.com/kyma-project/helm-broker) - A Service Broker which exposes Helm charts as Service Classes in the [Service Catalog](https://svc-cat.io/)
* [Chart Releaser](https://github.com/helm/chart-releaser) - Helps Turn GitHub Repositories into Helm Chart Repositories
* [ChartMuseum](https://chartmuseum.com/) - ChartMuseum is an open-source, easy to deploy, Helm Chart Repository server.
* [Helmify](https://github.com/arttor/helmify) - Generates a Helm chart from Kubernetes yamls
* [Helm Docs](https://github.com/norwoodj/helm-docs) - Auto-generates documentation from helm charts into markdown files
* [Chart Viewer](https://github.com/ecojuntak/chart-viewer) - Helps you inspect and compare chart template and also rendered manifest
* [werf](https://werf.io/) - A CLI tool for implementing CI/CD best practices using an extended version of Helm under the hood for deployment


Community
---------
Forums, discussion groups, SO tags.

* [Helm Slack](http://slack.k8s.io/) - #helm-users channel on Kubernetes Slack
* [StackOverflow Kubernetes-Helm](https://stackoverflow.com/questions/tagged/kubernetes-helm) - Stack Overflow threads tagged kubernetes-helm
* [StackOverflow Helm](https://stackoverflow.com/questions/tagged/helm) - Stack Overflow threads tagged Helm

Contributing
=======================================================================

Contributions are most welcome!

Check out the [Contributing Guidelines](../CONTRIBUTING.md).



If you have any additional resources or links that you believe would benefit others, please feel free to contribute. Our goal is to create a repository of the best learning materials, ensuring everyone has access to top-notch content.

We appreciate your visit to this repository. If you find our initiatives valuable, kindly star this repository to show your support.

Thank you once again, and happy learning!