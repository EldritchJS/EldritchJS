### Jason Schlessman

Senior Principal Software Engineer at Red Hat, on the Open Accelerator Team. I build and harden OpenShift clusters for research computing at the Mass Open Cloud.

**Now**

- **Compliance-ready OpenShift.** FIPS 140-3, NIST SP 800-171 (scanned as the NIST 800-53 Moderate baseline) and the HIPAA Security Rule, delivered as Helm charts and GitOps in [CCI-MOC/oac-apps](https://github.com/CCI-MOC/oac-apps). On the reference cluster, node compliance-scan failures went from 377 to 0, and nine charts reproduce that cluster.
- **FIPS container images.** Rebuilt the Pure Storage COSI driver and the upstream COSI controller and sidecar on Red Hat toolchains so their crypto runs through RHEL's validated OpenSSL ([CCI-MOC/pure-cosi](https://github.com/CCI-MOC/pure-cosi)).
- **GPU infrastructure.** H100 clusters on OpenShift, GPU passthrough to VMs, multi-tenant isolation testing, and NCCL and RDMA/RoCE benchmarking.

**Before**

- **Image forensics** at Red Hat Research: [pyIFD](https://github.com/EldritchJS/pyIFD), a Python toolkit for image forgery detection.
- **ML on OpenShift:** adversarial example generation and retraining pipelines, NLP over CORD-19.
- **Embedded and FPGA:** ESP32, STM32 and RISC-V soft cores. [esp32-gdb-mqtt](https://github.com/EldritchJS/esp32-gdb-mqtt) is a wireless GDB server over MQTT.

**Tools:** OpenShift, Kubernetes, Helm, Argo CD, Advanced Cluster Management, Compliance Operator, ACS, KubeVirt, Python, Go, C.
