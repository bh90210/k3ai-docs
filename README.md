---
description: >-
  K3Ai is a lightweight infrastructure-in-a-box ready to run on top of edge and
  IoT devices which provides a set of Artificial Intelligence platforms and
  solutions
---

# K3ai \(keɪ3ai\)

## What is K3ai

![](.gitbook/assets/demo.gif)

K3ai is a lightweight infrastructure-in-a-box specifically built to install and configure AI tools and platforms to quickly experiment and/or run in production over edge devices.

Ready to experiment?

```text
curl -sfL https://get.k3ai.in | bash -
```

Curious? Checkout the documentation at [**https://docs.k3ai.in**](https://docs.k3ai.in)

Looking for more interaction? join our Slack channel [**here**](https://join.slack.com/t/kf5ikfai/shared_invite/zt-huh5ib1f-ZyBxqyBDKooGNvpd5_MoQQ)\*\*\*\*

## Components of K3ai

Currently, we install the following components \(the list is changing and growing\):

* Kubernetes based on K3s from Rancher: [https://k3s.io/](https://k3s.io/)
* Kubeflow pipelines: [https://github.com/kubeflow/pipelines](https://github.com/kubeflow/pipelines)
* Argo Workflows: [https://github.com/argoproj/argo](https://github.com/argoproj/argo)
* Kubeflow: [https://www.kubeflow.org/](https://www.kubeflow.org/) - **\(coming soon\)**
* NVIDIA GPU support: [https://docs.nvidia.com/datacenter/cloud-native/index.html](https://docs.nvidia.com/datacenter/cloud-native/index.html)
* NVIDIA Triton inference server: [https://github.com/triton-inference-server/server/tree/master/deploy/single\_server](https://github.com/triton-inference-server/server/tree/master/deploy/single_server) **\(coming soon\)**
* Tensorflow Serving: [https://www.tensorflow.org/tfx/serving/serving\_kubernetes](https://www.tensorflow.org/tfx/serving/serving_kubernetes):
  * ResNet
  * Mnist **\(coming soon\)**

