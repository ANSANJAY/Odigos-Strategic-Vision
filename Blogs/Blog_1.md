# The Smoothest APM with eBPF: An Introduction to Odigos

## Introduction
In today’s software landscape, observability is essential. As systems become increasingly distributed, monitoring and tracing application performance becomes more complex. Traditional APM (Application Performance Monitoring) tools often require extensive instrumentation, slowing down development and impacting performance.

Enter Odigos: an open-source observability tool that seamlessly integrates eBPF and OpenTelemetry to offer automatic, code-free instrumentation. In this blog, we will explore why Odigos is emerging as the smoothest APM solution and how it leverages cutting-edge technologies to simplify observability.

## Why Odigos Stands Out
Odigos addresses key challenges in observability by providing:
- **Automatic Instrumentation:** No need for manual code changes or language-specific agents.
- **Multi-Language Support:** Works with Go, Java, Python, .NET, and Node.js.
- **Efficient Data Collection:** Leverages eBPF for high-performance, low-overhead data gathering.
- **Easy Integration:** Supports OpenTelemetry format, compatible with popular backends like Grafana and Jaeger.

### Odigos vs. Traditional APM Tools
Traditional APMs often involve intrusive agents or extensive configuration. In contrast, Odigos offers a lightweight, automatic approach, making it faster and more efficient. This is particularly valuable in high-traffic environments where performance impact must be minimized.

## How Odigos Works
Odigos seamlessly detects application languages and uses the appropriate instrumentation method:
- **eBPF for Compiled Languages:** Utilizes kernel-level tracing for minimal impact.
- **OpenTelemetry for VM-Based Languages:** Provides standard tracing without manual intervention.

By combining these approaches, Odigos ensures comprehensive observability across diverse application stacks.

## Real-World Impact
Imagine monitoring a microservice architecture with dozens of interconnected services. Setting up traditional APMs would require configuring each service separately, adding agents, and maintaining compatibility. With Odigos, the setup is automatic and unified, saving time and reducing errors.

## Conclusion
Odigos is reshaping the APM landscape with its automatic, efficient, and versatile approach to observability. By leveraging eBPF and OpenTelemetry, it not only simplifies setup but also ensures optimal performance. Whether you're a DevOps engineer or a developer, Odigos makes observability smoother and more manageable.

Stay tuned for the next blog in this series, where we will dive deeper into eBPF and its role in modern observability.

