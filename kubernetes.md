# Kubernetes

Exam prep lives in [cka.md](cka.md).

## Learning resources

- [Kubernetes Learning Resources (spreadsheet)](https://docs.google.com/spreadsheets/d/10NltoF_6y3mBwUzQ4bcQLQfCE1BWSgUDcJXy-Qp2JEU/edit#gid=0)
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes)
- [47 Things To Become a Kubernetes Expert](https://ymmt2005.hatenablog.com/entry/k8s-things)
- [Kubernetes Overview Diagrams](https://brennerm.github.io/posts/kubernetes-overview-diagrams.html)
- [Kubernetes Examples](https://github.com/ContainerSolutions/kubernetes-examples)

## Install and clusters

- [Kubernetes by kubeadm config yamls](https://medium.com/@kosta709/kubernetes-by-kubeadm-config-yamls-94e2ee11244)
- [Deploy Kubernetes with kubeadm on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-create-a-kubernetes-cluster-using-kubeadm-on-ubuntu-18-04)
- [Create a Kubernetes multinode cluster](https://linux.xvx.cz/2018/04/create-kubernetes-multinode-cluster.html)
- [hobby-kube: Kubernetes on a budget](https://github.com/hobby-kube/guide)
- [Upgrading Homelab Kubernetes Cluster from 1.20 to 1.21](https://www.lisenet.com/2021/upgrading-homelab-kubernetes-cluster-from-1-20-to-1-21/)
- [Using dnsmasq with a local kind clusters](https://medium.com/@charled.breteche/using-dnsmasq-with-a-local-kind-clusters-9a27c8987073)
- [Kubernetes NFS and dynamic NFS provisioning](https://medium.com/@myte/kubernetes-nfs-and-dynamic-nfs-provisioning-97e2afb8b4a9)

## Internals

- [Kubernetes under the hood](https://github.com/mvallim/kubernetes-under-the-hood)
- [What happens when k8s](https://github.com/jamiehannaford/what-happens-when-k8s)
- [What happens when kubectl run is executed?](https://faun.pub/what-happens-when-kubectl-run-is-executed-fb5ea9eb42b8)
- [What Happens When Deleting a Pod](https://medium.com/@meng.yan/what-happens-when-deleting-a-pod-d1219c7e1b53)
- [How does 'kubectl exec' work? / Docker shim](https://erkanerol.github.io/post/how-kubectl-exec-works/)
- [How It Works: kubectl exec / CRI-O](https://itnext.io/how-it-works-kubectl-exec-e31325daa910)
- [Demystifying kube-proxy](https://mayankshah.dev/blog/demystifying-kube-proxy/)
- [Layer-by-Layer Cgroup in Kubernetes](https://medium.com/geekculture/layer-by-layer-cgroup-in-kubernetes-c4e26bda676c)
- [Quality of Service Management for Pods by Kubelet](https://www.sobyte.net/post/2022-03/kubelet-quality-of-service-management-for-pods/)
- [In-depth analysis of the election mechanism in Kubernetes](https://www.sobyte.net/post/2022-06/k8s-election/)

## Kubernetes API

- [Kubernetes API Basics: Resources, Kinds, and Objects](https://iximiuz.com/en/posts/kubernetes-api-structure-and-terminology/)
- [How To Call Kubernetes API using Simple HTTP Client](https://iximiuz.com/en/posts/kubernetes-api-call-simple-http-client/)
- [How To Call Kubernetes API using Go: Types and Common Machinery](https://iximiuz.com/en/posts/kubernetes-api-go-types-and-common-machinery/)
- [How To Extend Kubernetes API: Kubernetes vs. Django](https://iximiuz.com/en/posts/kubernetes-api-how-to-extend/)
- [How To Develop Kubernetes CLIs Like a Pro](https://iximiuz.com/en/posts/kubernetes-api-go-cli/)
- [An example of using dynamic client of k8s.io/client-go](https://ymmt2005.hatenablog.com/entry/2020/04/14/An_example_of_using_dynamic_client_of_k8s.io/client-go)
- [The Kubernetes dynamic client](https://caiorcferreira.github.io/post/the-kubernetes-dynamic-client/)
- [Kubernetes Python client](https://github.com/kubernetes-client/python)

## Configuration

- Kubernetes configuration patterns
  - [Part 1: Patterns for Kubernetes primitives](https://developers.redhat.com/blog/2021/04/28/kubernetes-configuration-patterns-part-1-patterns-for-kubernetes-primitives#configuration_with_secrets)
  - [Part 2: Patterns for Kubernetes controllers](https://developers.redhat.com/blog/2021/05/05/kubernetes-configuration-patterns-part-2-patterns-for-kubernetes-controllers#configuration_with_central_configmaps)
- [Set OpenAPI patch strategy for Kubernetes Custom Resources (Kustomize)](https://tech.aabouzaid.com/2022/11/set-openapi-patch-strategy-for-kubernetes-custom-resources-kustomize.html)

## Resources, limits and autoscaling

- [Who murdered my lovely Prometheus container in Kubernetes cluster?](https://engineering.linecorp.com/en/blog/prometheus-container-kubernetes-cluster/)
- [How to rightsize the Kubernetes resource limits](https://sysdig.com/blog/kubernetes-resource-limits/)
- [Kubernetes Resource Management in Production](https://itnext.io/kubernetes-resource-management-in-production-d5382c904ed1)
- [Architecting Kubernetes clusters: choosing the best autoscaling strategy](https://learnk8s.io/kubernetes-autoscaling-strategies)
- [Vertical Pod Autoscaling: The Definitive Guide](https://povilasv.me/vertical-pod-autoscaling-the-definitive-guide/)

## Deployments

- Kubernetes Deployment Antipatterns
  - [Part 1](https://medium.com/containers-101/kubernetes-deployment-antipatterns-part-1-9e7b54a08b9)
  - [Part 2](https://medium.com/containers-101/kubernetes-deployment-antipatterns-part-2-2af25a710bc0)
  - [Part 3](https://medium.com/containers-101/kubernetes-deployment-antipatterns-part-3-dfbdd2fd3292)

## Troubleshooting

- [Breaking down and fixing Kubernetes](https://itnext.io/breaking-down-and-fixing-kubernetes-4df2f22f87c3)
- [Ephemeral Containers: For a More Civilized Debugging Age](https://bmiguel-teixeira.medium.com/ephemeral-containers-for-a-more-civilized-debugging-age-399fa3162f3b)
- [How to Clean Up Old Containers and Images in Your Kubernetes Cluster](https://www.howtogeek.com/devops/how-to-clean-up-old-containers-and-images-in-your-kubernetes-cluster/)

## DNS

- [The life of a DNS query in Kubernetes](https://www.nslookup.io/learning/the-life-of-a-dns-query-in-kubernetes/)
- [Kubernetes Node Local DNS Cache](https://povilasv.me/kubernetes-node-local-dns-cache/)
- [Accessing kube-dns from your desktop](https://blog.kubiosec.io/accessing-kube-dns-from-your-desktop) (site offline)
- [Cilium: Debugging and Monitoring DNS issues in Kubernetes](https://cilium.io/blog/2019/12/18/how-to-debug-dns-issues-in-k8s)

## Networking

- [Why and How of Kubernetes Ingress (and Networking)](https://itnext.io/why-and-how-of-kubernetes-ingress-and-networking-6cb308ca03d2)
- [Network Policy Editor (Cilium)](https://editor.cilium.io/)
- [Network policy tutorial](https://github.com/networkpolicy/tutorial)
- [Cilium Code Walk Through Series](http://arthurchiao.art/blog/cilium-code-series/)

## Service mesh (Istio)

- [Istio Data Plane Pod Startup Process Explained](https://jimmysong.io/en/blog/istio-pod-process-lifecycle/)
- [Sidecar Injection, Transparent Traffic Hijacking, and Routing Process in Istio Explained in Detail](https://jimmysong.io/en/blog/sidecar-injection-iptables-and-traffic-routing/)
- [Traffic Types and Iptables Rules in Istio Sidecar Explained](https://jimmysong.io/en/blog/istio-sidecar-traffic-types/)
- [Understanding Istio and TCP service](https://tetrate.io/blog/understanding-istio-and-tcp-services/)
- [Istio Ingress vs. Kubernetes Ingress](https://software.danielwatrous.com/istio-ingress-vs-kubernetes-ingress/)
- [Using Istio Service Mesh as API Gateway](https://jimmysong.io/en/blog/istio-servicemesh-api-gateway/)
- [Why Would You Need SPIRE for Authentication With Istio?](https://jimmysong.io/en/blog/why-istio-need-spire/)
- [Locality Aware Routing](https://karlstoney.com/2020/10/01/locality-aware-routing/)

## Security

- [NSA, CISA release Kubernetes Hardening Guidance](https://www.nsa.gov/News-Features/Feature-Stories/Article-View/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/)
- [RBAC](https://rbac.dev/)
- [Using RBAC Authorization (Kubernetes docs)](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
- [Kubernetes Single Sign On: A detailed guide](https://www.talkingquickly.co.uk/kubernetes-sso-a-detailed-guide)
- [How to Generate a Self-Signed Certificate for Kubernetes](https://phoenixnap.com/kb/kubernetes-ssl-certificates)
- [Running Vault and Consul on Kubernetes](https://testdriven.io/blog/running-vault-and-consul-on-kubernetes/)

## Helm

- [13 Best Practices for using Helm](https://codersociety.com/blog/articles/helm-best-practices)
- [Using Helm To Include All Files From A Directory In-line](https://tratnayake.dev/helm-include-all-files-from-directory-in-line)
- [Understanding Helm upgrade flags --reset-values and --reuse-values](https://helm-playground.com/understanding-helm-upgrade-reset-reuse-values.html)
- [Helm: Advanced Commands](https://medium.com/geekculture/helm-advanced-commands-9365097475b)

## GitOps

### Argo

- [ArgoCD: a Helm chart deployment, and working with Helm Secrets via AWS KMS](https://rtfm.co.ua/en/argocd-a-helm-chart-deployment-and-working-with-helm-secrets-via-aws-kms/)
- [Argo: Workflow Engine for Kubernetes](https://itnext.io/argo-workflow-engine-for-kubernetes-7ae81eda1cc5)
- [Create Argo CD local users](https://faun.pub/create-argo-cd-local-users-9e830db3763f)
- [ArgoCD with Kustomize and ksops](https://blog.devgenius.io/argocd-with-kustomize-and-ksops-2d43472e9d3b)
- [argocd-vault-plugin](https://argocd-vault-plugin.readthedocs.io/en/stable/)
- [kind, Keycloak and Argo CD with SSO](https://medium.com/@charled.breteche/kind-keycloak-and-argocd-with-sso-9f3536dd7f61)

### Flux

- [Manage your Kubernetes clusters with Flux2](https://medium.com/alterway/manage-your-kubernetes-clusters-with-flux2-82dd1cfe2a6a)

## Monitoring

- [Alerting with Prometheus on Kubernetes](http://elatov.github.io/2020/01/alerting-with-prometheus-on-kubernetes/)

## Admission webhooks

- [A Gentle Intro to Validation Admission Webhooks in Kubernetes](https://blog.container-solutions.com/a-gentle-intro-to-validation-admission-webhooks-in-kubernetes)
- [Building a Kubernetes Mutating Admission Webhook](https://didil.medium.com/building-a-kubernetes-mutating-admission-webhook-7e48729523ed)
- [Diving into Kubernetes MutatingAdmissionWebhook](https://medium.com/ibm-cloud/diving-into-kubernetes-mutatingadmissionwebhook-6ef3c5695f74)
- Getting Started to Write Your First Kubernetes Admission Webhook
  - [Part 1](https://medium.com/trendyol-tech/getting-started-to-write-your-first-kubernetes-admission-webhook-part-1-623f40c2adda)
  - [Part 2](https://medium.com/trendyol-tech/getting-started-to-write-your-first-kubernetes-admission-webhook-part-2-48d0b0b1780e)
- [Writing and testing Kubernetes webhooks using Kubebuilder v2](https://ymmt2005.hatenablog.com/entry/2019/08/10/Writing_and_testing_Kubernetes_webhooks_using_Kubebuilder_v2)

## Operators and controllers

- [Writing a Kubernetes Operator: From Zero to Hero](https://anupamgogoi.medium.com/writing-a-kubernetes-operator-from-zero-to-hero-8ca5dc2462b7)
- [Kubernetes Operators by Example](https://codeburst.io/kubernetes-operators-by-example-99a77ea4ac43)
- [From Zero to Kubernetes Operator](https://medium.com/@victorpaulo/from-zero-to-kubernetes-operator-dd06436b9d89)
- [A Practical Kubernetes Operator using Ansible: an example](https://itnext.io/a-practical-kubernetes-operator-using-ansible-an-example-d3a9d3674d5b)
- Getting Started With Kubernetes Operators
  - [Part 1: Helm based](https://www.velotio.com/engineering-blog/getting-started-with-kubernetes-operators-helm-based-part-1)
  - [Part 2: Ansible based](https://www.velotio.com/engineering-blog/getting-started-with-kubernetes-operators-ansible-based-part-2)
  - [Part 3: Go based](https://www.velotio.com/engineering-blog/getting-started-with-kubernetes-operators-golang-based-part-3)
- Kubernetes operators with Python
  - [Part 1: Creating CRDs](https://brennerm.github.io/posts/k8s-operators-with-python-part-1.html)
  - [Part 2: Implementing Controller](https://brennerm.github.io/posts/k8s-operators-with-python-part-2.html)
- Kubernetes Operator with Kubebuilder
  - [Part 1](https://janosmiko.com/blog/2023-03-02-tutorial-kubebuilder-1/)
  - [Part 2](https://janosmiko.com/blog/2023-03-03-tutorial-kubebuilder-2/)
  - [Part 3](https://janosmiko.com/blog/2023-03-04-tutorial-kubebuilder-3/)
- GitHub Repository Operator and Webhook with operator-sdk
  - [Part 1: Scaffold and first slice of the operator](https://pnguyen.io/posts/test-drive-kubernetes-operator-1/)
  - [Part 2: Update and delete of GitHub repository](https://pnguyen.io/posts/test-drive-kubernetes-operator-2/)
  - [Part 3: Creating a GitHub repository by cloning another repository](https://pnguyen.io/posts/test-drive-kubernetes-operator-3/)
  - [Part 4: Validation using webhooks](https://pnguyen.io/posts/test-drive-kubernetes-operator-4/)
- [Build a Highly Available Kubernetes Operator Using Golang](https://betterprogramming.pub/building-a-highly-available-kubernetes-operator-using-golang-fe4a44c395c2)
- [Creating a Redis operator with kubebuilder](https://www.mo4tech.com/k8s-operator-introduction.html)
- [Running logic of kubebuilder operator](https://programmer.ink/think/running-logic-of-kubebuilder-operator.html)
- [Kubebuilder installation, deployment and controller-runtime source analysis](https://www.fatalerrors.org/a/0Nl31Tg.html)
- [Kubernetes operators for resource management](https://www.stephenzoio.com/kubernetes-operators-for-resource-management/)
- [Writing a Kubernetes Controller: Part 1](https://fedepaol.github.io/blog/2020/12/07/writing-a-kubernetes-controller-part-1/)
- [Writing a Kubernetes Controller: Part 2](https://fedepaol.github.io/blog/2021/01/07/writing-a-kubernetes-controller-part-2/)
- [Testing Production Kubernetes Controllers](https://superorbital.io/blog/testing-production-controllers/)
