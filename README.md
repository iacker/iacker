<!--
  README profil GitHub — iacker (Erwan Billard)
  Thème NVIDIA : vert #76B900 sur fond #0D1117
  Libs externes : capsule-render · readme-typing-svg · skillicons.dev
                  github-readme-stats · shields.io
-->

<div align="center">

<img width="62%" src="./assets/logo.png" alt="iacker" />

### AI Infrastructure Engineer

**Je fais tourner des LLM sur GPU en production — et je maîtrise le coût, la latence et l'énergie qui vont avec.**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=22&duration=3600&pause=700&color=76B900&center=true&vCenter=true&width=820&lines=GPU+serving+%C2%B7+vLLM+%C2%B7+Kubernetes;IaC+%C2%B7+FinOps+GPU+%C2%B7+Observabilit%C3%A9;Agents+%C2%B7+MCP+%C2%B7+RAG+local)](https://git.io/typing-svg)

<img src="https://komarev.com/ghpvc/?username=iacker&label=Vues&color=76B900&style=flat-square" alt="vues" />
<img src="https://img.shields.io/github/followers/iacker?label=Followers&style=flat-square&color=76B900&labelColor=0D1117" alt="followers" />

</div>

---

## Ce que je fais

Ancien **DevSecOps** passé côté **infrastructure GPU / LLM**. Mon terrain, c'est la couche entre le modèle et le hardware : provisionner le GPU, servir le modèle, l'observer, et le rendre **rentable**.

- **`GPU / LLM serving`** — vLLM, quantization FP16/FP8, RunPod & bare-metal, dimensionnement, DCGM
- **`Kubernetes / Platform`** — k3s, Talos, Helm, GitOps (Flux/Argo), Kueue, autoscaling, hybride on-prem ↔ cloud
- **`IaC & FinOps`** — Terraform, coût €/token et énergie mesurés, budget guards, teardown propre
- **`Agents & tooling`** — MCP, RAG local, orchestration multi-agents
- **`Sécurité`** — DevSecOps, eBPF/NDR, supply chain, hardening

<div align="center">

[![Skills](https://skillicons.dev/icons?i=kubernetes,docker,terraform,pytorch,python,go,aws,azure,gcp,nix,linux,grafana,prometheus,bash&perline=14&theme=dark)](https://skillicons.dev)

</div>

---

## Projets

> La couche complète : **provisionner → servir → opérer → optimiser** un LLM sur GPU.

<div align="center">

[![terraform-runpod-vllm](https://github-readme-stats.vercel.app/api/pin/?username=iacker&repo=terraform-runpod-vllm&border_color=76B900&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900)](https://github.com/iacker/terraform-runpod-vllm)
[![gpu-infra-lab](https://github-readme-stats.vercel.app/api/pin/?username=iacker&repo=gpu-infra-lab&border_color=76B900&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900)](https://github.com/iacker/gpu-infra-lab)
[![Nimbridge](https://github-readme-stats.vercel.app/api/pin/?username=iacker&repo=Nimbridge&border_color=76B900&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900)](https://github.com/iacker/Nimbridge)
[![brain-rag-server](https://github-readme-stats.vercel.app/api/pin/?username=iacker&repo=brain-rag-server&border_color=76B900&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900)](https://github.com/iacker/brain-rag-server)
[![mcp-scalpel](https://github-readme-stats.vercel.app/api/pin/?username=iacker&repo=mcp-scalpel&border_color=76B900&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900)](https://github.com/iacker/mcp-scalpel)
[![Talos_Bastion_DevSecOps](https://github-readme-stats.vercel.app/api/pin/?username=iacker&repo=Talos_Bastion_DevSecOps&border_color=76B900&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900)](https://github.com/iacker/Talos_Bastion_DevSecOps)

</div>

| Projet | En bref |
|--------|---------|
| **[terraform-runpod-vllm](https://github.com/iacker/terraform-runpod-vllm)** | Un `terraform apply` → un GPU RunPod qui sert un LLM en API OpenAI. Budget guard, anti-doublon, teardown propre. |
| **[gpu-infra-lab](https://github.com/iacker/gpu-infra-lab)** | Lab SRE : vLLM sur k3s, observabilité DCGM, coût €/token et énergie **mesurés**, runbooks d'incidents vécus. |
| **[Nimbridge](https://github.com/iacker/Nimbridge)** | Inférence NVIDIA NIM en hybride : Kubernetes on-prem + GPU Azure, registry Harbor. |
| **[brain-rag-server](https://github.com/iacker/brain-rag-server)** | RAG local sur Obsidian via MCP — embeddings CPU, LanceDB + BM25, zéro cloud. |
| **[mcp-scalpel](https://github.com/iacker/mcp-scalpel)** | Proxy de filtrage sémantique pour le Docker MCP Gateway. Réduit les tokens de catalogue par tour. |
| **[Talos_Bastion_DevSecOps](https://github.com/iacker/Talos_Bastion_DevSecOps)** | Cluster Talos Linux GitOps : Cilium (eBPF), Traefik, ArgoCD, accès zéro-trust. |

---

## Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=iacker&show_icons=true&hide_border=true&count_private=true&bg_color=0D1117&title_color=76B900&text_color=CCCCCC&icon_color=76B900" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=iacker&layout=compact&hide_border=true&langs_count=8&bg_color=0D1117&title_color=76B900&text_color=CCCCCC" />

</div>

---

<div align="center">

<sub>`chaque commit est une cible` — mon graphe de contribution joué en space shooter, régénéré chaque jour</sub>

<img width="92%" src="https://raw.githubusercontent.com/iacker/iacker/main/game.gif" alt="Graphe de contribution en space shooter" />

</div>

---

## Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-76B900?style=for-the-badge&logo=linkedin&logoColor=black)](https://linkedin.com/in/erwan-billard)
[![Email](https://img.shields.io/badge/Email-76B900?style=for-the-badge&logo=protonmail&logoColor=black)](mailto:erwan.billard@protonmail.com)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:76B900,50:1a2e00,100:000000&height=110&section=footer" />

</div>
