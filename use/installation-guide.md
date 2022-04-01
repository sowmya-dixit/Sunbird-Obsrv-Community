# Installation Guide

All components in Sunbird Obsrv can be installed through automation scripts. The automation scripts require [Ansible](https://docs.ansible.com/ansible/latest/index.html) as a prerequisite. Some of the components also require [helm](https://helm.sh/docs/) as a prerequisite to run the component on [Kubernetes](https://kubernetes.io).

#### Telemetry Service

{% embed url="https://github.com/project-sunbird/sunbird-devops/tree/release-4.8.0/kubernetes/helm_charts/core/telemetry" %}
Telemetry Service helm chart
{% endembed %}

#### Data Pipeline

{% embed url="https://github.com/project-sunbird/sunbird-data-pipeline/tree/release-4.8.0/kubernetes/ansible/roles/flink-jobs-deploy" %}
Ansible role for Data Pipeline
{% endembed %}

#### Data Service

{% embed url="https://github.com/project-sunbird/sunbird-devops/tree/release-4.8.0/kubernetes/helm_charts/core/analytics" %}
Data Service helm chart
{% endembed %}

#### Report Service

{% embed url="https://github.com/project-sunbird/sunbird-devops/tree/release-4.8.0/kubernetes/helm_charts/core/report" %}
Report Service helm chart
{% endembed %}

#### Summarisers

{% embed url="https://github.com/project-sunbird/sunbird-data-pipeline/tree/release-4.8.0/ansible/roles/data-products-deploy" %}
Ansbile role for Summarizer data products
{% endembed %}
