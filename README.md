# Hello

Welcome user. I operate a small handful of personal/private repositories mainly
centered around fun little code projects, my aging homelab/home server setup,
and maybe, one day, some pipelines and public cloud builds to get a website going.

I do not contribute to public projects with this name - most of the employers I've
had the pleasure of working with actually forbid unapproved open-source
contribution as they want first right of refusal for anything I come up with...
Not that it's particularly gamechanging, just that's how they roll.

## My Projects

### HomeStacks (Private)

- A set of configurators created for each stage of my home lab equipment lifecycle
  - __Scripts:__ Pull down repositories, configure Docker/PodMan, start local clusters, install GitOps tools eg. ArgoCD
  - __Docker:__ Stacks folders containing collections of docker-compose's that can be used to stand up homelab features like Newsgroup downloaders and Plex Media Servers ;)
  - __Kubernetes:__ Lots of straight-up YAML deployables, Kustomizations and Helm Charts for testing things in Kubernetes using Rancher k3d, KIND and/or Minikube.
  - __OpenShift:__ An offshoot of the Kuberntes work, but focussing on ArgoCD/GitOps Operator patterns, initializing entire clusters single-yaml ignition-style, and figuring out how some super-sus operators actually work.

HomeStacks commands a small variety of HomeLab equiment:

- __RASPI:__ Mainly runs as an emergency network access head in my rack, and runs neovim on console pretty good for config hacks when doing major rack maintenance.
- __FLEXO:__ My trusty Gigabyte Brix 4th generation i7 mini PC.  It still runs 24x7 after all these years.
  - Storage and Media Streaming
- __PROXMOX:__ A Dell PowerEdge T630 running Proxmox for virtualization work.
  - Hosts OpenShift and KIND clusters.
  - Hosts the all-important MINECRAFT SERVER!

### EDDN Projects

- Reference: [https://eddn.edcd.io/](https://eddn.edcd.io/)
- I want to store all known Elite Dangerous galaxy discovery data and have a realtime constant stream of updates pushing into the solution.
- Looking at making a flexible message routing system with RabbitMQ that will allow multiple apps to pull meaningful messages out and perform various tasks on them.