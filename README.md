<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=200&text=UJJWAL&fontSize=80&color=0:00FFD1,50:7B2FBE,100:FF003C&fontColor=fff&stroke=00FFD1&strokeWidth=2&animation=fadeIn&desc=DevOps%20Engineer%20%7C%20SRE%20%7C%20Cloud%20Native%20Architect&descSize=18&descAlignY=75" />

<a href="https://github.com/uxzwal"><img src="https://img.shields.io/badge/GitHub-Ujjwal-00FFD1?style=for-the-badge&logo=github&logoColor=00FFD1&labelColor=0D0D0D" /></a>
<a href="https://linkedin.com/in/uxzwal"><img src="https://img.shields.io/badge/LinkedIn-Ujjwal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=00FFD1&labelColor=0D0D0D" /></a>
<a href="https://uzwal.netlify.app"><img src="https://img.shields.io/badge/Portfolio-FF003C?style=for-the-badge&logo=vercel&logoColor=FF003C&labelColor=0D0D0D" /></a>
<a href="https://t.me/uxzwal"><img src="https://img.shields.io/badge/Telegram-uxzwal-26A5E4?style=for-the-badge&logo=telegram&logoColor=26A5E4&labelColor=0D0D0D" /></a>
<a href="mailto:iamkashyup@gmail.com"><img src="https://img.shields.io/badge/Email-iamkashyup-EA4335?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=0D0D0D" /></a>

<br/><br/>

<img src="https://img.shields.io/badge/STATUS-OPERATIONAL-00FFD1?style=flat-square&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/UPTIME-99.99%25-00FFD1?style=flat-square&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/DORA-ELITE_TIER-7B2FBE?style=flat-square&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/IaC-100%25_COVERAGE-FF003C?style=flat-square&labelColor=0D0D0D" />
<img src="https://komarev.com/ghpvc/?username=uxzwal&label=RECON+HITS&style=flat-square&color=00FFD1&labelColor=0D0D0D" />

</div>

---
<img align="right" width="380" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" />


```bash
┌──────────────────────────────────────┐
│  ssh U
jjwal@devops.nexus           │
├──────────────────────────────────────┤
│  > whoami                            │
│  Ujjwal — Lead DevOps Engineer       │
│  Cloud Native Architect · SRE        │
│                                      │
│  > uptime                            │
│  247d 0h — 0 unplanned outages       │
│                                      │
│  > echo $LOCATION                    │
│  India                               │
│                                      │
│  > echo $PHILOSOPHY                  │
│  automate · measure · never drift    │
│                                      │
│  > systemctl is-active production    │
│  active ✓                            │
└──────────────────────────────────────┘
```

<br clear="right"/>

---

<div align="center">

## ⚡ GITOPS SIGNAL FLOW

```mermaid
%%{init:{'theme':'dark','themeVariables':{'primaryColor':'#00FFD1','primaryTextColor':'#000','primaryBorderColor':'#00FFD1','lineColor':'#7B2FBE','background':'#0D0D0D','edgeLabelBackground':'#0D0D0D','fontFamily':'JetBrains Mono'}}}%%
flowchart LR
  A([👨‍💻 git push])-->|webhook|B([⚡ GitHub Actions])
  B-->|docker build|C([🐳 Registry])
  C-->|scan|D{🔒 Trivy}
  D-->|PASS|E([✍️ Cosign])
  D-->|FAIL|X([🚫 Blocked])
  E-->|sync|F([🚢 ArgoCD])
  F-->|deploy|G([☸️ K8s])
  G-->|scrape|H([📊 Prometheus])
  H-->|SLO breach|I([🔄 Auto Rollback])
  I-->|revert|F
```

</div>

---

## 🛸 TECH STACK

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,azure,gcp,cloudflare,kubernetes,docker,helm,terraform,ansible,githubactions,git,python,go,rust,bash,grafana,prometheus,linux,vim,vscode&theme=dark&perline=10" />

