# Hi, I'm Thomas

DevOps student at Chas Academy, Stockholm. Building a homelab to learn infrastructure the hard way — Terraform, Ansible, Kubernetes, and GitOps.

Instead of just reading theory, I built this from scratch with zero prior knowledge. I learn better by doing first — hands-on before the theory hits in school, then more practice afterwards.

The goal is to land a job as a DevOps engineer, with a focus on infrastructure rather than the dev side. The parts I've enjoyed most: Terraform, Ansible, GitOps, and getting backups right.

![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![Kubernetes](https://img.shields.io/badge/k3s-326CE5?logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?logo=argo&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)

## What I'm working on

**[homelab](https://github.com/Thomas-3145/homelab)** — my main project. HA k3s cluster on Proxmox + Raspberry Pi 5, fully managed with GitOps.

![CI](https://github.com/Thomas-3145/homelab/actions/workflows/lint.yaml/badge.svg)

> Terraform provisions VMs, Ansible installs k3s, ArgoCD deploys everything from Git. 4 nodes, 3 control plane + 1 ARM64 worker. Longhorn for storage, SOPS for secrets, Cloudflare Tunnel for access.

**[ibindex-app](https://github.com/Thomas-3145/ibindex-app)** — Python/Streamlit app that fetches daily data on Swedish investment companies and suggests a portfolio allocation. Runs on my own k3s cluster, deployed via ArgoCD GitOps.

**Other projects:**
- **[jobsearch](https://github.com/Thomas-3145/jobsearch-arbetsformedlingen-python)** — Python script that searches jobs via the Arbetsformedlingen API
- **[python-project-creator](https://github.com/Thomas-3145/python-project-creator-bash)** — Bash tool for scaffolding Python projects

## Blog

I write about the homelab journey at **[3145.blog](https://3145.blog)** — real debugging sessions, architectural decisions, and lessons learned building infrastructure from scratch.

## Looking for

Internship (LIA) for autumn 2026 — Cloud, Platform Engineering, or SRE.
