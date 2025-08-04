# MirrorMariner

**⚓️ Sail your OCI artifacts straight to your local port!**

MirrorMariner seamlessly mirrors container images, Helm charts, and other OCI bundles from any cloud registry right into your own local registry—so you control where your artifacts live and how fast they arrive. 🌊🏠

---

## 🚀 What We’re Achieving

* **Local-First Delivery**
  Sync every image to your local registry for ultra-fast pulls and zero external dependencies.
* **Global Sources, Local Storage**
  Pull from ACR, ECR, GHCR, GCR, Harbor—or any OCI-compliant source—and deposit them safely on your own machine or cluster.
* **Dependency Resilience**
  Ensure every CI/CD job, developer laptop, or air-gapped environment has on-demand access to the exact artifacts it needs.

---

## ✨ Why You’ll Love It

* **Lightning-Fast Builds** ⚡
  Local mirrors eliminate internet latency—build and deploy in record time.
* **Offline-Ready Workflows** 🛠️
  Run tests and demos anywhere, even without cloud connectivity.
* **Total Control** 🔐
  Keep your images behind your firewall and apply your own security policies.
* **One-Click Sync** 🎯
  Trigger on-demand mirror jobs or schedule regular updates—no scripts, no hassles.

---

## 🌟 How It Works (At a Glance)

1. **Connect**
   Point MirrorMariner at your remote registry credentials.
2. **Configure**
   Specify which repos, tags, or charts to mirror—use inclusion/exclusion patterns to keep things tidy.
3. **Deploy**
   Install MirrorMariner into your Kubernetes cluster (or run standalone CLI).
4. **Enjoy**
   Watch artifacts flow into localhost (or your custom port) and power your pipelines instantly.

---

## ⚓️ Core Highlights

* **Multi-Registry Support** 🌐
  ACR · ECR · GHCR · GCR · Harbor · Private Registries
* **Declarative Sync Rules** 📜
  Mirror by repo, tag pattern, semantic version, branch tag—your choice.
* **Smart Scheduling** ⏰
  Cron-style jobs with retry/back-off logic for rock-solid reliability.
* **Secure Credentials** 🔑
  Integrate with Kubernetes Secrets, Vault, AWS Secrets Manager.
* **Metrics & Logs** 📈
  Prometheus-compatible metrics + detailed sync events for full visibility.

---

> Now just define your sync rules, and watch your artifacts land on Local! 🎉

---

## 🤝 Join the Fleet

We welcome feedback, ideas, and contributions!

* Open issues and PRs on GitHub
* Chat with us on Slack
* Star ⭐ the repo to stay updated

*MirrorMariner — your gateway from global registries to local port.* 🚢✨

