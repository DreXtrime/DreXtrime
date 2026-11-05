# Tanel Erik Neitov 
fullStack_DevOps  
readme or don't readme, but make sure to mark this down, hi

## Projects

**[ASUS Strix Fan Control](https://github.com/DreXtrime/AsusStrixExternalFanControl)**  | [LinkedIn blog post about it](https://lnkd.in/p/e6pSSBD2)  
Needed a software solution to control external fan speed on an old ASUS Strix gtx 1080 graphics card, since the software Asus built for it is kind of as(u)s. Took some reverse engineering to figure out how the software communicates with the graphics cards onboard microcontroller. But the work paid off and and I'm real proud of this one.  
`Ghidra` `x32dbg` `API monitor` `CI/CD`

**[GCP vLLM](https://github.com/DreXtrime/gcp-vllm-infra)**   
Had leftover credits for Google cloud, decided to setup a terraform ansible script to setup a VM with an NVIDIA A100, vLLM and expose it over wireguard to run various models there. Turns out google does not like it very much though.  
`Terraform` `Ansible`  

**[Ollama bench](https://github.com/DreXtrime/ollama-bench)**    
How good are local models at following instructions? How do they act at different quantisation levels?  
I used this tool to compare prompts outputs directly from various models running in ollama. Wraps the ollama api to run tests on a remote gpu server.  
`Python` `Ollama` `HTML`  

**[Voyager](https://github.com/DreXtrime/voyager)**
Built out a full production-grade cloud infrastructure on GCP from scratch. Two environments, GitOps deployment pipeline, secrets management, monitoring and alerting.  
`GCP` `Terraform` `Kubernetes` `ArgoCD` `GitLab CI`  

**[Cloud Cartographer](https://github.com/DreXtrime/cloud-cartographer)**
Before building Voyager, I needed pricing estimations. Stress tested the app locally, found where it actually breaks, and did a full cost breakdown comparing AWS and GCP.  
`GCP` `AWS` `Locust` `Prometheus` `Grafana` `Docker`


**[Sherlock Logs](https://github.com/DreXtrime/sherlock-logs)**    
A containerized infrastructure setup with centralized monitoring and logging, fully automated with Vagrant and Ansible. A dedicated monitoring VM runs Prometheus, Grafana, and the ELK stack to provide real-time visibility across all infrastructure components.  
`Ansible` `Vagrant` `Grafana` `Prometheus` `ELK Stack`  
