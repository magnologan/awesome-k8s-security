# Awesome K8s Security
A curated list for Awesome and Free Kubernetes Security resources. Most of the resources are in English, the ones that aren't will be flagged as such. 

## Disclaimer
All the contents of this list are public and mostly free, use them for educational purposes only. Most of the tools have NOT been tested or reviewed, use them at your own risk! Also, I don't consider myself a K8s Security expert, I'm just learning and helping others learn along with me. Cheers!

## The Basics
To understand about Kubernetes Security you first need to understand how Kubernetes works and all the components involved. Here's some links and materials to help you with that journey.

### Official Pages

Kubernetes.io - https://kubernetes.io/

Kubernetes GitHub - https://github.com/kubernetes/kubernetes

### Blogs

Kubernetes: Getting Started - https://azure.microsoft.com/en-us/overview/kubernetes-getting-started/

Kubernetes 101 - https://www.aquasec.com/resources/kubernetes-101/

### Books

Kubernetes: Up and Running, Second Edition by Brendan Burns, Joe Beda and Kelsey Hightower - https://azure.microsoft.com/en-us/resources/kubernetes-up-and-running/

### Repos

Kubernetes The Hard Way - Kelsey Hightower - https://github.com/kelseyhightower/kubernetes-the-hard-way

Kubernetes - Challenge - https://github.com/hector-vido/kubernetes-challenge (pt-BR)

Kubernetes de K a S - https://github.com/erlonpinheiro/kubernetes_de_k_a_s (pt-BR)

Kubernetes Training - https://github.com/ashishrpandey/kubernetes-training

### Trainings

Introduction to Kubernetes - https://www.edx.org/course/introduction-to-kubernetes

Kube Academy - https://kube.academy/

Game of Pods (KodeKloud) - https://kodekloud.com/p/game-of-pods

Uncomplicating Kubernetes (Jefferson Noronha aka LinuxTips) - https://www.youtube.com/watch?v=zz1p3gjyHgc (pt-BR)

### Videos

Kubernetes in 5 mins - https://www.youtube.com/watch?v=PH-2FfFD2PU

Kubernetes Concepts Explained in 9 minutes! - https://www.youtube.com/watch?v=QJ4fODH6DXI

### Podcasts / Videocasts

TGI Kubernetes - https://www.youtube.com/playlist?list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa

The Podlets - https://thepodlets.io


## Kubernetes Security 
These are the main contents of this awesome list. Everything related to the security of Kubernetes, either breaking or improving it, will be added down below. If you have any other good recommendations, feel free to submit a PR.

### Official Pages

Kubernetes Security and Disclosure Information - https://kubernetes.io/docs/reference/issues-security/security/

Cloud Native Security - https://kubernetes.io/docs/concepts/security/overview/

Pod Security Standards - https://kubernetes.io/docs/concepts/security/pod-security-standards/

CNCF Special Interest Group for Security (SIG-Security) - https://github.com/cncf/sig-security

CNCF Special Interest Group for Authorization, Authentication, and Cluster Security Policy (SIG-Auth) - https://github.com/kubernetes/community/tree/master/sig-auth

### Blogs

Kubernetes Security - https://kubernetes-security.info/

Introducing Kubernetes Goat - https://blog.madhuakula.com/introducing-kubernetes-goat-8624f6d70e9e

Attack Matrix for Kubernetes - https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/

Open Sourcing the Kubernetes Security Audit - https://www.cncf.io/blog/2019/08/06/open-sourcing-the-kubernetes-security-audit/

Amazon EKS Best Practices Guide for Security - https://aws.github.io/aws-eks-best-practices/

CVE-2018-18264 Privilege escalation through Kubernetes dashboard - https://sysdig.com/blog/privilege-escalation-kubernetes-dashboard

Protecting Against Kubernetes Threats: Chapter 1 - Initial Access - https://www.stackrox.com/post/2020/06/protecting-against-kubernetes-threats-chapter-1-initial-access/

Guidance on Kubernetes Threat Modeling - https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/guidance-on-kubernetes-threat-modeling

Securing the 4Cs of Cloud Native - https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/securing-the-4-cs-of-cloud-native-systems-cloud-cluster-container-and-code

### Books

Container Security by Liz Rice - https://containersecurity.tech/

Kubernetes Security by Liz Rice and Michael Hausenblas - https://info.aquasec.com/kubernetes-security

### Papers

Kubernetes Security Assessment - https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/Kubernetes%20Final%20Report.pdf

Kubernetes Security Whitepaper - https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/Kubernetes%20White%20Paper.pdf

Kubernetes Threat Model - https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/Kubernetes%20Threat%20Model.pdf

Kubernetes Attack Tree - https://github.com/cncf/financial-user-group/tree/master/projects/k8s-threat-model

