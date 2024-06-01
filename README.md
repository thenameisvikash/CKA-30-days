# CKA 1-Month Study Plan

## Overview
This repository contains my one-month study plan to prepare for the Certified Kubernetes Administrator (CKA) exam.

## Weekly Roadmap

### Week 1: Kubernetes Basics and Cluster Setup
#### Day 1-2: Introduction to Kubernetes
- [ ] Understand the basics of containerization (Docker).
- [ ] Learn Kubernetes architecture and components (Master, Nodes, etc.).
- [ ] Set up a local Kubernetes cluster using [Minikube](https://minikube.sigs.k8s.io/docs/start/) or [Docker Desktop](https://docs.docker.com/desktop/kubernetes/).

#### Day 3-4: Core Kubernetes Objects
- [ ] Learn about Pods, ReplicaSets, Deployments, and Namespaces.
- [ ] Practice creating and managing basic objects using `kubectl`.

#### Day 5-7: Cluster Configuration and Networking
- [ ] Install Kubernetes with [kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/).
- [ ] Configure cluster networking (CNI).
- [ ] Understand the Kubernetes API server and control plane.

### Week 2: Workloads, Services, and Storage
#### Day 1-2: Application Lifecycle Management
- [ ] Manage deployments and rollouts.
- [ ] Learn about DaemonSets, StatefulSets, and Jobs/CronJobs.

#### Day 3-4: Services and Networking
- [ ] Understand Services (ClusterIP, NodePort, LoadBalancer).
- [ ] Practice configuring Ingress controllers and Ingress resources.
- [ ] Study CoreDNS and service discovery.

#### Day 5-7: Persistent Storage
- [ ] Learn about Persistent Volumes (PV) and Persistent Volume Claims (PVC).
- [ ] Explore storage classes and dynamic provisioning.

### Week 3: Security, Scheduling, and Logging
#### Day 1-2: Security
- [ ] Study Kubernetes authentication and authorization (RBAC).
- [ ] Understand Network Policies and Pod security policies.
- [ ] Learn about Secrets and ConfigMaps.

#### Day 3-4: Scheduling
- [ ] Study how Kubernetes schedules Pods onto Nodes.
- [ ] Learn about taints, tolerations, node selectors, and affinity/anti-affinity.

#### Day 5-7: Logging and Monitoring
- [ ] Explore logging and monitoring basics in Kubernetes.
- [ ] Learn to use tools like [Prometheus](https://prometheus.io/) and [Grafana](https://grafana.com/).

### Week 4: Advanced Topics and Practice Exams
#### Day 1-2: Troubleshooting
- [ ] Practice troubleshooting common Kubernetes issues.
- [ ] Learn to read and understand Kubernetes logs.

#### Day 3-4: Advanced Configuration
- [ ] Study advanced scheduling (resource limits, quotas).
- [ ] Learn about custom resources and operators.
- [ ] Explore [Helm](https://helm.sh/) for package management.

#### Day 5-7: Review and Practice Exams
- [ ] Review all key concepts and practices from the previous weeks.
- [ ] Take practice exams and time yourself.
- [ ] Review official Kubernetes documentation.
- [ ] Join study groups or forums for additional support and tips.

## Resources
- [Official Kubernetes Documentation](https://kubernetes.io/docs/home/)
- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [CKA Exam Curriculum](https://github.com/cncf/curriculum)

## Progress Tracking
- [ ] Week 1: Kubernetes Basics and Cluster Setup
- [ ] Week 2: Workloads, Services, and Storage
- [ ] Week 3: Security, Scheduling, and Logging
- [ ] Week 4: Advanced Topics and Practice Exams

## Folder Structure

CKA-1-Month-Study-Plan/
│
├── Week1/
│ ├── Day1-2/
│ │ ├── DockerBasics.md
│ │ ├── KubernetesArchitecture.md
│ │ └── MinikubeSetup.md
│ ├── Day3-4/
│ │ ├── KubernetesObjects.md
│ │ └── KubectlCommands.md
│ └── Day5-7/
│ ├── KubeadmInstallation.md
│ ├── ClusterNetworking.md
│ └── APIServer.md
│
├── Week2/
│ ├── Day1-2/
│ │ ├── ApplicationLifecycle.md
│ │ └── Workloads.md
│ ├── Day3-4/
│ │ ├── Services.md
│ │ ├── Ingress.md
│ │ └── CoreDNS.md
│ └── Day5-7/
│ ├── PersistentStorage.md
│ └── StorageClasses.md
│
├── Week3/
│ ├── Day1-2/
│ │ ├── RBAC.md
│ │ ├── NetworkPolicies.md
│ │ └── SecretsConfigMaps.md
│ ├── Day3-4/
│ │ ├── Scheduling.md
│ │ └── Affinity.md
│ └── Day5-7/
│ ├── Logging.md
│ └── Monitoring.md
│
└── Week4/
├── Day1-2/
│ ├── Troubleshooting.md
│ └── Logs.md
├── Day3-4/
│ ├── AdvancedScheduling.md
│ └── CustomResources.md
└── Day5-7/
├── Review.md
├── PracticeExams.md
└── StudyGroups.md
