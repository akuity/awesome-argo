[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/terrytangyuan/awesome-argo)
[![Twitter Follow](https://img.shields.io/twitter/follow/argoproj?style=social)](https://twitter.com/argoproj)
[![Slack](https://img.shields.io/badge/slack-argoproj-brightgreen.svg?logo=slack)](https://argoproj.github.io/community/join-slack)

# Awesome Argo

A curated list of awesome projects and resources related to [Argo](https://argoproj.github.io/), a [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) hosted project.

![Argo Image](images/argo.png)

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
- [Blog Posts](#blogs)
- [Videos](#videos)
- [Community](#community)
- [Acknowledgement](#acknowledgement)

<!-- /MarkdownTOC -->


<a name="ecosystem-projects" />

## Ecosystem Projects

Selected projects from [argoproj](https://github.com/argoproj) (other than the four projects mentioned above) and [argoproj-labs](https://github.com/argoproj-labs):

* [Argo CD ApplicationSet](https://github.com/argoproj-labs/applicationset) manages multiple Argo CD Applications as a single ApplicationSet unit, supporting deployments to large numbers of clusters, deployments of large monorepos, and enabling secure Application self-service.
* [Argo CD Autopilot](https://github.com/argoproj-labs/argocd-autopilot) offers an opinionated way of installing Argo CD and managing GitOps repositories.
* [Argo CD Extensions](https://github.com/argoproj-labs/argocd-extensions) enables extensions for Argo CD.
* [Argo CD Image Updater](https://github.com/argoproj-labs/argocd-image-updater) is a tool to automatically update the container images of Kubernetes workloads which are managed by Argo CD.
* [Argo CD Notifications](https://github.com/argoproj-labs/argocd-notifications) continuously monitors Argo CD applications and provides a flexible way to notify users about important changes in the applications state.
* [Argo CD Operator](https://github.com/argoproj-labs/argocd-operator) is a Kubernetes operator for managing Argo CD clusters.
* [Argo CD Vault Plugin](https://github.com/argoproj-labs/argocd-vault-plugin) is an Argo CD plugin to retrieve secrets from Secret Management tools and inject them into Kubernetes resources.
* [Argo CloudOps](https://github.com/argoproj-labs/argo-cloudops) is a service for running infrastructure as code software tools including CDK, Terraform and Cloud Formation via GitOps.
* [Argo Dataflow](https://github.com/argoproj-labs/argo-dataflow) is a Kubernetes-native platform for executing large parallel data-processing pipelines.
* [Argo Helm](https://github.com/argoproj/argo-helm) is a collection of community maintained Helm charts for Argo projects.
* [Argo Rollout Extension](https://github.com/argoproj-labs/rollout-extension) contains the Argo Rollout dashboard that can be added into the Argo CD Web UI.
* [Argo Workflows Catalog](https://github.com/argoproj-labs/argo-workflows-catalog) contains free reusable templates for Argo Workflows.
* [GitOps Engine](https://github.com/argoproj/gitops-engine) contains various GitOps operators that address different use-cases and provide different user experiences but all have similar set of core features.
* [Hera](https://github.com/argoproj-labs/hera-workflows) is an Argo Workflows Python SDK that aims to make workflow construction and submission easy and accessible to everyone.
* [Notifications Engine](https://github.com/argoproj/notifications-engine) is a configuration-driven Golang library that provides notifications for cloud-native applications.


Other open source projects that use Argo:

* [active-monitor](https://github.com/keikoproj/active-monitor) is a Kubernetes controller which enables deep cluster monitoring and self-healing using Argo Workflows.
* [argocd-commenter](https://github.com/int128/argocd-commenter) is a Kubernetes controller to notify a change of Argo CD Application status via comments on GitHub pull requests and GitHub Deployments.
* [argocd-interlace](https://github.com/IBM/argocd-interlace) is a Kubernetes controller to enable software supply chain security capabilities in Argo CD.
* [argoflow](https://github.com/argoflow/argoflow) provides a fully declarative and GitOps approach to deploy and maintain your Kubeflow distribution with Argo CD.
* [Couler](https://github.com/couler-proj/couler) provides a unified interface for constructing and managing workflows on different workflow engines.
* [Kedro](https://github.com/quantumblacklabs/kedro) is an open-source Python framework for creating reproducible, maintainable and modular data science code.
* [Kubeflow Katib](https://github.com/kubeflow/katib) is a Kubernetes-native project for automated machine learning (AutoML).
* [Kubeflow Pipelines](https://github.com/kubeflow/pipelines) is dedicated to making deployments of machine learning workflows on Kubernetes simple, portable, and scalable with Kubeflow.
* [Onepanel](https://github.com/onepanelio/onepanel) is the open source, end-to-end computer vision platform.
* [provider-argocd](https://github.com/crossplane-contrib/provider-argocd) is the Crossplane infrastructure provider for Argo CD.
* [Ploomber](https://github.com/ploomber/ploomber) helps overcome the challenges of working with Jupyter notebooks and allows teams to develop collaborative, production-ready pipelines using JupyterLab or any text editor.
* [Seldon](https://github.com/SeldonIO/seldon-core) is an MLOps framework to package, deploy, monitor and manage thousands of production machine learning models.
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow) extends SQL to support AI and compiles the SQL program to a workflow that runs on Kubernetes.
* [terraform-provider-argocd](https://github.com/oboukili/terraform-provider-argocd) is the Terraform provider for Argo CD.
* [Azure Orkestra](https://github.com/Azure/orkestra) is a cloud-native release orchestration and lifecycle management (LCM) platform for the fine-grained orchestration of inter-dependent helm charts and their dependencies

<a name="books" />

## Books

* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns) teaches you how to take machine learning models from your personal laptop to large distributed clusters. You’ll explore key concepts and patterns behind successful distributed machine learning systems, and learn technologies like TensorFlow, Kubernetes, Kubeflow, and Argo Workflows with real-world scenarios and hands-on projects.
* [GitOps and Kubernetes](https://www.manning.com/books/gitops-and-kubernetes) teaches you how to use Git and the GitOps methodology to manage a Kubernetes cluster. The book interleaves theory with practice, presenting core Ops concepts alongside easy-to-implement techniques so you can put GitOps into action. Learn to develop pipelines that trace changes, roll back mistakes, and audit container deployment.


<a name="blogs" />

## Blog Posts

Please check out the [official Argo Project blog](https://blog.argoproj.io/). Additional links:

* [Applied GitOps with Argo CD](https://thenewstack.io/applied-gitops-with-argocd/)
* [Argo Ansible Role: Provisioning Argo Workflows on OpenShift](https://medium.com/@marekermk/provisioning-argo-on-openshift-with-ansible-and-kustomize-340a1fda8b50)
* [Argo Integration Review](http://dev.matt.hillsdon.net/2018/03/24/argo-integration-review.html)
* [Argo Workflows vs Apache Airflow](http://bit.ly/30YNIvT)
* [Building a Successful Open Source Community as an End User Company](https://medium.com/intuit-engineering/building-a-successful-open-source-community-as-an-end-user-company-89a70445134)
* [CI/CD with Argo on Kubernetes](https://medium.com/@bouwe.ceunen/ci-cd-with-argo-on-kubernetes-28c1a99616a9)
* [Comparison of Argo CD, Spinnaker, Jenkins X, and Tekton](https://www.inovex.de/blog/spinnaker-vs-argo-cd-vs-tekton-vs-jenkins-x/)
* [Creating Temporary Preview Environments Based On Pull Requests With Argo CD And Codefresh](https://codefresh.io/continuous-deployment/creating-temporary-preview-environments-based-pull-requests-argo-cd-codefresh/)
* [Decentralized GitOps Over Environments](https://blogs.sap.com/2021/05/06/decentralized-gitops-over-environments/)
* [Deploy Argo CD with Ingress and TLS in Three Steps: No YAML Yak Shaving Required](https://itnext.io/deploy-argo-cd-with-ingress-and-tls-in-three-steps-no-yaml-yak-shaving-required-bc536d401491)
* [Designing A Complete CI/CD Pipeline CI/CD Pipeline Using Argo Events, Workflows, and CD](https://www.slideshare.net/JulianMazzitelli/designing-a-complete-ci-cd-pipeline-using-argo-events-workflow-and-cd-products-228452500)
* [Flux vs ArgoCD](https://gatsby-casper.netlify.com/2021-10-28-flux-vs-argocd/)
* [GitOps Deployment and Kubernetes - using Argo CD](https://medium.com/riskified-technology/gitops-deployment-and-kubernetes-f1ab289efa4b)
* [GitOps for Kubeflow using Argo CD](https://v0-6.kubeflow.org/docs/use-cases/gitops-for-kubeflow/)
* [GitOps Model for Provisioning and Bootstrapping Amazon EKS Clusters Using Crossplane and Argo CD](https://aws.amazon.com/blogs/containers/gitops-model-for-provisioning-and-bootstrapping-amazon-eks-clusters-using-crossplane-and-argo-cd/)
* [GitOps Toolsets on Kubernetes with CircleCI and Argo CD](https://www.digitalocean.com/community/tutorials/webinar-series-gitops-tool-sets-on-kubernetes-with-circleci-and-argo-cd)
* [Gradual Code Releases Using an In-House Kubernetes Canary Controller on Top of Argo Rollouts](https://doordash.engineering/2021/04/14/gradual-code-releases-using-an-in-house-kubernetes-canary-controller/)
* [How GitOps and Operators Mark the Rise of Infrastructure-As-Software](https://paytmlabs.com/blog/2021/10/how-to-improve-operational-work-with-operators-and-gitops/)
* [Introducing Couler: Unified Interface for Constructing and Managing Workflows](https://github.com/terrytangyuan/public-talks/tree/main/talks/introducing-couler-unified-interface-for-constructing-and-managing-workflows-argo-workflows-community-meeting)
* [Jenkins X 3 and Argo CD](https://jenkins-x.io/blog/2021/06/28/argo/)
* [Machine Learning Hyperparameter Optimization with Argo](https://canvatechblog.com/machine-learning-hyperparameter-optimization-with-argo-a60d70b1fc8c)
* [Minimize Failed Deployments with Argo Rollouts and Smoke Tests](https://codefresh.io/continuous-deployment/minimize-failed-deployments-argo-rollouts-smoke-tests/)
* [Open Source Model Management Roundup: Polyaxon, Argo, and Seldon](https://www.anaconda.com/blog/developer-blog/open-source-model-management-roundup-polyaxon-argo-and-seldon/)
* [Producing 200 OpenStreetMap Extracts in 35 Minutes Using a Scalable Data Workflow](https://www.interline.io/blog/scaling-openstreetmap-data-workflows/)
* [Recover Automatically from Failed Deployments with Argo Rollouts and Prometheus Metrics](https://codefresh.io/continuous-deployment/recover-automatically-from-failed-deployments/)
* [Running Argo Workflows Across Multiple Kubernetes Clusters](https://admiralty.io/blog/running-argo-workflows-across-multiple-kubernetes-clusters/)
* [Setting up Argo CD with Helm](https://www.arthurkoziel.com/setting-up-argocd-with-helm/)
* [Simplify and Automate Deployments Using GitOps with IBM Multicloud Manager 3.1.2](https://www.ibm.com/cloud/blog/simplify-and-automate-deployments-using-gitops-with-ibm-multicloud-manager-3-1-2)
* [Solving Configuration Drift Using GitOps with Argo CD](https://www.cncf.io/blog/2020/12/17/solving-configuration-drift-using-gitops-with-argo-cd/)
* [Stay Up to Date With Argo CD and Renovate](https://mjpitz.com/blog/2020/12/03/renovate-your-gitops/)


<a name="videos" />

## Videos

Please check out the [official Argo Project YouTube channel](https://www.youtube.com/channel/UCOvYmppcbOPm1viN6ust3lA). Additional links:

* [Argo and Tekton: Pushing the Boundaries of the Possible on Kubernetes](https://youtu.be/iPRw_n_JV4o)
* :bell: (Link TBA) Argo-Based Service Delivery for Multi-Tenant, Multi Region Clusters at Adobe
* [Argo CD: Applying GitOps Principles To Manage Production Environment In Kubernetes](https://youtu.be/vpWQeoaiRM4)
* :bell: [Argo CD and Stateful Applications - Tips and Tricks](https://youtu.be/_-oVaO4SxLk)
* [Argo CD - GitOps Continuous Delivery for Kubernetes](https://www.youtube.com/watch?v=aWDIQMbp1cc&feature=youtu.be&t=1m4s)
* :bell: (Link TBA) Argo CD Production Best Practices
* [Automation of Everything - How To Combine Argo Events, Workflows & Pipelines, CD, and Rollouts](https://youtu.be/XNXJtxkUKeY)
* [Argo Events Deep-dive](https://youtu.be/U4tCYcCK20w)
* [Argo Events - Event-Based Dependency Manager for Kubernetes](https://youtu.be/sUPkGChvD54)
* [Argo Rollouts - Canary Deployments Made Easy In Kubernetes](https://youtu.be/84Ky0aPbHvY)
* :bell: (Link TBA) Argo: The Present, Past, and Future
* [Argo Workflows and Pipelines - CI/CD, Machine Learning, and Other Kubernetes Workflows](https://youtu.be/UMaivwrAyTA)
* [Automating Research Workflows at BlackRock](https://www.youtube.com/watch?v=ZK510prml8o)
* [A Multi-Cluster, Multi-Cloud Infrastructure with GitOps at CERN](https://youtu.be/h6xDWc6fXao)
* :bell: [Bridging into Python Ecosystem with Cloud-Native Distributed Machine Learning Pipelines](https://github.com/terrytangyuan/public-talks/tree/main/talks/bridging-into-python-ecosystem-with-cloud-native-distributed-machine-learning-pipelines-argocon-2021)
* [Building a Successful Open Source Community as an End-user Company](https://youtu.be/BrZMZJc3Vh4)
* :bell: [Building Medical Grade AI with Argo Workflows](https://youtu.be/4VPSktuM5Ow)
* [CI/CD in Light Speed with K8s and Argo CD](https://www.youtube.com/watch?v=OdzH82VpMwI&feature=youtu.be)
* :bell: [Cloud-native CI/CD via ArgoCD & Workflows in Multi-region & Muti-cell Environment](https://youtu.be/IPiNWwPgsjw)
* [Combining Argo CD (GitOps), Crossplane (Control Plane), and KubeVela (OAM)](https://youtu.be/eEcgn_gU3SM)
* [Couchbase - How To Run a Database Cluster in Kubernetes Using Argo CD](https://youtu.be/nkPoPaVzExY)
* :bell: [Deploying Cluster Addons at Scale using ApplicationSets](https://youtu.be/Yj60Co4UxXk)
* :bell: (Link TBA) Deployments on the Edge using Argo CD & Workflows and K3s
* :bell: [Dynamic, Event-Driven Machine Learning Pipelines with Argo Workflows](https://youtu.be/ei4r0a7eAV0)
* [Easy Notifications for Kubernetes](https://youtu.be/gZ0MfSoHbY0)
* [Environments Based on Pull Requests (PRs): Using Argo CD To Apply GitOps Principles on Previews](https://youtu.be/cpAaI8p4R60)
* :bell: (Link TBA) Extending GitOps to Manage K8s (so you don’t have to)!
* [GitOps Cloud Resource Management](https://youtu.be/TJQHB8XVW44)
* [GitOps Guide to the Galaxy: Argo Workflows](https://www.youtube.com/watch?v=2lI41q8Z7ko)
* [GitOps with Argo CD and an Argo Rollouts Canary Release](https://www.youtube.com/watch?v=35Qimb_AZ8U)
* [GitOps Without Pipelines With ArgoCD Image Updater](https://youtu.be/avPUQin9kzU)
* [How Intuit Does Canary and Blue Green Deployments](https://www.youtube.com/watch?v=yeVkTTO9nOA)
* :bell: (Link TBA) How Scalable is Argo-Rollouts: A Cloud Operator’s Perspective
* [How to Apply GitOps to Everything - Combining Argo CD and Crossplane](https://youtu.be/yrj4lmScKHQ)
* [Introduction to Argo CD: Kubernetes DevOps CI/CD](https://www.youtube.com/watch?v=2WSJF7d8dUg&feature=youtu.be)
* :bell: (Link TBA) Journey of the Argonauts
* [Kubernetes Blue-Green Deployments with Argo Rollouts](https://www.youtube.com/watch?v=krDxDz4V4Tg)
* [Kubernetes Canary Deployments with Argo Rollouts](https://www.youtube.com/watch?v=fviYWA2mcF8)
* [Leveling Up Your CD: Unlocking Progressive Delivery on Kubernetes](https://www.youtube.com/watch?v=Nv0PPwbIEkY)
* [Level Unlocked: GitOps to the Edge and Infrastructure Provisioning](https://youtu.be/4zDm23kA8oE)
* [Litmus 2 - Chaos Engineering Meets Argo Workflows](https://youtu.be/B8DfYnDh2F4)
* [Machine Learning as Code: GitOps for ML with Kubeflow and ArgoCD](https://www.youtube.com/watch?v=VXrGp5er1ZE&t=0s&index=135&list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU)
* [Making Complex R Forecast Applications Into Production Using Argo Workflows](https://www.youtube.com/watch?v=fPjztsUXHcg)
* [Manage More Clusters with Less Hassle, with Argo CD Application Sets](https://youtu.be/GcvHKc2IHi8)
* [Multi-Stage Delivery with Keptn and Argo Rollouts](https://www.youtube.com/watch?v=w-E8FzTbN3g&t=1s)
* :bell: (Link TBA) Processing Petabytes in Python with Argo Workflows & Dask
* [Robocat Meets Octopus and Octocat: Interoperability in CI/CD](https://youtu.be/Yq5lqr6n0E8)
* :bell: (Link TBA) Scaling Kubernetes across BlackRock’s Aladdin Platform
* :bell: (Link TBA) Scaling Software Delivery on Argo
* [Shh, It’s a Secret: Managing Your Secrets in a GitOps Way](https://youtu.be/7L6nSuKbC2c)
* :bell: [Supercharge Your Dev Experience [DX] with ArgoCD, Crossplane, & Shipa](https://youtu.be/-p0sn_X2CXQ)
* [TGI Kubernetes with Joe Beda: Argo Workflow System](https://www.youtube.com/watch?v=M_rxPPLG8pU&start=859)
* [TGI Kubernetes with Joe Beda: CloudEvents and Argo Events](https://www.youtube.com/watch?v=LQbBgQnUs_k&list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa&index=2&t=0s)
* [The Argo Ecosystem: Tailoring Your Installation Through Community Add-ons](https://youtu.be/EPtiDNXpS78)
* :bell: [Unveil The Secret Ingredients for Argo CD in the Enterprise-Scale](https://github.com/terrytangyuan/public-talks/tree/main/talks/unveil-the-secret-ingredients-for-argo-cd-at-enterprise-scale-kubecon-china-2021)
* :bell: (Link TBA) The Journey from DevOps to GitOps
* [Towards Cloud-Native Distributed Machine Learning Pipelines at Scale](https://github.com/terrytangyuan/public-talks/tree/main/talks/towards-cloud-native-distributed-machine-learning-pipelines-at-scale-pydata-global-2021)
* [Tutorial: Everything You Need To Become A GitOps Ninja](https://www.youtube.com/watch?v=r50tRQjisxw)
[GitOps Continuous Delivery with Argo and Codefresh](https://codefresh.io/events/cncf-member-webinar-gitops-continuous-delivery-argo-codefresh/)



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