Attacking Kubernetes - A Guide for Administrators and Penetration Testers - https://raw.githubusercontent.com/kubernetes/community/master/wg-security-audit/findings/AtredisPartners_Attacking_Kubernetes-v1.0.pdf

CIS Kubernetes Benchmark v1.5.0 - https://www.cisecurity.org/benchmark/kubernetes/  

Kubernetes é seguro por default ou à prova de má configuração? - https://medium.com/@p0ssuidao/kubernetes-%C3%A9-seguro-por-default-ou-aprova-de-m%C3%A1-configura%C3%A7%C3%A3o-9d3bccc2f342

### Recorded Talks (Videos)

Advanced Persistence Threats: The Future of Kubernetes Attacks (RSAC 2020) - https://www.youtube.com/watch?v=CH7S5rE3j8w

Kubernetes Security Best Practices - Ian Lewis, Google - https://www.youtube.com/watch?v=wqsUfvRyYpw

Securing Kubernetes Secrets (Cloud Next '19) - https://www.youtube.com/watch?v=DNKcRUyz4Hw

Jay Beale - Attacking and Defending Kubernetes - DEF CON 27 Packet Hacking Village - https://www.youtube.com/watch?v=2fmAuR3rnBo

The State of Kubernetes Security - Liz Rice - https://www.youtube.com/watch?v=_l56oUxHSio

DIY Pen-Testing for Your Kubernetes Cluster - Liz Rice, Aqua Security - https://www.youtube.com/watch?v=fVqCAUJiIn0

### Presentations (Slides)

Communication is Key - Understanding Kubernetes Networking (KubeCon EU 2020) - https://static.sched.com/hosted_files/kccnceu20/3d/Communication_is_Key.pdf

Seccomp Profiles and you: A practical guide (KubeCon EU 2020) - https://www.slideshare.net/DuffieCooley/seccomp-profiles-and-you-a-practical-guide

Advanced Persistence Threats: The Future of Kubernetes Attacks (KubeCon EU 2020) - https://speakerdeck.com/iancoldwater/advanced-persistence-threats-the-future-of-kubernetes-attacks

Help! My Cluster Is On The Internet! - bit.ly/SamK8sSec

### Tools / Open Source projects

#### Learning

Bust-a-Kube - https://www.bustakube.com/

kube-goat - https://github.com/ksoclabs/kube-goat

Kubernetes Goat - https://github.com/madhuakula/kubernetes-goat

Kubernetes networking labs for KubeCon EU 2020 talk - https://github.com/korvus81/k8s-net-labs

#### Attacking

kube-hunter - https://github.com/aquasecurity/kube-hunter

Peirates - https://github.com/inguardians/peirates

#### Defending

Kubernetes Audit by Trail of Bits - https://github.com/trailofbits/audit-kubernetes

falco - https://github.com/falcosecurity/falco

kubesec - https://github.com/controlplaneio/kubesec

kube-bench - https://github.com/aquasecurity/kube-bench

trivy - https://github.com/aquasecurity/trivy

MKIT - https://github.com/darkbitio/mkit

kubetap - https://github.com/soluble-ai/kubetap

kube-forensics - https://github.com/keikoproj/kube-forensics

k8s-security-dashboard - https://github.com/k8scop/k8s-security-dashboard

CIS Kubernetes Benchmark - InSpec Profile - https://github.com/dev-sec/cis-kubernetes-benchmark

Kube PodSecurityPolicy Advisor - https://github.com/sysdiglabs/kube-psp-advisor

Inspektor Gadget - https://github.com/kinvolk/inspektor-gadget

Starboard - https://github.com/aquasecurity/starboard

Advocacy Site for Kubernetes RBAC - https://github.com/mhausenblas/rbac.dev

Helm-Snyk - https://github.com/snyk-labs/helm-snyk

Krane - https://github.com/appvia/krane

### Trainings

Secure Kubernetes - https://securekubernetes.com/

Cloud Native Security Tutorial - https://tutorial.kubernetes-security.info/

Kubernetes Security (Advanced Concepts) - https://linuxacademy.com/course/kubernetes-security-advanced-concepts/

Kubernetes Goat Guide - https://madhuakula.com/kubernetes-goat/

Katacoda Kubernetes Goat Videos - https://katacoda.com/madhuakula/scenarios/kubernetes-goat

Attacking and Auditing Docker Containers and Kubernetes Clusters - https://github.com/appsecco/attacking-and-auditing-docker-containers-and-kubernetes-clusters


### Other Awesome Lists

kubepwn - https://github.com/alexivkin/kubepwn

awesome-kubernetes-security - https://github.com/ksoclabs/awesome-kubernetes-security

awesome-kubernetes - https://github.com/ramitsurana/awesome-kubernetes
