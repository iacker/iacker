<!--
  README profil GitHub — iacker (Erwan Billard)
  Thème : dégradé violet #7C3AED → cyan #22D3EE sur fond #0D1117
  Libs : capsule-render · readme-typing-svg · skillicons.dev · shields.io
-->

<div align="center">

<img width="44%" src="./assets/wordmark.png" alt="iacker" />

<br/>

**AI Infrastructure Engineer**

<img src="./assets/tagline.svg" alt="GPU serving · vLLM · Kubernetes · IaC · FinOps GPU · Observabilité · Agents · MCP · RAG local" width="620" />

<img src="https://komarev.com/ghpvc/?username=iacker&label=Vues&color=7C3AED&style=flat-square" alt="vues" />
<img src="https://img.shields.io/github/followers/iacker?label=Followers&style=flat-square&color=7C3AED&labelColor=0D1117" alt="followers" />

</div>

<br/>

## Ce que je fais

Je fais tourner des LLM sur GPU en production, et je maîtrise le coût, la latence et l'énergie qui vont avec. Mon terrain, c'est la couche entre le modèle et le hardware : provisionner le GPU, servir le modèle, l'observer, le rendre **rentable**.

- **`GPU / LLM serving`** : vLLM, quantization FP16/FP8, RunPod et bare metal, dimensionnement, DCGM
- **`Kubernetes / Platform`** : k3s, Talos, Helm, GitOps (Flux, Argo), Kueue, autoscaling, hybride sur site et cloud
- **`IaC et FinOps`** : Terraform, coût €/token et énergie mesurés, budget guards, teardown propre
- **`Agents et tooling`** : MCP, RAG local, orchestration multi agents
- **`Sécurité`** : DevSecOps, eBPF/NDR, supply chain, hardening

<div align="center">

[![Skills](https://skillicons.dev/icons?i=kubernetes,docker,terraform,pytorch,python,go,aws,azure,gcp,nix,linux,grafana,prometheus,bash&perline=14&theme=dark)](https://skillicons.dev)

</div>

<br/>

## Projets

> La couche complète : provisionner, servir, opérer puis optimiser un LLM sur GPU.

| Projet | En bref |
|--------|---------|
| **[terraform-runpod-vllm](https://github.com/iacker/terraform-runpod-vllm)** | Un `terraform apply`, et un GPU RunPod sert un LLM en API OpenAI. Budget guard, anti doublon, teardown propre. |
| **[gpu-infra-lab](https://github.com/iacker/gpu-infra-lab)** | Lab SRE : vLLM sur k3s, observabilité DCGM, coût €/token et énergie **mesurés**, runbooks d'incidents vécus. |
| **[Nimbridge](https://github.com/iacker/Nimbridge)** | Inférence NVIDIA NIM en hybride : Kubernetes sur site plus GPU Azure, registry Harbor. |
| **[brain-rag-server](https://github.com/iacker/brain-rag-server)** | RAG local sur Obsidian via MCP : embeddings CPU, LanceDB plus BM25, zéro cloud. |
| **[mcp-scalpel](https://github.com/iacker/mcp-scalpel)** | Proxy de filtrage sémantique pour le Docker MCP Gateway. Réduit les tokens de catalogue par tour. |
| **[Talos_Bastion_DevSecOps](https://github.com/iacker/Talos_Bastion_DevSecOps)** | Cluster Talos Linux GitOps : Cilium (eBPF), Traefik, ArgoCD, accès zéro trust. |

<br/>

<div align="center">

<sub>`chaque commit est une cible` : mon graphe de contribution joué en space shooter, régénéré chaque jour</sub>

<img width="90%" src="https://raw.githubusercontent.com/iacker/iacker/main/game.gif" alt="Graphe de contribution en space shooter" />

</div>

<br/>

## Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/erwan-billard)
[![Email](https://img.shields.io/badge/Email-22D3EE?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:erwan.billard@protonmail.com)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,100:7C3AED&height=110&section=footer" />

</div>
