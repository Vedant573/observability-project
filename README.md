# OpenTelemetry Distributed Tracing Implementation

A hands-on implementation of distributed tracing using OpenTelemetry to instrument microservices and visualize telemetry data for observability.

## 📋 Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Key Learnings](#key-learnings)
- [Screenshots](#screenshots)
- [Resources](#resources)

## 🎯 Overview

This project demonstrates the implementation of distributed tracing across microservices using OpenTelemetry (OTEL). The goal was to gain hands-on experience with observability concepts including:
- Automatic and manual instrumentation
- Trace context propagation across services
- Metrics collection and visualization
- Performance bottleneck identification


## 🛠️ Technologies Used

- **Language/Framework**: TypeScript, Python, Go, Docker
- **Observability Backend**: Jaeger, Grafana Tempo
- **Containerization**: Docker, Docker Compose
- **Additional Tools**: Prometheus, Grafana, JaegerUI

## ✅ Prerequisites

Before running this project, ensure you have:
- Docker and Docker Compose (recommended)
- Git


## 🎓 Key Learnings

Through this project, I gained practical experience with:

1. **Instrumentation Strategies**
   - Automatic instrumentation using OTEL libraries
   - Manual span creation for custom business logic
   - Adding span attributes and events for context

2. **Trace Context Propagation**
   - Understanding Trace Context 
   - Tracing and Trace Mapping
   - Maintaining trace continuity in async operations

3. **Performance Analysis**
   - Identifying slow operations through trace analysis
   - Understanding service dependencies
   - Measuring end-to-end request latency

4. **Observability Best Practices**
   - Semantic conventions for consistent naming
   - Sampling strategies to reduce overhead
   - Correlation between traces, metrics, and logs

## 📸 Screenshots

### Metrics Dashboard
<img width="1899" height="863" alt="Screenshot 2026-01-14 170745" src="https://github.com/user-attachments/assets/07df12c7-f3e7-4e4c-ac20-61b72ec62bfd" />
<img width="1900" height="860" alt="Screenshot 2026-01-14 170636" src="https://github.com/user-attachments/assets/82ef3d2b-fe23-45c3-894d-cf7d6f98de14" />
<img width="1899" height="863" alt="Screenshot 2026-01-14 171250" src="https://github.com/user-attachments/assets/8fa8152a-ccd2-438f-8815-49efcdaa972b" />
<img width="1908" height="858" alt="Screenshot 2026-01-14 172233" src="https://github.com/user-attachments/assets/f71b7934-793b-4b0e-aad1-9bfa9d1dafa4" />

*Performance metrics collected via OpenTelemetry*

### JaegerUI
<img width="1917" height="862" alt="Screenshot 2026-01-14 170940" src="https://github.com/user-attachments/assets/4cc472a2-afa2-4da5-9a4b-3581be374d31" />
<img width="1917" height="866" alt="Screenshot 2026-01-14 171027" src="https://github.com/user-attachments/assets/f0d59412-4a13-4579-ad0a-9a5db9d8d984" />


*Visual representation of microservice interactions*



## 📚 Resources

### Official Documentation
- [OpenTelemetry Documentation](https://opentelemetry.io/docs/)
- [OpenTelemetry Demo Application](https://github.com/open-telemetry/opentelemetry-demo)

### Additional Learning
- [CNCF OpenTelemetry Project](https://www.cncf.io/projects/opentelemetry/)
- [Distributed Tracing Concepts](https://opentelemetry.io/docs/concepts/observability-primer/)

## 🔄 How to Recreate This Project
Head on to the official OpenTelemetry documentation page for detailed steps and guide.


## 🤝 Contributing

This is a learning project, but suggestions and improvements are welcome! Feel free to open issues or submit pull requests.


**Note**: This project was created for educational purposes to learn OpenTelemetry and distributed tracing concepts.
