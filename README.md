# Awesome Argo  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/terrytangyuan/awesome-argo)

A curated list of awesome projects and resources related to [Argo](https://argoproj.github.io/), a [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) hosted project.

## What is Argo?

Argo consists of a set of open source tools for Kubernetes to run workflows, manage clusters, and do GitOps right, including:
* [Argo Workflows](https://argoproj.github.io/workflows/): Kubernetes-native workflow engine supporting DAG and step-based workflows.
* [Argo CD](https://argoproj.github.io/cd/): Declarative continuous delivery with a fully-loaded UI.
* [Argo Rollouts](https://argoproj.github.io/rollouts/): Advanced Kubernetes deployment strategies such as Canary and Blue-Green made easy.
* [Argo Events](https://argoproj.github.io/events/): Event based dependency management for Kubernetes.

In addition, [argoproj-labs](https://github.com/argoproj-labs) is a separate GitHub org for community contributions related to the Argo ecosystem.

## Table of Contents

<!-- MarkdownTOC depth=4 -->
- [Projects](#projects)
- [Books](#books)
- [Blog posts](#blogs)
- [Videos](#videos)
- [Community](#community)
- [Acknowledgement](#acknowledgement)

<!-- /MarkdownTOC -->

<a name="projects" />

## Projects

* [GitOps Engine](https://github.com/argoproj/gitops-engine)
* [Notifications for Argo CD](https://github.com/argoproj-labs/argocd-notifications)
* [Argo CD ApplicationSet](https://github.com/argoproj-labs/applicationset)
* [Argo CD Image Updater](https://github.com/argoproj-labs/argocd-image-updater)
* [Argo CD Operator](https://github.com/argoproj-labs/argocd-operator)
* [Argo CD Extensions](https://github.com/argoproj-labs/argocd-extensions)
* [Argo Rollout Extension](https://github.com/argoproj-labs/rollout-extension)
* [Argo Dataflow](https://github.com/argoproj-labs/argo-dataflow)
* [Couler](https://github.com/couler-proj/couler)
* [Katib](https://github.com/kubeflow/katib)
* [Kedro](https://kedro.readthedocs.io/en/stable/)
* [Kubeflow Pipelines](https://github.com/kubeflow/pipelines)
* [Onepanel](https://www.onepanel.ai/)
* [Ploomber](https://github.com/ploomber/ploomber)
* [Seldon](https://github.com/SeldonIO/seldon-core)
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow)
* [Hera Workflows](https://github.com/argoproj-labs/hera-workflows)

<a name="books" />

## Books

* [GitOps and Kubernetes](https://www.manning.com/books/gitops-and-kubernetes)
* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns)

<a name="blogs" />

## Blog Posts

* [Official Argo Blog](https://blog.argoproj.io/)
* [Argo Ansible role: Provisioning Argo Workflows on OpenShift](https://medium.com/@marekermk/provisioning-argo-on-openshift-with-ansible-and-kustomize-340a1fda8b50)
* [Argo Workflows vs Apache Airflow](http://bit.ly/30YNIvT)
* [CI/CD with Argo on Kubernetes](https://medium.com/@bouwe.ceunen/ci-cd-with-argo-on-kubernetes-28c1a99616a9)
* [Running Argo Workflows Across Multiple Kubernetes Clusters](https://admiralty.io/blog/running-argo-workflows-across-multiple-kubernetes-clusters/)
* [Open Source Model Management Roundup: Polyaxon, Argo, and Seldon](https://www.anaconda.com/blog/developer-blog/open-source-model-management-roundup-polyaxon-argo-and-seldon/)
* [Producing 200 OpenStreetMap extracts in 35 minutes using a scalable data workflow](https://www.interline.io/blog/scaling-openstreetmap-data-workflows/)
* [Argo integration review](http://dev.matt.hillsdon.net/2018/03/24/argo-integration-review.html)
* [Creating Temporary Preview Environments Based On Pull Requests With Argo CD And Codefresh](https://codefresh.io/continuous-deployment/creating-temporary-preview-environments-based-pull-requests-argo-cd-codefresh/)
* [Comparison of Argo CD, Spinnaker, Jenkins X, and Tekton](https://www.inovex.de/blog/spinnaker-vs-argo-cd-vs-tekton-vs-jenkins-x/)
* [Simplify and Automate Deployments Using GitOps with IBM Multicloud Manager 3.1.2](https://www.ibm.com/cloud/blog/simplify-and-automate-deployments-using-gitops-with-ibm-multicloud-manager-3-1-2)
* [GitOps for Kubeflow using Argo CD](https://v0-6.kubeflow.org/docs/use-cases/gitops-for-kubeflow/)
* [GitOps Toolsets on Kubernetes with CircleCI and Argo CD](https://www.digitalocean.com/community/tutorials/webinar-series-gitops-tool-sets-on-kubernetes-with-circleci-and-argo-cd)
* [GitOps Deployment and Kubernetes - using Argo CD](https://medium.com/riskified-technology/gitops-deployment-and-kubernetes-f1ab289efa4b)
* [Deploy Argo CD with Ingress and TLS in Three Steps: No YAML Yak Shaving Required](https://itnext.io/deploy-argo-cd-with-ingress-and-tls-in-three-steps-no-yaml-yak-shaving-required-bc536d401491)
* [Stay up to date with Argo CD and Renovate](https://mjpitz.com/blog/2020/12/03/renovate-your-gitops/)
* [Setting up Argo CD with Helm](https://www.arthurkoziel.com/setting-up-argocd-with-helm/)
* [Applied GitOps with Argo CD](https://thenewstack.io/applied-gitops-with-argocd/)
* [Solving configuration drift using GitOps with Argo CD](https://www.cncf.io/blog/2020/12/17/solving-configuration-drift-using-gitops-with-argo-cd/)
* [Decentralized GitOps over environments](https://blogs.sap.com/2021/05/06/decentralized-gitops-over-environments/)
* [How GitOps and Operators mark the rise of Infrastructure-As-Software](https://paytmlabs.com/blog/2021/10/how-to-improve-operational-work-with-operators-and-gitops/)
* * [Designing A Complete CI/CD Pipeline CI/CD Pipeline Using Argo Events, Workflows, and CD](https://www.slideshare.net/JulianMazzitelli/designing-a-complete-ci-cd-pipeline-using-argo-events-workflow-and-cd-products-228452500)
* [Minimize failed deployments with Argo Rollouts and Smoke tests](https://codefresh.io/continuous-deployment/minimize-failed-deployments-argo-rollouts-smoke-tests/)
* [Recover automatically from failed deployments with Argo Rollouts and Prometheus metrics](https://codefresh.io/continuous-deployment/recover-automatically-from-failed-deployments/)
* [Gradual Code Releases Using an In-House Kubernetes Canary Controller on top of Argo Rollouts](https://doordash.engineering/2021/04/14/gradual-code-releases-using-an-in-house-kubernetes-canary-controller/)


<a name="videos" />

## Videos

* [Automation of Everything - How To Combine Argo Events, Workflows & Pipelines, CD, and Rollouts](https://youtu.be/XNXJtxkUKeY)
* [Argo Workflows and Pipelines - CI/CD, Machine Learning, and Other Kubernetes Workflows](https://youtu.be/UMaivwrAyTA)
* TGI Kubernetes with Joe Beda: [Argo workflow system](https://www.youtube.com/watch?v=M_rxPPLG8pU&start=859)
* [GitOps Without Pipelines With ArgoCD Image Updater](https://youtu.be/avPUQin9kzU)
* [Combining Argo CD (GitOps), Crossplane (Control Plane), And KubeVela (OAM)](https://youtu.be/eEcgn_gU3SM)
* [How to Apply GitOps to Everything - Combining Argo CD and Crossplane](https://youtu.be/yrj4lmScKHQ)
* [Couchbase - How To Run a Database Cluster in Kubernetes Using Argo CD](https://youtu.be/nkPoPaVzExY)
* [Environments Based On Pull Requests (PRs): Using Argo CD To Apply GitOps Principles On Previews](https://youtu.be/cpAaI8p4R60)
* [Argo CD: Applying GitOps Principles To Manage Production Environment In Kubernetes](https://youtu.be/vpWQeoaiRM4)
* [Tutorial: Everything You Need To Become A GitOps Ninja](https://www.youtube.com/watch?v=r50tRQjisxw) 90m tutorial on GitOps and Argo CD.
* [CI/CD in Light Speed with K8s and Argo CD](https://www.youtube.com/watch?v=OdzH82VpMwI&feature=youtu.be)
* [Machine Learning as Code](https://www.youtube.com/watch?v=VXrGp5er1ZE&t=0s&index=135&list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU). Among other things, describes how Kubeflow uses Argo CD to implement GitOPs for ML.
* [Argo CD - GitOps Continuous Delivery for Kubernetes](https://www.youtube.com/watch?v=aWDIQMbp1cc&feature=youtu.be&t=1m4s)
* [Introduction to Argo CD : Kubernetes DevOps CI/CD](https://www.youtube.com/watch?v=2WSJF7d8dUg&feature=youtu.be)
[GitOps Continuous Delivery with Argo and Codefresh](https://codefresh.io/events/cncf-member-webinar-gitops-continuous-delivery-argo-codefresh/)
* [Argo Events - Event-Based Dependency Manager for Kubernetes](https://youtu.be/sUPkGChvD54)
* [Argo Events Deep-dive](https://youtu.be/U4tCYcCK20w)
* [Automating Research Workflows at BlackRock](https://www.youtube.com/watch?v=ZK510prml8o)
* TGI Kubernetes with Joe Beda: [CloudEvents and Argo Events](https://www.youtube.com/watch?v=LQbBgQnUs_k&list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa&index=2&t=0s)
* [Argo Rollouts - Canary Deployments Made Easy In Kubernetes](https://youtu.be/84Ky0aPbHvY)
* [How Intuit Does Canary and Blue Green Deployments](https://www.youtube.com/watch?v=yeVkTTO9nOA)
* [Leveling Up Your CD: Unlocking Progressive Delivery on Kubernetes](https://www.youtube.com/watch?v=Nv0PPwbIEkY)
* [Kubernetes Blue-Green deployments with Argo Rollouts](https://www.youtube.com/watch?v=krDxDz4V4Tg)
* [Kubernetes canary deployments with Argo Rollouts](https://www.youtube.com/watch?v=fviYWA2mcF8)
* [GitOps with Argo CD and an Argo Rollouts canary release](https://www.youtube.com/watch?v=35Qimb_AZ8U)
* [Multi-Stage Delivery with Keptn and Argo Rollouts](https://www.youtube.com/watch?v=w-E8FzTbN3g&t=1s)


<a name="community" />

## Community

* [Argo Community Calendar](https://calendar.google.com/calendar/embed?src=argoproj@gmail.com)([ICS file](https://calendar.google.com/calendar/ical/argoproj%40gmail.com/public/basic.ics))
* [Community governance](https://github.com/argoproj/argoproj/blob/master/community/GOVERNANCE.md)
* [Slack](https://argoproj.github.io/community/join-slack)
* [Twitter](https://twitter.com/argoproj)
* [Reddit](https://www.reddit.com/r/argoproj/)


<a name="acknowledgement" />

## Acknowledgement

* Some of the references are originally documented in [Argo's community blogs and presentations](https://github.com/argoproj/argoproj#community-blogs-and-presentations). Thanks to the contributors who've submitted pull requests to add the references, specially:
	* [Argo Workflows](https://github.com/argoproj/argo-workflows/blob/master/README.md#community-blogs-and-presentations)
	* [Argo CD](https://github.com/argoproj/argo-cd/blob/master/README.md#community-blogs-and-presentations)
	* [Argo Events](https://github.com/argoproj/argo-events/blob/master/README.md#community-blogs-and-presentations)
	* [Argo Rollouts](https://github.com/argoproj/argo-rollouts/blob/master/README.md#community-blogs-and-presentations)
