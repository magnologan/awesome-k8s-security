<a href="https://kubernetes.io/">
    <img src="https://github.com/magnologan/awesome-k8s-security/blob/master/logo.png"
         alt="Kubernetes logo" title="Kubernetes" height="100" width="100" />
</a></br>

# Awesome Kubernetes (K8s) Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list for Kubernetes (K8s) Security resources such as articles, books, tools, talks and videos.  

# Disclaimer
Most of the resources are in English, the ones that aren't will be flagged as such. All the content in this list is public and free, please use them for educational purposes only!

Not all the tools have been tested or reviewed, use them at your own risk! Also, I don't consider myself a K8s Security expert, I'm just learning and helping others learn along with me. Thanks!

# Contents
These are the main topics of this Awesome Kubernetes (K8s) Security List. Everything related to the Security of Kubernetes (and its components such as CoreDNS, etcd) either for learning, breaking or defending it, will be added down below. If you have any other good links or recommendations, feel free to submit a PR!

- [💊 The Basics](#basics)
- [💼 Official Pages](#official)
- [📹 Talks and Videos](#talks-and-videos)
- [📰 Blogs and Articles](#blogs-and-articles)
- [🗒️ Books](#books)
- [📆 Certifications](#certifications)
- [🔥 CVEs](#cves)
- [📑 Slides](#slides)
- [🧪 Trainings](#trainings)
- [🐾 Repositories](#repositories)
- [📂 Papers](#papers)
- [🎤 Podcasts](#podcasts)
- [🧰 Jobs](#jobs)
- [📡 Community](#community)

## The Basics
To understand about Kubernetes Security you first need to understand the basics of how Kubernetes works and all the components involved. Here's some links and materials to help you with that journey:

[Kubernetes in 5 mins](https://www.youtube.com/watch?v=PH-2FfFD2PU)

[Kubernetes Concepts Explained in 9 minutes!](https://www.youtube.com/watch?v=QJ4fODH6DXI)

[Kubernetes 101](https://www.aquasec.com/resources/kubernetes-101/)

[Kubernetes: Getting Started](https://azure.microsoft.com/en-us/overview/kubernetes-getting-started/)

[Kubernetes The Hard Way - Kelsey Hightower](https://github.com/kelseyhightower/kubernetes-the-hard-way)

[Kubernetes Challenge](https://github.com/hector-vido/kubernetes-challenge) 🇧🇷

[Kubernetes de K a S - Erlon Pinheiro](https://github.com/erlonpinheiro/kubernetes_de_k_a_s) 🇧🇷

[Kubernetes Training](https://github.com/ashishrpandey/kubernetes-training)

[Introduction to Kubernetes](https://www.edx.org/course/introduction-to-kubernetes)

[Kube Academy](https://kube.academy/)

[Game of Pods (KodeKloud)](https://kodekloud.com/p/game-of-pods)

[Gist of Kubernetes Resources](https://gist.github.com/dims/bb219a4a8d9cb88dc2a2dc1f11a537c6)

[Uncomplicating Kubernetes (Jefferson Noronha aka LinuxTips)](https://www.youtube.com/watch?v=zz1p3gjyHgc) 🇧🇷

## Official Pages

[Kubernetes.io](https://kubernetes.io/)

[Kubernetes GitHub](https://github.com/kubernetes/kubernetes)

[Kubernetes Security and Disclosure Information](https://kubernetes.io/docs/reference/issues-security/security/)

[Cloud Native Security](https://kubernetes.io/docs/concepts/security/overview/)

[Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/)

[CNCF STAG - Security Technical Advisory Group](https://github.com/cncf/tag-security)

[CNCF STAG Meeting Notes](https://docs.google.com/document/d/170y5biX9k95hYRwprITprG6Mc9xD5glVn-4mB2Jmi2g/edit)

[CNCF STAG Mailing List](https://lists.cncf.io/g/cncf-tag-security)

[Kubernetes SIG Security](https://github.com/kubernetes/community/tree/master/sig-security)

[Kubernetes SIG Security Meeting Notes](https://docs.google.com/document/d/1GgmmNYN88IZ2v2NBiO3gdU8Riomm0upge_XNVxEYXp0/edit)

[Kubernetes SIG Auth (Authorization, Authentication, and Cluster Security Policy)](https://github.com/kubernetes/community/tree/master/sig-auth)

[Kubernetes Security Audit 2019 Results](https://github.com/kubernetes/community/tree/master/sig-security/security-audit-2019)

[Kubernetes Security Audit 2021 RFP](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2021/RFP.md)

## Talks and Videos

[Compromising Kubernetes Cluster by Exploiting RBAC Permissions - Eviatar Gerzi, CyberArk (RSA 2020)](https://www.youtube.com/watch?v=1LMo0CftVC4)

[Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson, DOMO](https://www.youtube.com/watch?v=90kZRyPcRZw)

[Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson, DOMO  (Extended Version)](https://vimeo.com/245778144/4d1d597c5e)

[Advanced Persistence Threats: The Future of Kubernetes Attacks (RSAC 2020)](https://www.youtube.com/watch?v=CH7S5rE3j8w)

[Kubernetes Security Best Practices - Ian Lewis, Google](https://www.youtube.com/watch?v=wqsUfvRyYpw)

[Securing Kubernetes Secrets (Cloud Next '19)](https://www.youtube.com/watch?v=DNKcRUyz4Hw)

[Jay Beale - Attacking and Defending Kubernetes - DEF CON 27 Packet Hacking Village](https://www.youtube.com/watch?v=2fmAuR3rnBo)

[The State of Kubernetes Security - Liz Rice](https://www.youtube.com/watch?v=_l56oUxHSio)

[DIY Pen-Testing for Your Kubernetes Cluster - Liz Rice, Aqua Security](https://www.youtube.com/watch?v=fVqCAUJiIn0)

[Kubernetes Security 101: Best Practices to Secure your Cluster](https://www.youtube.com/watch?v=d-pIWfDaZK8&t=3408s)

[Kubernetes Security 101: OWASP Natal Virtual Meeting](https://youtu.be/CF-ScdbhU5o) 🇧🇷

[Rory's McCune **@raesene** Kubernetes Security Lab | Rawkode Live workshop](https://youtu.be/Srd1qqxDReA)

## Blogs and Articles

[Cloud native security for your clusters](https://kubernetes.io/blog/2020/11/18/cloud-native-security-for-your-clusters)

[Container Security: Examining Potential Threats to the Container Environment](https://www.trendmicro.com/vinfo/us/security/news/security-technology/container-security-examining-potential-threats-to-the-container-environment)

[Kubernetes securityContext: Linux capabilities in Kubernetes](https://snyk.io/blog/kubernetes-securitycontext-linux-capabilities/)

[10 Kubernetes Security Context settings you should understand](https://snyk.io/blog/10-kubernetes-security-context-settings-you-should-understand/)

[Kubesploit: A New Offensive Tool for Testing Containerized Environments](https://www.cyberark.com/resources/threat-research-blog/kubesploit-a-new-offensive-tool-for-testing-containerized-environments)  

[Securing Kubernetes Clusters by Eliminating Risky Permissions](https://www.cyberark.com/resources/threat-research-blog/securing-kubernetes-clusters-by-eliminating-risky-permissions)

[Using Kubelet Client to Attack the Kubernetes Cluster](https://www.cyberark.com/resources/threat-research-blog/using-kubelet-client-to-attack-the-kubernetes-cluster)

[Eight Ways to Create a Pod](https://www.cyberark.com/resources/threat-research-blog/eight-ways-to-create-a-pod)

[Risk8s Business: Risk Analysis of Kubernetes Clusters](https://tldrsec.com/guides/kubernetes/)

[How to Set Up and Manage Logs with Kubernetes](https://iamondemand.com/blog/how-to-set-up-and-manage-logs-with-kubernetes/)

[The Current State of Kubernetes Threat Modelling](https://www.marcolancini.it/2020/blog-kubernetes-threat-modelling/)

[Hildegard: New TeamTNT Cryptojacking Malware Targeting Kubernetes](https://unit42.paloaltonetworks.com/hildegard-malware-teamtnt/)

[The Basics of Keeping Kubernetes Clusters Secure](https://www.trendmicro.com/vinfo/us/security/news/security-technology/the-basics-of-keeping-your-kubernetes-cluster-secure-part-1)

[The Basics of Keeping Kubernetes Cluster Secure: Worker Nodes and Related Components](https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/the-basics-of-keeping-kubernetes-cluster-secure-worker-nodes-and-related-components)

[How to Secure Your Kubernetes Cluster](https://containerjournal.com/topics/container-security/how-to-secure-your-kubernetes-cluster/)

[Kubernetes Security 101: Best Practices To Secure Your Cluster](https://www.devseccon.com/kubernetes-security-101-best-practices-to-secure-your-cluster-secadvent-day-17/)

[Kubernetes Security](https://kubernetes-security.info/)

[Introducing Kubernetes Goat](https://blog.madhuakula.com/introducing-kubernetes-goat-8624f6d70e9e)

[Threat Matrix for Kubernetes](https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/)

[Open Sourcing the Kubernetes Security Audit](https://www.cncf.io/blog/2019/08/06/open-sourcing-the-kubernetes-security-audit/)

[Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/)

[Protecting Kubernetes: The Kubernetes Attack Matrix and How to Mitigate Its Threats](https://security.stackrox.com/rs/219-UEH-533/images/StackRox-Whitepaper-Kubernetes_Attack_Matrix_and_Mitigation.pdf)

[Securing the 4Cs of Cloud Native](https://www.trendmicro.com/vinfo/us/security/news/virtualization-and-cloud/securing-the-4-cs-of-cloud-native-systems-cloud-cluster-container-and-code)

[CVE-2018-18264 Privilege escalation through Kubernetes dashboard](https://sysdig.com/blog/privilege-escalation-kubernetes-dashboard)

[Certified Kubernetes Security Specialist (CKS) exam guide](https://medium.com/cooking-with-azure/certified-kubernetes-security-specialist-cks-exam-guide-a8fc2b4c47ea)

[A Deep Dive Into Kubernetes Schema Validation](https://www.datree.io/resources/kubernetes-schema-validation)

## Books

[Hacking Kubernetes by Andrew Martin, Michael Hausenblas](https://learning.oreilly.com/library/view/hacking-kubernetes/9781492081722/)

[Learn Kubernetes Security by Kaizhe Huang and Pranjal Jumde](https://www.amazon.com/Learn-Kubernetes-Security-orchestrate-microservices-ebook/dp/B087Q9G51R)

[Kubernetes Security by Liz Rice and Michael Hausenblas](https://info.aquasec.com/kubernetes-security)

[Container Security by Liz Rice](https://containersecurity.tech/)

[Kubernetes: Up and Running, Second Edition by Brendan Burns, Joe Beda and Kelsey Hightower](https://azure.microsoft.com/en-us/resources/kubernetes-up-and-running/)

[The Kubernetes Book by Nigel Poulton and Pushkar Joglekar](https://www.amazon.com/dp/B072TS9ZQZ)

[Kubernetes Patterns: Reusable Elements for Designing Cloud-Native Applications by Bilgin Ibryam & Roland Huß](https://www.redhat.com/cms/managed-files/cm-oreilly-kubernetes-patterns-ebook-f19824-201910-en.pdf)

## Certifications

- [CKAD](https://www.cncf.io/certification/ckad/)

- [CKA](https://www.cncf.io/certification/cka/)

- [Certified Kubernetes Administrator (CKA) Course](https://github.com/kodekloudhub/certified-kubernetes-administrator-course)

- [CKS](https://www.cncf.io/certification/cks/)

- [Certified Kubernetes Security Specialist (CKS)](https://github.com/walidshaari/Certified-Kubernetes-Security-Specialist)

- [CKSS-Certified-Kubernetes-Security-Specialist](https://github.com/ibrahimjelliti/CKSS-Certified-Kubernetes-Security-Specialist)

- [Certified Kubernetes Security Specialist Study Guide](https://github.com/stackrox/Kubernetes_Security_Specialist_Study_Guide)

- [References for CKS Exam Objectives](https://github.com/abdennour/certified-kubernetes-security-specialist)

## CVEs

[Exploring container security: Vulnerability management in open-source Kubernetes](https://cloud.google.com/blog/products/containers-kubernetes/exploring-container-security-vulnerability-management-in-open-source-kubernetes)

[CVE-2018-18264](https://nvd.nist.gov/vuln/detail/CVE-2018-18264)

[CVE-2019-11247](https://nvd.nist.gov/vuln/detail/CVE-2019-11247)

[CVE-2019-11249](https://nvd.nist.gov/vuln/detail/CVE-2019-11249)

[CVE-2020-8558 PoC](https://github.com/tabbysable/POC-2020-8558)

[CVE-2020-8559 PoC](https://github.com/tabbysable/POC-2020-8559)

[CVE-2020-8559 PoC 2](https://github.com/tdwyer/CVE-2020-8559)

[CVE-2020-10749 PoC](https://github.com/knqyf263/CVE-2020-10749)


## Slides

[Communication is Key - Understanding Kubernetes Networking (KubeCon EU 2020)](https://static.sched.com/hosted_files/kccnceu20/3d/Communication_is_Key.pdf)

[Seccomp Profiles and you: A practical guide (KubeCon EU 2020)](https://www.slideshare.net/DuffieCooley/seccomp-profiles-and-you-a-practical-guide)

[Advanced Persistence Threats: The Future of Kubernetes Attacks (KubeCon EU 2020)](https://speakerdeck.com/iancoldwater/advanced-persistence-threats-the-future-of-kubernetes-attacks)

[Help! My Cluster Is On The Internet!](https://bit.ly/SamK8sSec)

## Trainings

[Secure Kubernetes](https://securekubernetes.com/)

[Cloud Native Security Tutorial](https://tutorial.kubernetes-security.info/)

[Kubernetes Security (Advanced Concepts)](https://acloudguru.com/course/kubernetes-security-advanced-concepts)

[Kubernetes Goat Guide](https://madhuakula.com/kubernetes-goat/)

[Katacoda Kubernetes Goat Videos](https://katacoda.com/madhuakula/scenarios/kubernetes-goat)

[Attacking and Auditing Docker Containers and Kubernetes Clusters](https://github.com/Kloudle/attacking-and-auditing-docker-containers-and-kubernetes-clusters-training)

[A Cloud Guru Kubernetes Security](https://acloudguru.com/course/kubernetes-security)

[SANS Cloud-Native Security Defending Containers and Kubernetes](https://www.sans.org/event/stay-sharp-blue-team-ops-and-cloud-dec-2020/course/cloud-native-security-defending-containers-kubernetes)

[Tutorial: Getting Started With Cloud-Native Security - KubeCon EU 2020 - Liz Rice & Michael Hausenblas](https://youtu.be/MisS3wSds40)

[Control Plane Security Training](https://control-plane.io/training/)

[Kubernetes CKS Exam Simulator](https://killer.sh/cks)

[Kubernetes Security Workshop](https://github.com/scotty-c/kubernetes-security-workshop)

[Linux Academy - Kubernetes Security](https://github.com/linuxacademy/content-kubernetes-security)

[Mumshad's KodeCloud Certified kubernetes security specialist **cks**](https://kodekloud.com/p/certified-kubernetes-security-specialist-cks)

## Repositories / Tools

### Learning

[kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

[krew](https://krew.sigs.k8s.io/docs/user-guide/setup/install/)

[Bust-a-Kube](https://www.bustakube.com/)

[kube-goat](https://github.com/ksoclabs/kube-goat)

[Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat)

[Kubernetes Networking Labs for KubeCon EU 2020 Talk](https://github.com/korvus81/k8s-net-labs)

[CNCF Security Audits](https://github.com/magnologan/cncf-security-audits)

[Kube Security Lab: Learn from Kuberenetes attacks using Ansible and KinD](https://github.com/raesene/kube_security_lab)

### Attacking

[kubesploit](https://github.com/cyberark/kubesploit)  

[kubeletctl](https://github.com/cyberark/kubeletctl)

[kube-hunter](https://github.com/aquasecurity/kube-hunter)

[Peirates](https://github.com/inguardians/peirates)

### Defending

[KubiScan](https://github.com/cyberark/KubiScan)

[Kubernetes Audit by Trail of Bits](https://github.com/trailofbits/audit-kubernetes)

[kubeaudit](https://github.com/Shopify/kubeaudit)

[falco](https://github.com/falcosecurity/falco)

[kubesec](https://github.com/controlplaneio/kubesec)

[kube-bench](https://github.com/aquasecurity/kube-bench)

[trivy](https://github.com/aquasecurity/trivy)

[MKIT](https://github.com/darkbitio/mkit)

[kubetap](https://github.com/soluble-ai/kubetap)

[kube-forensics](https://github.com/keikoproj/kube-forensics)

[k8s-security-dashboard](https://github.com/k8scop/k8s-security-dashboard)

[CIS Kubernetes Benchmark - InSpec Profile](https://github.com/dev-sec/cis-kubernetes-benchmark)

[Kube PodSecurityPolicy Advisor](https://github.com/sysdiglabs/kube-psp-advisor)

[Inspektor Gadget](https://github.com/kinvolk/inspektor-gadget)

[Starboard](https://github.com/aquasecurity/starboard)

[Advocacy Site for Kubernetes RBAC](https://github.com/mhausenblas/rbac.dev)

[Helm-Snyk](https://github.com/snyk-labs/helm-snyk)

[Krane](https://github.com/appvia/krane)

[rakkess](https://github.com/corneliusweig/rakkess)

[kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can)

[Kubernetes Security - Best Practice Guide](https://github.com/freach/kubernetes-security-best-practice)

[External Secrets](https://github.com/external-secrets/external-secrets)

[KubeLinter](https://github.com/stackrox/kube-linter)

[Open Policy Agent](https://www.openpolicyagent.org)

[Gatekeeper](https://github.com/open-policy-agent/gatekeeper)

[Kyverno](https://kyverno.io)


## Papers

[Kubernetes Security Assessment - Final Report - May 2019](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2019/findings/Kubernetes%20Final%20Report.pdf)

[Kubernetes Security Whitepaper - June 2019](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2019/findings/Kubernetes%20Final%20Report.pdf)

[Kubernetes Threat Model - June 2019](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2019/findings/Kubernetes%20Threat%20Model.pdf)

[Kubernetes Attack Tree](https://github.com/cncf/financial-user-group/tree/master/projects/k8s-threat-model)

[Attacking Kubernetes - A Guide for Administrators and Penetration Testers](https://github.com/kubernetes/community/blob/master/sig-security/security-audit-2019/findings/AtredisPartners_Attacking_Kubernetes-v1.0.pdf)

[CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes/)

[Kubernetes é seguro por default ou à prova de má configuração?](https://p0ssuidao.medium.com/kubernetes-%C3%A9-seguro-por-default-ou-aprova-de-m%C3%A1-configura%C3%A7%C3%A3o-9d3bccc2f342) 🇧🇷

## Podcasts

[TGI Kubernetes](https://www.youtube.com/playlist?list=PL7bmigfV0EqQzxcNpmcdTJ9eFRPBe-iZa)

[The Podlets](https://thepodlets.io)

[Kubecast](https://www.kubecast.com/)

[Kubernetes Podcast (from Google)](https://kubernetespodcast.com/)

[PodCTL - Enterprise Kubernetes](https://www.podctl.com/)

## Community

### Slacks

[Kubernetes Slack](https://kubernetes.slack.com)

[CNCF Slack](https://cloud-native.slack.com)

[Kubernetes Canada Slack](https://k8scanadaslack.herokuapp.com/)

### Newsletters

[kubelist](https://kubelist.com/) 
[LWKD](http://lwkd.info/)

### Jobs

[Kube Careers](https://kube.careers/)

### K8s Managed Services

[AKS](https://docs.microsoft.com/en-us/azure/aks/)

[EKS](https://aws.amazon.com/eks/)

[GKE](https://cloud.google.com/kubernetes-engine/)

### K8s Alternatives

[Docker Swarm](https://docs.docker.com/get-started/swarm-deploy/)

[Apache Mesos](https://mesos.apache.org/)

[HashiCorp Nomad](https://www.nomadproject.io/)

[Red Hat Openshift](https://www.openshift.com/)

### Other Awesome Lists

[kubepwn](https://github.com/alexivkin/kubepwn)

[awesome-kubernetes-security](https://github.com/ksoclabs/awesome-kubernetes-security)

[awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)

[awesome-istio](https://github.com/mstrYoda/awesome-istio)

[awesome-falco](https://github.com/developer-guy/awesome-falco)

[awesome-cloud-native](https://github.com/rootsongjc/awesome-cloud-native)

[awesome-opa](https://github.com/anderseknert/awesome-opa)

## Honk the Planet!

<br>
    <img src="https://github.com/magnologan/awesome-k8s-security/blob/master/honk.gif">
<br>
