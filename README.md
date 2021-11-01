[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/terrytangyuan/awesome-argo)
[![Twitter Follow](https://img.shields.io/twitter/follow/argoproj?style=social)](https://twitter.com/argoproj)
[![Slack](https://img.shields.io/badge/slack-argoproj-brightgreen.svg?logo=slack)](https://argoproj.github.io/community/join-slack)

# Awesome Argo

A curated list of awesome projects and resources related to [Argo](https://argoproj.github.io/), a [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) hosted project.

![Argo Image](https://github.com/argoproj/argoproj/blob/master/docs/assets/argo.png)

## What is Argo?

Argo consists of a set of open source tools for deploying and running applications and workloads on Kubernetes, including:
* [Argo Workflows](https://argoproj.github.io/workflows/): Kubernetes-native workflow engine supporting DAG and step-based workflows.
* [Argo CD](https://argoproj.github.io/cd/): Declarative continuous delivery with a fully-loaded UI.
* [Argo Rollouts](https://argoproj.github.io/rollouts/): Advanced Kubernetes deployment strategies such as Canary and Blue-Green made easy.
* [Argo Events](https://argoproj.github.io/events/): Event based dependency management for Kubernetes.

In addition, [argoproj-labs](https://github.com/argoproj-labs) is a separate GitHub org for community contributions related to the Argo ecosystem.

## Table of Contents

<!-- MarkdownTOC depth=4 -->
- [Ecosystem Projects](#ecosystem-projects)
- [Books](#books)
- [Blog posts](#blogs)
- [Videos](#videos)
- [Community](#community)
- [Acknowledgement](#acknowledgement)

<!-- /MarkdownTOC -->

<a name="ecosystem-projects" />

## Ecosystem Projects

This section includes selected projects from [argoproj-labs](https://github.com/argoproj-labs) as well as other open source projects that use Argo.

* [GitOps Engine](https://github.com/argoproj/gitops-engine) contains various GitOps operators that address different use-cases and provide different user experiences but all have similar set of core features.
* [Argo CD Notifications](https://github.com/argoproj-labs/argocd-notifications) continuously monitors Argo CD applications and provides a flexible way to notify users about important changes in the applications state.
* [Argo CD ApplicationSet](https://github.com/argoproj-labs/applicationset) manages multiple Argo CD Applications as a single ApplicationSet unit, supporting deployments to large numbers of clusters, deployments of large monorepos, and enabling secure Application self-service.
* [Argo CD Image Updater](https://github.com/argoproj-labs/argocd-image-updater) is a tool to automatically update the container images of Kubernetes workloads which are managed by Argo CD.
* [Argo CD Operator](https://github.com/argoproj-labs/argocd-operator) is a Kubernetes operator for managing Argo CD clusters.
* [Argo CD Extensions](https://github.com/argoproj-labs/argocd-extensions) enables extensions for Argo CD.
* [Argo Rollout Extension](https://github.com/argoproj-labs/rollout-extension) contains the Argo Rollout dashboard that can be added into the Argo CD Web UI.
* [Argo Dataflow](https://github.com/argoproj-labs/argo-dataflow) is a Kubernetes-native platform for executing large parallel data-processing pipelines.
* [Couler](https://github.com/couler-proj/couler) provides a unified interface for constructing and managing workflows on different workflow engines.
* [Katib](https://github.com/kubeflow/katib) is a Kubernetes-native project for automated machine learning (AutoML).
* [Kedro](https://github.com/quantumblacklabs/kedro) is an open-source Python framework for creating reproducible, maintainable and modular data science code.
* [Kubeflow Pipelines](https://github.com/kubeflow/pipelines) is a machine learning (ML) toolkit that is dedicated to making deployments of ML workflows on Kubernetes simple, portable, and scalable with Kubeflow.
* [Onepanel](https://github.com/onepanelio/onepanel) is the open source, end-to-end computer vision platform.
* [Ploomber](https://github.com/ploomber/ploomber) helps overcome the challenges of working with Jupyter notebooks and allows teams to develop collaborative, production-ready pipelines using JupyterLab or any text editor.
* [Seldon](https://github.com/SeldonIO/seldon-core) is an MLOps framework to package, deploy, monitor and manage thousands of production machine learning models.
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow) extends SQL to support AI and compiles the SQL program to a workflow that runs on Kubernetes.
* [Hera Workflows](https://github.com/argoproj-labs/hera-workflows) is an Argo Workflows Python SDK that aims to make workflow construction and submission easy and accessible to everyone.

<a name="books" />

## Books

* [GitOps and Kubernetes](https://www.manning.com/books/gitops-and-kubernetes) teaches you how to use Git and the GitOps methodology to manage a Kubernetes cluster. The book interleaves theory with practice, presenting core Ops concepts alongside easy-to-implement techniques so you can put GitOps into action. Learn to develop pipelines that trace changes, roll back mistakes, and audit container deployment.
* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns) teaches you how to take machine learning models from your personal laptop to large distributed clusters. You’ll explore key concepts and patterns behind successful distributed machine learning systems, and learn technologies like TensorFlow, Kubernetes, Kubeflow, and Argo Workflows with real-world scenarios and hands-on projects.

<a name="blogs" />

## Blog Posts

* [Official Argo Project Blog](https://blog.argoproj.io/)
* [GitOps Model for Provisioning and Bootstrapping Amazon EKS Clusters Using Crossplane and Argo CD](https://aws.amazon.com/blogs/containers/gitops-model-for-provisioning-and-bootstrapping-amazon-eks-clusters-using-crossplane-and-argo-cd/)
* [Argo Ansible role: Provisioning Argo Workflows on OpenShift](https://medium.com/@marekermk/provisioning-argo-on-openshift-with-ansible-and-kustomize-340a1fda8b50)
* [Argo Workflows vs Apache Airflow](http://bit.ly/30YNIvT)
* [CI/CD with Argo on Kubernetes](https://medium.com/@bouwe.ceunen/ci-cd-with-argo-on-kubernetes-28c1a99616a9)
* [Running Argo Workflows Across Multiple Kubernetes Clusters](https://admiralty.io/blog/running-argo-workflows-across-multiple-kubernetes-clusters/)
* [Open Source Model Management Roundup: Polyaxon, Argo, and Seldon](https://www.anaconda.com/blog/developer-blog/open-source-model-management-roundup-polyaxon-argo-and-seldon/)
* [Producing 200 OpenStreetMap Extracts in 35 Minutes Using a Scalable Data Workflow](https://www.interline.io/blog/scaling-openstreetmap-data-workflows/)
* [Argo Integration Review](http://dev.matt.hillsdon.net/2018/03/24/argo-integration-review.html)
* [Creating Temporary Preview Environments Based On Pull Requests With Argo CD And Codefresh](https://codefresh.io/continuous-deployment/creating-temporary-preview-environments-based-pull-requests-argo-cd-codefresh/)
* [Comparison of Argo CD, Spinnaker, Jenkins X, and Tekton](https://www.inovex.de/blog/spinnaker-vs-argo-cd-vs-tekton-vs-jenkins-x/)
* [Simplify and Automate Deployments Using GitOps with IBM Multicloud Manager 3.1.2](https://www.ibm.com/cloud/blog/simplify-and-automate-deployments-using-gitops-with-ibm-multicloud-manager-3-1-2)
* [GitOps for Kubeflow using Argo CD](https://v0-6.kubeflow.org/docs/use-cases/gitops-for-kubeflow/)
* [GitOps Toolsets on Kubernetes with CircleCI and Argo CD](https://www.digitalocean.com/community/tutorials/webinar-series-gitops-tool-sets-on-kubernetes-with-circleci-and-argo-cd)
* [GitOps Deployment and Kubernetes - using Argo CD](https://medium.com/riskified-technology/gitops-deployment-and-kubernetes-f1ab289efa4b)
* [Deploy Argo CD with Ingress and TLS in Three Steps: No YAML Yak Shaving Required](https://itnext.io/deploy-argo-cd-with-ingress-and-tls-in-three-steps-no-yaml-yak-shaving-required-bc536d401491)
* [Stay Up to Date With Argo CD and Renovate](https://mjpitz.com/blog/2020/12/03/renovate-your-gitops/)
* [Setting up Argo CD with Helm](https://www.arthurkoziel.com/setting-up-argocd-with-helm/)
* [Applied GitOps with Argo CD](https://thenewstack.io/applied-gitops-with-argocd/)
* [Solving Configuration Drift Using GitOps with Argo CD](https://www.cncf.io/blog/2020/12/17/solving-configuration-drift-using-gitops-with-argo-cd/)
* [Decentralized GitOps Over Environments](https://blogs.sap.com/2021/05/06/decentralized-gitops-over-environments/)
* [How GitOps and Operators Mark the Rise of Infrastructure-As-Software](https://paytmlabs.com/blog/2021/10/how-to-improve-operational-work-with-operators-and-gitops/)
* [Designing A Complete CI/CD Pipeline CI/CD Pipeline Using Argo Events, Workflows, and CD](https://www.slideshare.net/JulianMazzitelli/designing-a-complete-ci-cd-pipeline-using-argo-events-workflow-and-cd-products-228452500)
* [Minimize Failed Deployments with Argo Rollouts and Smoke Tests](https://codefresh.io/continuous-deployment/minimize-failed-deployments-argo-rollouts-smoke-tests/)
* [Recover Automatically from Failed Deployments with Argo Rollouts and Prometheus Metrics](https://codefresh.io/continuous-deployment/recover-automatically-from-failed-deployments/)
* [Gradual Code Releases Using an In-House Kubernetes Canary Controller on Top of Argo Rollouts](https://doordash.engineering/2021/04/14/gradual-code-releases-using-an-in-house-kubernetes-canary-controller/)


<a name="videos" />

## Videos

* [Official Argo Project YouTube Channel](https://www.youtube.com/channel/UCOvYmppcbOPm1viN6ust3lA)
* [Making Complex R Forecast Applications Into Production Using Argo Workflows](https://www.youtube.com/watch?v=fPjztsUXHcg)
* [Automation of Everything - How To Combine Argo Events, Workflows & Pipelines, CD, and Rollouts](https://youtu.be/XNXJtxkUKeY)
* [Argo Workflows and Pipelines - CI/CD, Machine Learning, and Other Kubernetes Workflows](https://youtu.be/UMaivwrAyTA)
* [TGI Kubernetes with Joe Beda: Argo Workflow System](https://www.youtube.com/watch?v=M_rxPPLG8pU&start=859)
* [GitOps Without Pipelines With ArgoCD Image Updater](https://youtu.be/avPUQin9kzU)
* [Combining Argo CD (GitOps), Crossplane (Control Plane), and KubeVela (OAM)](https://youtu.be/eEcgn_gU3SM)
* [How to Apply GitOps to Everything - Combining Argo CD and Crossplane](https://youtu.be/yrj4lmScKHQ)
* [Couchbase - How To Run a Database Cluster in Kubernetes Using Argo CD](https://youtu.be/nkPoPaVzExY)
* [Environments Based On Pull Requests (PRs): Using Argo CD To Apply GitOps Principles On Previews](https://youtu.be/cpAaI8p4R60)
* [Argo CD: Applying GitOps Principles To Manage Production Environment In Kubernetes](https://youtu.be/vpWQeoaiRM4)
* [Tutorial: Everything You Need To Become A GitOps Ninja](https://www.youtube.com/watch?v=r50tRQjisxw)
* [CI/CD in Light Speed with K8s and Argo CD](https://www.youtube.com/watch?v=OdzH82VpMwI&feature=youtu.be)
* [Machine Learning as Code: GitOps for ML with Kubeflow and ArgoCD](https://www.youtube.com/watch?v=VXrGp5er1ZE&t=0s&index=135&list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU)
* [Argo CD - GitOps Continuous Delivery for Kubernetes](https://www.youtube.com/watch?v=aWDIQMbp1cc&feature=youtu.be&t=1m4s)
* [Introduction to Argo CD : Kubernetes DevOps CI/CD](https://www.youtube.com/watch?v=2WSJF7d8dUg&feature=youtu.be)
[GitOps Continuous Delivery with Argo and Codefresh](https://codefresh.io/events/cncf-member-webinar-gitops-continuous-delivery-argo-codefresh/)
* [Argo Events - Event-Based Dependency Manager for Kubernetes](https://youtu.be/sUPkGChvD54)
* [Argo Events Deep-dive](https://youtu.be/U4tCYcCK20w)
* [Automating Research Workflows at BlackRock](https://www.youtube.com/watch?v=ZK510prml8o)
* [TGI Kubernetes with Joe Beda: CloudEvents and Argo Events](https://www.youtube.com/watch?v=LQbBgQnUs_k&list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa&index=2&t=0s)
* [Argo Rollouts - Canary Deployments Made Easy In Kubernetes](https://youtu.be/84Ky0aPbHvY)
* [How Intuit Does Canary and Blue Green Deployments](https://www.youtube.com/watch?v=yeVkTTO9nOA)
* [Leveling Up Your CD: Unlocking Progressive Delivery on Kubernetes](https://www.youtube.com/watch?v=Nv0PPwbIEkY)
* [Kubernetes Blue-Green deployments with Argo Rollouts](https://www.youtube.com/watch?v=krDxDz4V4Tg)
* [Kubernetes Canary Deployments with Argo Rollouts](https://www.youtube.com/watch?v=fviYWA2mcF8)
* [GitOps with Argo CD and an Argo Rollouts Canary Release](https://www.youtube.com/watch?v=35Qimb_AZ8U)
* [Multi-Stage Delivery with Keptn and Argo Rollouts](https://www.youtube.com/watch?v=w-E8FzTbN3g&t=1s)


<a name="community" />

## Community

* [Argo Community Calendar](https://calendar.google.com/calendar/embed?src=argoproj@gmail.com) ([ICS File](https://calendar.google.com/calendar/ical/argoproj%40gmail.com/public/basic.ics))
* [Argo Project GitHub Organization](https://github.com/argoproj)
* [Community Governance](https://github.com/argoproj/argoproj/blob/master/community/GOVERNANCE.md)
* [Argo at Conferences](https://docs.google.com/document/d/1VWiwmintCq7cdoZaW8D49JpEWbLJ6PrOWQNELRg1ALg/edit?usp=sharing)
* [ArgoCon](https://argoproj.github.io/argocon21/)
* [Slack](https://argoproj.github.io/community/join-slack)
* [Twitter](https://twitter.com/argoproj)
* [Reddit](https://www.reddit.com/r/argoproj/)



<a name="acknowledgement" />

## Acknowledgement

Some of the blogposts and videos are selected from [Argo's community blogs and presentations](https://github.com/argoproj/argoproj#community-blogs-and-presentations).

Thanks to the contributors who've submitted pull requests to add the original references to the following locations:
* [Argo Workflows](https://github.com/argoproj/argo-workflows/blob/master/README.md#community-blogs-and-presentations)
* [Argo CD](https://github.com/argoproj/argo-cd/blob/master/README.md#community-blogs-and-presentations)
* [Argo Events](https://github.com/argoproj/argo-events/blob/master/README.md#community-blogs-and-presentations)
* [Argo Rollouts](https://github.com/argoproj/argo-rollouts/blob/master/README.md#community-blogs-and-presentations)