<br/><br/>

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=000)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![Linkerd](https://img.shields.io/badge/Linkerd-2BEDA7?style=flat-square&logo=linkerd&logoColor=000)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Crossplane](https://img.shields.io/badge/Crossplane-EF3B2D?style=flat-square&logo=crossplane&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Tekton](https://img.shields.io/badge/Tekton-FD495C?style=flat-square&logo=tekton&logoColor=white)
![FluxCD](https://img.shields.io/badge/FluxCD-5468FF?style=flat-square&logo=flux&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46817?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000?style=flat-square&logo=opentelemetry&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A623?style=flat-square&logo=grafana&logoColor=000)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=000)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)
![OPA](https://img.shields.io/badge/OPA-7D3C98?style=flat-square&logo=openpolicyagent&logoColor=white)
![Falco](https://img.shields.io/badge/Falco-00A86B?style=flat-square)
![Cosign](https://img.shields.io/badge/Cosign-1A73E8?style=flat-square&logo=sigstore&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-CE4A00?style=flat-square&logo=rust&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</div>

---

## 🧬 DORA METRICS

<div align="center">

| METRIC | VALUE | TREND | THRESHOLD | STATUS |
|:--|:--:|:--:|:--:|:--:|
| 🚀 Deploy Frequency | **47 / day** | ▲ +12% | > 30/day | ✅ ELITE |
| ⏱️ Lead Time | **23 min** | ▼ faster | < 1 hour | ✅ ELITE |
| 🔄 MTTR | **12 min** | ▼ faster | < 1 hour | ✅ ELITE |
| 💥 Change Failure Rate | **0.8%** | ▼ lower | < 15% | ✅ ELITE |
| 🟢 Error Budget | **99.2%** remaining | stable | > 95% | ✅ ELITE |

<br/>

<img src="https://img.shields.io/badge/🚀_Deploy-47%2Fday_▲12%25-00FFD1?style=for-the-badge&labelColor=0A0A0A" />
<img src="https://img.shields.io/badge/⏱️_Lead_Time-23_min_▼-7B2FBE?style=for-the-badge&labelColor=0A0A0A" />
<img src="https://img.shields.io/badge/🔄_MTTR-12_min_▼-FF003C?style=for-the-badge&labelColor=0A0A0A" />
<img src="https://img.shields.io/badge/💥_CFR-0.8%25_▼-FF9900?style=for-the-badge&labelColor=0A0A0A" />

</div>

---

## 📡 PRODUCTION RADAR

```json
{
  "operator"           : "Ujjwal",
  "cluster_health"     : "🟢 GREEN",
  "clusters"           : ["eks-prod-us-east-1", "aks-prod-eu-west", "gke-stg-asia"],
  "avg_latency_p99"    : "187ms",
  "error_budget_burn"  : "0.8%",
  "next_k8s_upgrade"   : "1.32 → 1.33",
  "incident_status"    : "✅ NONE",
  "chaos_experiments"  : "every Tuesday 02:00 UTC",
  "last_rollback"      : "none in 247 days",
  "iac_coverage"       : "100%",
  "last_manual_change" : null
}
```

---

## 🔮 CURRENT FOCUS

<div align="center">

<img src="https://img.shields.io/badge/🎯_SHIPPING-Platform_Engineering_IDP-FF003C?style=for-the-badge&labelColor=0A0A0A" />
<img src="https://img.shields.io/badge/🏗️_BUILDING-Internal_Developer_Portal-7B2FBE?style=for-the-badge&labelColor=0A0A0A" />
<br/>
<img src="https://img.shields.io/badge/🔄_SCALING-GitOps_at_Enterprise_Scale-00FFD1?style=for-the-badge&labelColor=0A0A0A" />
<img src="https://img.shields.io/badge/🧠_LEARNING-eBPF_+_Cilium_+_Tetragon-FF9900?style=for-the-badge&labelColor=0A0A0A" />
<br/>
<img src="https://img.shields.io/badge/🔬_EXPLORING-WASM_+_OPA_Policy_Mesh-38BDF8?style=for-the-badge&labelColor=0A0A0A" />
<img src="https://img.shields.io/badge/🎓_ALWAYS-Learning_&_Building-4EAA25?style=for-the-badge&labelColor=0A0A0A" />

</div>

---

## 📈 GITHUB COSMOS

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=uxzwal&show_icons=true&count_private=true&hide_border=true&bg_color=0D0D0D&title_color=00FFD1&icon_color=7B2FBE&text_color=8B949E&ring_color=00FFD1&include_all_commits=true" />
<img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=uxzwal&hide_border=true&background=FFFADA&stroke=00FFD1&ring=7B2FBE&fire=FF003C&currStreakLabel=000000&sideLabels=8B949E&dates=555555" />

<br/>

<img width="94%" src="https://github-readme-activity-graph.vercel.app/graph?username=uxzwal&theme=github-dark&bg_color=0D0D0D&hide_border=true&area=true&area_color=7B2FBE&point=00FFD1&line=00FFD1&color=8B949E" />

## 🎖️ MANIFESTO

```
╔══════════════════════════════════════════════════════════╗
║  /etc/devops/manifesto.conf                             ║
╠══════════════════════════════════════════════════════════╣
║  [IaC]         100% coverage. zero manual drift. ever.  ║
║  [ROLLBACK]    < 60s automated. on any SLO breach.      ║
║  [SECURITY]    shift-left. scan every commit. sign.     ║
║  [POSTMORTEM]  blameless. learn. automate. never again. ║
║  [CHAOS]       untested = not production-ready.         ║
║  [TOIL]        do it twice? automate it on the third.   ║
║  [SLO]         user happiness is the only real SLI.     ║
╚══════════════════════════════════════════════════════════╝
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:00FFD1,50:7B2FBE,100:FF003C&section=footer" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=13&duration=2500&pause=600&color=00FFD1&center=true&vCenter=true&width=750&height=28&lines=build+→+scan+→+sign+→+deploy+→+observe+→+rollback+→+repeat;if+it%27s+not+in+git%2C+it+does+not+exist;automation+is+the+only+sustainable+scaling+strategy" />

<br/>

<img src="https://img.shields.io/badge/made_with-☸️_kubernetes-326CE5?style=flat-square&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/powered_by-🔮_terraform-7B42BC?style=flat-square&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/observed_by-📡_prometheus-E6522C?style=flat-square&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/deployed_via-⚡_argocd-EF7B4D?style=flat-square&labelColor=0D0D0D" />

<br/><br/>

<sub>🟢 infrastructure operational · profile auto-regenerated on every visit</sub>

</div>
