[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/terrytangyuan/awesome-argo) [![Slack](https://img.shields.io/badge/slack-argoproj-brightgreen.svg?logo=slack)](https://argoproj.github.io/community/join-slack) [![Twitter Follow](https://img.shields.io/twitter/follow/argoproj?style=social)](https://twitter.com/argoproj) [![Twitter Follow](https://img.shields.io/twitter/follow/TerryTangYuan?style=social)](https://twitter.com/TerryTangYuan)

# Awesome Argo

**NEWS**:
* 🔥 [KubeCon Europe 2022 talks](#videos) are available now! ([follow updates](https://twitter.com/TerryTangYuan))

A curated list of awesome projects and resources related to [Argo](https://argoproj.github.io/), a [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) hosted project.

![Argo Image](images/argo.png)

This list is maintained and sponsored by [Akuity](https://akuity.io/), the Enterprise Company for Argo Project.

<img align="center" src="images/akuity.png" alt="akuity" width="50%" height="50%">


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
  - [Blog Posts](#blog-posts)
  - [Videos](#videos)
  - [Community](#community)
  - [Acknowledgement](#acknowledgement)

<!-- /MarkdownTOC -->


<a name="ecosystem-projects" />

## Ecosystem Projects

Selected projects from [argoproj](https://github.com/argoproj) (other than the four projects mentioned above) and [argoproj-labs](https://github.com/argoproj-labs):

* [Argo CD ApplicationSet](https://github.com/argoproj/applicationset) manages multiple Argo CD Applications as a single ApplicationSet unit, supporting deployments to large numbers of clusters, deployments of large monorepos, and enabling secure Application self-service.
* [Argo CD Autopilot](https://github.com/argoproj-labs/argocd-autopilot) offers an opinionated way of installing Argo CD and managing GitOps repositories.
* [Argo CD Extensions](https://github.com/argoproj-labs/argocd-extensions) enables extensions for Argo CD.
* [Argo CD Image Updater](https://github.com/argoproj-labs/argocd-image-updater) is a tool to automatically update the container images of Kubernetes workloads which are managed by Argo CD.
* [Argo CD Interlace](https://github.com/argoproj-labs/argocd-interlace) is a Kubernetes controller to enable software supply chain security capabilities in Argo CD.
* [Argo CD Notifications](https://github.com/argoproj-labs/argocd-notifications) continuously monitors Argo CD applications and provides a flexible way to notify users about important changes in the applications state.
* [Argo CD Operator](https://github.com/argoproj-labs/argocd-operator) is a Kubernetes operator for managing Argo CD clusters.
* [Argo CD Vault Plugin](https://github.com/argoproj-labs/argocd-vault-plugin) is an Argo CD plugin to retrieve secrets from Secret Management tools and inject them into Kubernetes resources.
* [Argo Dataflow](https://github.com/argoproj-labs/argo-dataflow) is a Kubernetes-native platform for executing large parallel data-processing pipelines.
* [Argo Helm](https://github.com/argoproj/argo-helm) is a collection of community-maintained Helm charts for Argo projects.
* [Argo Rollout Extension](https://github.com/argoproj-labs/rollout-extension) contains the Argo Rollout dashboard that can be added into the Argo CD Web UI.
* [Argo Workflows Catalog](https://github.com/argoproj-labs/argo-workflows-catalog) contains free reusable templates for Argo Workflows.
* [Argo Workflows Plugins](https://argoproj.github.io/argo-workflows/plugin-directory) contains reusable plugins that extend Argo Workflows with new capabilities.
* [GitOps Engine](https://github.com/argoproj/gitops-engine) contains various GitOps operators that address different use-cases and provide different user experiences but all have a similar set of core features.
* [Hera](https://github.com/argoproj-labs/hera-workflows) is an Argo Workflows Python SDK that aims to make workflow construction and submission easy and accessible to everyone.
* [Notifications Engine](https://github.com/argoproj/notifications-engine) is a configuration-driven Golang library that provides notifications for cloud-native applications.


Other open source projects that use Argo:

* [active-monitor](https://github.com/keikoproj/active-monitor) is a Kubernetes controller which enables deep cluster monitoring and self-healing using Argo Workflows.
* [argocd-commenter](https://github.com/int128/argocd-commenter) is a Kubernetes controller to notify a change of Argo CD Application status via comments on GitHub pull requests and GitHub Deployments.
* [argocd-lovely-plugin](https://github.com/crumbhole/argocd-lovely-plugin) is a plugin that allows you to composite multiple things together into a single argocd application or applicationSet. Includes allowing Helm+Kustomize, addition other manifests trivially and running additional plugins in a pipe.
* [backstage-plugin-argo-cd](https://www.npmjs.com/package/@roadiehq/backstage-plugin-argo-cd) is a Argo CD plugin for Backstage, an open platform for building developer portals.
* [Cello](https://github.com/cello-proj/cello) is a service for running infrastructure as code software tools including CDK, Terraform and Cloud Formation via GitOps.
* [ci-github-notifiter](https://github.com/sendible-labs/ci-github-notifier) is a lightweight container to post Argo Workflow statuses back to GitHub as [Status Checks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/collaborating-on-repositories-with-code-quality-features/about-status-checks).
* [Couler](https://github.com/couler-proj/couler) provides a unified interface for constructing and managing workflows on different workflow engines.
* [Devtron](https://github.com/devtron-labs/devtron) is a Web-Based CI/CD Platform for Kubernetes, powered by Argo.
* [Kedro](https://github.com/quantumblacklabs/kedro) is an open-source Python framework for creating reproducible, maintainable and modular data science code.
* [Kubeflow Katib](https://github.com/kubeflow/katib) is a Kubernetes-native project for automated machine learning (AutoML).
* [Kubeflow Pipelines](https://github.com/kubeflow/pipelines) is dedicated to making deployments of machine learning workflows on Kubernetes simple, portable, and scalable with Kubeflow.
* [Metaflow](https://github.com/Netflix/metaflow) is a Python library for building and managing real-life data science projects.
* [Onepanel](https://github.com/onepanelio/onepanel) is the open source, end-to-end computer vision platform.
* [Orchest](https://github.com/orchest/orchest) is a tool for building data pipelines/workflows. It supports Jupyter notebooks and scripts in multiple languages and provides a user friendly UI/browser based editor.
* [Orkestra](https://github.com/Azure/orkestra) is a cloud-native release orchestration and lifecycle management (LCM) platform for the fine-grained orchestration of inter-dependent Helm charts and their dependencies.
* [Ploomber](https://github.com/ploomber/ploomber) helps overcome the challenges of working with Jupyter notebooks and allows teams to develop collaborative, production-ready pipelines using JupyterLab or any text editor.
* [provider-argocd](https://github.com/crossplane-contrib/provider-argocd) is the Crossplane infrastructure provider for Argo CD.
* [Reloader](https://github.com/stakater/Reloader) is a Kubernetes controller to watch changes in ConfigMap and Secrets and do rolling upgrades on associated Deployments/StatefulSets/Daemonsets and Argo Rollouts.
* [Seldon](https://github.com/SeldonIO/seldon-core) is an MLOps framework to package, deploy, monitor and manage thousands of production machine learning models.
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow) extends SQL to support AI and compiles the SQL program to a workflow that runs on Kubernetes.
* [terraform-provider-argocd](https://github.com/oboukili/terraform-provider-argocd) is the Terraform provider for Argo CD.

<a name="books" />

## Books

* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns) teaches you how to take machine learning models from your personal laptop to large distributed clusters. You’ll explore key concepts and patterns behind successful distributed machine learning systems, and learn technologies like TensorFlow, Kubernetes, Kubeflow, and Argo Workflows with real-world scenarios and hands-on projects.
* [GitOps and Kubernetes](https://www.manning.com/books/gitops-and-kubernetes) teaches you how to use Git and the GitOps methodology to manage a Kubernetes cluster. The book interleaves theory with practice, presenting core Ops concepts alongside easy-to-implement techniques so you can put GitOps into action. Learn to develop pipelines that trace changes, roll back mistakes, and audit container deployment.


<a name="blogs" />

## Blog Posts

Please check out the [official Argo Project blog](https://blog.argoproj.io/). Additional links:

* [All About ArgoCD, a Beginner’s Guide](https://dev.to/abhinavd26/all-about-argocd-a-beginners-guide-33c9)
* [Applied GitOps with Argo CD](https://thenewstack.io/applied-gitops-with-argocd/)
* [Architecting Workflows For Reliability](https://blog.argoproj.io/architecting-workflows-for-reliability-d33bd720c6cc)
* [Argo 101 - What is Argo?](https://blog.akuity.io/argo-101-what-is-argo-82d78e0205c)
* [Argo Ansible Role: Provisioning Argo Workflows on OpenShift](https://medium.com/@marekermk/provisioning-argo-on-openshift-with-ansible-and-kustomize-340a1fda8b50)
* [Argo CD Best Practices](https://codefresh.io/argo-platform/argo-cd-best-practices/)
* [ArgoCD Best Practices You Should Know](https://datree.io/resources/argocd-best-practices-you-should-know)
* [ArgoCon 2021 Akuity Team Recap](https://blog.akuity.io/argocon-2021-akuity-team-recap-3ba0fc782025)
* [Argo Integration Review](http://dev.matt.hillsdon.net/2018/03/24/argo-integration-review.html)
* [Argo Security Automation with OSS-Fuzz](https://medium.com/argo-project/argo-security-automation-with-oss-fuzz-da38c1f86452)
* [Argo Workflow As the Choice To Run Data Pipelines in Casavo](https://medium.com/casavo/argo-workflow-in-casavo-722b40362e4c)
* [Automate Canary Analysis on Kubernetes with Argo](https://blog.px.dev/argo-rollouts/)
* [Building a Successful Open Source Community as an End User Company](https://medium.com/intuit-engineering/building-a-successful-open-source-community-as-an-end-user-company-89a70445134)
* [Best Practices for Multi-tenancy in Argo CD](https://blog.argoproj.io/best-practices-for-multi-tenancy-in-argo-cd-273e25a047b0)
* [CI/CD with Argo on Kubernetes](https://medium.com/@bouwe.ceunen/ci-cd-with-argo-on-kubernetes-28c1a99616a9)
* [Cloud Native CI/CD with Tekton and ArgoCD on AWS](https://aws.amazon.com/blogs/containers/cloud-native-ci-cd-with-tekton-and-argocd-on-aws/)
* [Continuous Delivery Using a Carvel ytt Argo CD Plugin](https://carvel.dev/blog/argocd-carvel-plugin/)
* [Decentralized GitOps Over Environments](https://blogs.sap.com/2021/05/06/decentralized-gitops-over-environments/)
* [Deploy Argo CD with Ingress and TLS in Three Steps: No YAML Yak Shaving Required](https://itnext.io/deploy-argo-cd-with-ingress-and-tls-in-three-steps-no-yaml-yak-shaving-required-bc536d401491)
* [Deploying Argo CD and Sealed Secrets with Helm](https://faun.pub/deploying-argo-cd-and-sealed-secrets-with-helm-8de12f53051b)
* [Designing A Complete CI/CD Pipeline CI/CD Pipeline Using Argo Events, Workflows, and CD](https://www.slideshare.net/JulianMazzitelli/designing-a-complete-ci-cd-pipeline-using-argo-events-workflow-and-cd-products-228452500)
* [Getting Started with ArgoCD for GitOps Kubernetes Deployments](https://medium.com/@outlier.developer/getting-started-with-argocd-for-gitops-kubernetes-deployments-fafc2ad2af0)
* [GitOps Deployment and Kubernetes - using Argo CD](https://medium.com/riskified-technology/gitops-deployment-and-kubernetes-f1ab289efa4b)
* [GitOps for Kubeflow using Argo CD](https://v0-6.kubeflow.org/docs/use-cases/gitops-for-kubeflow/)
* [GitOps - Getting Started with ArgoCD](https://vzilla.co.uk/vzilla-blog/gitops-getting-started-with-argocd)
* [GitOps – Including Backup in Your Continous Deployments](https://vzilla.co.uk/vzilla-blog/gitops-including-backup-in-your-continuous-deployments)
* [GitOps Model for Provisioning and Bootstrapping Amazon EKS Clusters Using Crossplane and Argo CD](https://aws.amazon.com/blogs/containers/gitops-model-for-provisioning-and-bootstrapping-amazon-eks-clusters-using-crossplane-and-argo-cd/)
* [GitOps Toolsets on Kubernetes with CircleCI and Argo CD](https://www.digitalocean.com/community/tutorials/webinar-series-gitops-tool-sets-on-kubernetes-with-circleci-and-argo-cd)
* [GitOps with Argo CD](https://www.giantswarm.io/blog/gitops-with-argocd-giant-swarm)
* [Gradual Code Releases Using an In-House Kubernetes Canary Controller on Top of Argo Rollouts](https://doordash.engineering/2021/04/14/gradual-code-releases-using-an-in-house-kubernetes-canary-controller/)
* [Hera - the Missing Argo Workflows Python SDK](https://www.dynotx.com/hera-the-missing-argo-workflows-python-sdk/)
* [How GitOps and Operators Mark the Rise of Infrastructure-As-Software](https://paytmlabs.com/blog/2021/10/how-to-improve-operational-work-with-operators-and-gitops/)
* [How to Automate Verification of Deployments with Argo Rollouts and Elastic Observability](https://www.elastic.co/blog/automate-verification-of-deployments-with-argo-rollouts-and-elastic-observability)
* [How to Deploy With ArgoCD When Helm Values and Chart Are in Different Repositories](https://mixi-developers.mixi.co.jp/argocd-with-helm-fee954d1003c)
* [https://blog.argoproj.io/human-centric-data-science-on-kubernetes-with-metaflow-7f60aad34cba](https://blog.argoproj.io/human-centric-data-science-on-kubernetes-with-metaflow-7f60aad34cba)
* [Jenkins X 3 and Argo CD](https://jenkins-x.io/blog/2021/06/28/argo/)
* [KubeCon EU 2022 - Akuity Team Recap](https://akuity.io/blog/kubeconeu-2022-akuity-team-recap)
* [Kubernetes Cluster Vending Machine With vcluster](https://blog.ediri.io/kubernetes-cluster-vending-machine-with-vcluster)
* [Kubernetes Security through GitOps Best Practices: ArgoCD and Starboard](https://anaisurl.com/gitops-argocd-starboard/)
* [Machine Learning Hyperparameter Optimization with Argo](https://canvatechblog.com/machine-learning-hyperparameter-optimization-with-argo-a60d70b1fc8c)
* [Making Complex R Applications into Production using Argo Workflows](https://blog.argoproj.io/making-complex-r-application-into-production-using-argo-workflows-648ce5d190b5)
* [Manage Namespaces on Multitenant Clusters with ArgoCD, Kustomize and Helm](https://developers.redhat.com/articles/2022/04/13/manage-namespaces-multitenant-clusters-argo-cd-kustomize-and-helm)
* [Measuring Argo Workflow Costs with Kubecost](https://blog.kubecost.com/blog/measuring-argo-workflows-with-kubecost/)
* [Minimize Failed Deployments with Argo Rollouts and Smoke Tests](https://codefresh.io/continuous-deployment/minimize-failed-deployments-argo-rollouts-smoke-tests/)
* [Open Source Model Management Roundup: Polyaxon, Argo, and Seldon](https://www.anaconda.com/blog/developer-blog/open-source-model-management-roundup-polyaxon-argo-and-seldon/)
* [Producing 200 OpenStreetMap Extracts in 35 Minutes Using a Scalable Data Workflow](https://www.interline.io/blog/scaling-openstreetmap-data-workflows/)
* [Recover Automatically from Failed Deployments with Argo Rollouts and Prometheus Metrics](https://codefresh.io/continuous-deployment/recover-automatically-from-failed-deployments/)
* [Running Argo Workflows Across Multiple Kubernetes Clusters](https://admiralty.io/blog/running-argo-workflows-across-multiple-kubernetes-clusters/)
* [Setting up Argo CD With Helm](https://www.arthurkoziel.com/setting-up-argocd-with-helm/)
* [Simplify and Automate Deployments Using GitOps with IBM Multicloud Manager 3.1.2](https://www.ibm.com/cloud/blog/simplify-and-automate-deployments-using-gitops-with-ibm-multicloud-manager-3-1-2)
* [Solving Configuration Drift Using GitOps with Argo CD](https://www.cncf.io/blog/2020/12/17/solving-configuration-drift-using-gitops-with-argo-cd/)
* [Stay Up to Date With Argo CD and Renovate](https://mjpitz.com/blog/2020/12/03/renovate-your-gitops/)
* Terraform Automation With Argo on Kubernetes ([Part1](https://medium.com/insideboard/terraform-automation-with-argo-on-kubernetes-part1-51b3914028d6) & [Part2](https://medium.com/insideboard/terraform-automation-with-argo-on-kubernetes-part2-consul-vault-92a020432cd0))
* [Unveil the Secret Ingredients of Continuous Delivery at Enterprise Scale with Argo CD](https://blog.akuity.io/unveil-the-secret-ingredients-of-continuous-delivery-at-enterprise-scale-with-argo-cd-7c5b4057ee49)
* [Using Argo to Train Predictive Models](https://flightaware.engineering/using-argo-to-train-predictive-models/)
* [Using Argo CD with vclusters](https://medium.com/@helfand.4/using-argo-cd-with-vclusters-ff8b9c16ac9e)
* [Preventing Tag Mutation With kbld And Argo CD](https://blog.argoproj.io/preventing-tag-mutation-with-kbld-and-argo-cd-19cecd65963)

Blogposts that provide comparisons:
* ArgoCD
  * vs. Flux: [[0]](https://www.sgmoratilla.com/2021-10-28-flux-vs-argocd/), [[1]](https://rajputvaibhav.medium.com/argo-cd-vs-flux-cd-right-gitops-tool-for-your-kubernetes-cluster-c71cff489d26), [[2]](https://thenewstack.io/gitops-on-kubernetes-deciding-between-argo-cd-and-flux/)
  * [vs. Spinnaker](https://tech.trell.co/choosing-a-continous-delivery-tool-spinnaker-vs-argocd-9adcc65a4fde)
  * [vs. Spinnaker, Jenkins X, and Tekton](https://www.inovex.de/blog/spinnaker-vs-argo-cd-vs-tekton-vs-jenkins-x/)
* Argo Workflows
  * [vs. Airflow and Prefect](https://medium.com/arthur-engineering/picking-a-kubernetes-orchestrator-airflow-argo-and-prefect-83539ecc69b)


<a name="videos" />

## Videos

Please check out the [official Argo Project YouTube channel](https://www.youtube.com/channel/UCOvYmppcbOPm1viN6ust3lA).

🔥 KubeCon Europe 2022 talks:
* [Applied GitOps with Argo CD Autopilot Using Multiple Clusters with an ApplicationSet](https://youtu.be/r3k2qI2NDsA)
* [Argo’s Vibrant Ecosystem and Community](https://youtu.be/9tYkxlhXdw4)
* [Automated Progressive Delivery Using GitOps and Service Mesh](https://youtu.be/5Ko-CnP2qhA)
* [Building AutoML Pipelines With Argo Workflows and Katib](https://youtu.be/d8o7fEd8l2g)
* [Exploring HashiCorp Vault and ArgoCD - the GitOps Way](https://youtu.be/2camnnjyviw)
* [GitOpsify Everything: When Crossplane Meets Argo CD](https://youtu.be/9odjdVqJkws)
* [How a Couple of Characters (and GitOps) Brought Down Our Site](https://youtu.be/FiEm2zOuHsg)
* [Intuitive Progressive Delivery Across Microservices in a Dependency Graph Using Argo Rollouts](https://youtu.be/02y5q4Cc2Fs)
* [Implementing Preview Environments with GitOps in Kubernetes](https://youtu.be/QNAiIJRIVWA)
* [Infra-like-apps - GitOpsifying Cloud Natively Managed Infrastructure with Crossplane and Argo CD](https://youtu.be/epoTCI4pqdE)
* [TikTok’s Story: How To Manage a Thousand Applications on Edge With Argo CD](https://youtu.be/Ftz5_lIepNA)

Other talks:

* [A Briefer History of Argo Project from the Founding Engineers](https://youtu.be/FQ9uB8FuX_I)
* [A Multi-Cluster, Multi-Cloud Infrastructure with GitOps at CERN](https://youtu.be/h6xDWc6fXao)
* [Argo-Based Service Delivery for Multi-Tenant, Multi Region Clusters at Adobe](https://youtu.be/Ahps2IwhREw)
* [Argo: The Present, Past, and Future](https://youtu.be/76iUpAWakIM)
* [Argo and Tekton: Pushing the Boundaries of the Possible on Kubernetes](https://youtu.be/iPRw_n_JV4o)
* [Argo CD - GitOps Continuous Delivery for Kubernetes](https://www.youtube.com/watch?v=aWDIQMbp1cc&feature=youtu.be&t=1m4s)
* [Argo CD: Applying GitOps Principles To Manage Production Environment In Kubernetes](https://youtu.be/vpWQeoaiRM4)
* [Argo CD and Stateful Applications - Tips and Tricks](https://youtu.be/_-oVaO4SxLk)
* [Argo CD Production Best Practices](https://youtu.be/ESQLqjbM8h0)
* [Argo CD Walkthrough – Learn Argo CD in 18 Minutes](https://youtu.be/2B3qcyCcBXs)
* [Argo CD in the Cloud: DevOps and Docker Live Show](https://youtu.be/DxJawE0uZgw?t=366)
* [Argo Events - Event-Based Dependency Manager for Kubernetes](https://youtu.be/sUPkGChvD54)
* [Argo Events Deep-dive](https://youtu.be/U4tCYcCK20w)
* [Argo Rollouts - Canary Deployments Made Easy In Kubernetes](https://youtu.be/84Ky0aPbHvY)
* [Argo Workflows and Pipelines - CI/CD, Machine Learning, and Other Kubernetes Workflows](https://youtu.be/UMaivwrAyTA)
* [Automating Research Workflows at BlackRock](https://www.youtube.com/watch?v=ZK510prml8o)
* [Automation of Everything - How To Combine Argo Events, Workflows & Pipelines, CD, and Rollouts](https://youtu.be/XNXJtxkUKeY)
* [Bridging into Python Ecosystem with Cloud-Native Distributed Machine Learning Pipelines](https://github.com/terrytangyuan/public-talks/tree/main/talks/bridging-into-python-ecosystem-with-cloud-native-distributed-machine-learning-pipelines-argocon-2021)
* [Building a Successful Open Source Community as an End-user Company](https://youtu.be/BrZMZJc3Vh4)
* [Building Medical Grade AI with Argo Workflows](https://youtu.be/4VPSktuM5Ow)
* [CI/CD for Machine Learning at MLB using Argo Workflows](https://youtu.be/fccWoYlwZKc?t=184)
* [CI/CD in Light Speed with K8s and Argo CD](https://www.youtube.com/watch?v=OdzH82VpMwI&feature=youtu.be)
* [Cloud Native AutoML with Argo Workflows and Katib](https://youtu.be/KjHqmS4gIxM?t=181)
* [Cloud-native CI/CD via ArgoCD & Workflows in Multi-region & Muti-cell Environment](https://youtu.be/IPiNWwPgsjw)
* [Combining Argo CD (GitOps), Crossplane (Control Plane), and KubeVela (OAM)](https://youtu.be/eEcgn_gU3SM)
* [Couchbase - How To Run a Database Cluster in Kubernetes Using Argo CD](https://youtu.be/nkPoPaVzExY)
* [Deploying Cluster Addons at Scale using ApplicationSets](https://youtu.be/Yj60Co4UxXk)
* [Deployments on the Edge using Argo CD & Workflows and K3s](https://youtu.be/9BSXBgaOmr4)
* [Distributed Load Testing Using Argo Workflows](https://youtu.be/9zg2EH2pRw0?t=1221)
* [Dynamic, Event-Driven Machine Learning Pipelines with Argo Workflows](https://youtu.be/ei4r0a7eAV0)
* [Easy Notifications for Kubernetes](https://youtu.be/gZ0MfSoHbY0)
* [Environments Based on Pull Requests (PRs): Using Argo CD To Apply GitOps Principles on Previews](https://youtu.be/cpAaI8p4R60)
* [Extending GitOps to Manage K8s (so you don’t have to)!](https://youtu.be/bTHkDdXRx24)
* [Getting Started with ArgoCD for GitOps Deployments](https://youtu.be/AvLuplh1skA)
* [GitOps Cloud Resource Management](https://youtu.be/TJQHB8XVW44)
* [GitOps Guide to the Galaxy: Argo Workflows](https://www.youtube.com/watch?v=2lI41q8Z7ko)
* [GitOps with Argo CD and an Argo Rollouts Canary Release](https://www.youtube.com/watch?v=35Qimb_AZ8U)
* [GitOps Without Pipelines With ArgoCD Image Updater](https://youtu.be/avPUQin9kzU)
* [How Intuit Does Canary and Blue Green Deployments](https://www.youtube.com/watch?v=yeVkTTO9nOA)
* [How Scalable is Argo-Rollouts: A Cloud Operator’s Perspective](https://youtu.be/rCEhxJ2NSTI)
* [How to Apply GitOps to Everything - Combining Argo CD and Crossplane](https://youtu.be/yrj4lmScKHQ)
* [Integrating Backup into Your GitOps CI/CD Pipeline](https://youtu.be/2mjlmjJ4NjQ)
* [Introducing Couler: Unified Interface for Constructing and Managing Workflows](https://github.com/terrytangyuan/public-talks/tree/main/talks/introducing-couler-unified-interface-for-constructing-and-managing-workflows-argo-workflows-community-meeting)
* [Introduction to Argo CD: Kubernetes DevOps CI/CD](https://www.youtube.com/watch?v=2WSJF7d8dUg&feature=youtu.be)
* [Journey of the Argonauts](https://youtu.be/boqZFQRLc9s)
* [K8s Cluster Vending Machine With vCluster](https://youtu.be/GkaqN8urStg)
* [Kubernetes Blue-Green Deployments with Argo Rollouts](https://www.youtube.com/watch?v=krDxDz4V4Tg)
* [Kubernetes Canary Deployments with Argo Rollouts](https://www.youtube.com/watch?v=fviYWA2mcF8)
* [Kubernetes Security through GitOps Best Practices: ArgoCD and Starboard](https://youtu.be/YvMY8to9aHI)
* [Leveling Up Your CD: Unlocking Progressive Delivery on Kubernetes](https://www.youtube.com/watch?v=Nv0PPwbIEkY)
* [Level Unlocked: GitOps to the Edge and Infrastructure Provisioning](https://youtu.be/4zDm23kA8oE)
* [Litmus 2 - Chaos Engineering Meets Argo Workflows](https://youtu.be/B8DfYnDh2F4)
* [Machine Learning as Code: GitOps for ML with Kubeflow and ArgoCD](https://www.youtube.com/watch?v=VXrGp5er1ZE&t=0s&index=135&list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU)
* [Machine Learning with Argo and Ploomber](https://youtu.be/FnpXyg-5W_c?t=172)
* [Maintainer Update on Argo CD and Rollouts](https://youtu.be/wn6OOLoHvQg)
* [Maintainer Update on Argo Workflows and Events](https://youtu.be/FUekn40l9-A)
* [Making Complex R Forecast Applications Into Production Using Argo Workflows](https://www.youtube.com/watch?v=fPjztsUXHcg)
* [Manage More Clusters with Less Hassle, with Argo CD Application Sets](https://youtu.be/GcvHKc2IHi8)
* [Metaflow Integration with Argo Workflows](https://youtu.be/EagFq5QtcpI?t=859)
* [MLOps at Tripadvisor: ML Models CI/CD Automation with Argo](https://youtu.be/BochC4GKxbo?t=906)
* [Multi-Stage Delivery with Keptn and Argo Rollouts](https://www.youtube.com/watch?v=w-E8FzTbN3g&t=1s)
* [Processing Petabytes in Python with Argo Workflows & Dask](https://youtu.be/f5lPS9WKy_8)
* [Robocat Meets Octopus and Octocat: Interoperability in CI/CD](https://youtu.be/Yq5lqr6n0E8)
* [Scaling Kubernetes across BlackRock’s Aladdin Platform](https://youtu.be/Hoo9pngi5Q0)
* [Scaling Software Delivery on Argo](https://youtu.be/hS_y4SxiPME)
* [Shh, It’s a Secret: Managing Your Secrets in a GitOps Way](https://youtu.be/7L6nSuKbC2c)
* [Supercharge Your Dev Experience [DX] with ArgoCD, Crossplane, & Shipa](https://youtu.be/-p0sn_X2CXQ)
* [TGI Kubernetes with Joe Beda: Argo Workflow System](https://www.youtube.com/watch?v=M_rxPPLG8pU&start=859)
* [TGI Kubernetes with Joe Beda: CloudEvents and Argo Events](https://www.youtube.com/watch?v=LQbBgQnUs_k&list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa&index=2&t=0s)
* [The Argo Ecosystem: Tailoring Your Installation Through Community Add-ons](https://youtu.be/EPtiDNXpS78)
* [The Journey from DevOps to GitOps](https://youtu.be/2kokbYtslbw)
* [Towards Cloud-Native Distributed Machine Learning Pipelines at Scale](https://github.com/terrytangyuan/public-talks/tree/main/talks/towards-cloud-native-distributed-machine-learning-pipelines-at-scale-pydata-global-2021)
* [Tutorial: Everything You Need To Become A GitOps Ninja](https://www.youtube.com/watch?v=r50tRQjisxw)
* [Unveil The Secret Ingredients for Argo CD in the Enterprise-Scale](https://github.com/terrytangyuan/public-talks/tree/main/talks/unveil-the-secret-ingredients-for-argo-cd-at-enterprise-scale-kubecon-china-2021)
* [Using Argo CD with vclusters](https://www.youtube.com/watch?v=M3ycfeocvNo)
* [Using Argo CD & Datree for Stable Kubernetes CI/CD Deployments](https://youtu.be/17894DTru2Y)
* [Preventing Tag Mutation With kbld And Argo CD](https://www.youtube.com/watch?v=KkgHYdVfXwY)

<a name="community" />

## Community

* [Argo Community Calendar](https://calendar.google.com/calendar/embed?src=argoproj@gmail.com) ([ICS File](https://calendar.google.com/calendar/ical/argoproj%40gmail.com/public/basic.ics))
* [Argo Project GitHub Organization](https://github.com/argoproj) ([Maintainers](https://github.com/argoproj/argoproj/blob/master/MAINTAINERS.md) and [Community Governance](https://github.com/argoproj/argoproj/blob/master/community/GOVERNANCE.md))
* [Argo at Conferences](https://docs.google.com/document/d/1VWiwmintCq7cdoZaW8D49JpEWbLJ6PrOWQNELRg1ALg/edit?usp=sharing)
* ArgoCon ([2022](https://events.linuxfoundation.org/argocon/) and [2021](https://argoproj.github.io/argocon21/))
* Argo Project User Survey Results ([2022](https://blog.argoproj.io/cncf-argo-project-2022-user-survey-results-f9caf46df7fd), [2021](https://github.com/argoproj/argoproj/blob/f4daa47706c73302faba1608cbc312bbafa0abfc/community/user_surveys/Argo%20CD%20and%20Rollouts%20User%20Survey%202021.pdf), and [2020](https://github.com/argoproj/argoproj/blob/f4daa47706c73302faba1608cbc312bbafa0abfc/community/user_surveys/ArgoWorkflows2020SurveySummary.pdf))

Social media accounts:

* [LinkedIn](https://www.linkedin.com/company/argoproj/)
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
