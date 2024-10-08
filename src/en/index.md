---
# https://vitepress.dev/reference/default-theme-home-page
layout: page

hero:
  name: OzHera
  text: Application Performance Monitoring (APM) platform in the era of cloud-native.
  tagline: OzHera is an Application Performance Monitoring (APM) platform designed for the cloud-native era. It revolves around applications and integrates capabilities such as metric monitoring, distributed tracing, logging, and alerting. The platform's mission is to enhance the online stability of applications and enable businesses to detect and locate issues within 1 minute and 5 minutes, respectively, when problems occur.
  image:
    src: /images/architecture.png
    alt: architecture
  actions:
    - theme: brand
      text: What is OzHera
      link: /en/guide/introduction.md
    - theme: alt
      text: Quick Start
      link: /en/guide/quick-start.md
features:
  - title: <font color="red">Embrace Cloud-Native</font>
    details: OzHera follows the Opentracing standard and integrates with various open-source stars like OpenTelemetry, Grafana, Prometheus, Elasticsearch (ES), CAdvisor, and more.
  - title: <font color="red">Precise Alerting</font>
    details: Based on RPC and custom business error code parsing, OzHera extracts business availability metrics (business availability = 1 - "abnormal" request count / total request count). This allows for accurate representation of the system's true health status and eliminates the interference of ineffective alerts.
  - title: <font color="red">Swift Issue Resolution</font>
    details: Based on traceId, OzHera establishes a closed-loop linkage between alerts, metrics, distributed tracing, and logs, significantly improving user issue resolution efficiency.
  - title: <font color="red">Cost-Effective</font>
    details: Storage costs are less than one in a thousand, meeting 99.9% of tracing needs.
  - title: <font color="red">Enterprise-Grade Observability Product</font>
    details: OzHera features comprehensive account, permission, application management, and message notification mechanisms. Core linkage modules are decoupled, ensuring minimal intrusion into business systems. It has undergone numerous stress tests at Xiaomi, handling over 1 PB of raw data daily.
  - title: <font color="red">Artificial Intelligence</font>
    details: The cutting-edge artificial intelligence technology has been introduced, using AI tools to help you quickly pinpoint issues, analyze the causes in-depth, and provide personalized repair suggestions. Let intelligence lead your application monitoring, achieving intelligent management and optimization.
---

<script setup>
import Home from '@theme/components/Home.vue'
</script>

<Home />
