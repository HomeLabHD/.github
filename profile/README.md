<div align="center">

<p>
  <img src="../assets/HomeLabHD-Logo-Captioned.png" width="320" alt="HomeLabHD">
</p>
<p>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=520&lines=HomeLab+Helpdesk;Images+%E2%80%A2+Guides+%E2%80%A2+CI+Components;Built+for+Homelabbers%2C+by+Homelabbers" alt="Typing SVG" />
</p>

[![PrPlanIT GitHub](https://img.shields.io/badge/PrPlanIT-181717?style=flat&logo=github&logoColor=white)](https://github.com/PrPlanIT)
[![HomeLabHD GitHub](https://img.shields.io/badge/HomeLabHD-181717?style=flat&logo=github&logoColor=white)](https://github.com/HomeLabHD)
[![PrPlanIT GitLab](https://img.shields.io/badge/PrPlanIT-FC6D26?style=flat&logo=gitlab&logoColor=white)](https://gitlab.prplanit.com/PrPlanIT)
[![HomeLabHD GitLab](https://img.shields.io/badge/HomeLabHD-FC6D26?style=flat&logo=gitlab&logoColor=white)](https://gitlab.prplanit.com/PrPlanIT/HomeLabHD)
[![prplanit Docker](https://img.shields.io/badge/prplanit-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/prplanit)
[![hlhd Docker](https://img.shields.io/badge/hlhd-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/hlhd)
[![donate](https://img.shields.io/badge/donate-FF5E5B?style=flat&logo=ko-fi&logoColor=white)](https://ko-fi.com/sofmeright)
[![sponsor](https://img.shields.io/badge/sponsor-EA4AAA?style=flat&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/PrPlanIT)

</div>

---

## What is HomeLabHD?

**HomeLabHD** (HomeLab Helpdesk) is a child organization of [PrPlanIT](https://github.com/PrPlanIT) — a collection of container images, guides, GitLab CI components, and other materials useful in homelab and production environments.

Our reasons for maintaining these projects vary: sometimes we can't find an image from a maintainer we trust, sometimes we need additional features or tooling baked in, and sometimes it's pure preference. Not everything here is a container image — you'll also find disaster recovery guides, CI components, and other resources we've found worth sharing.

Everything is freely available. We consume these internally and make a best effort to keep things current. Some projects may go stale between releases — we're actively building tooling ([StageFreight](https://github.com/PrPlanIT/StageFreight)) to automate dependency freshness, security scanning, and release workflows across the catalog. If you find something out of date, open an issue.

All container images are built with [StageFreight](https://github.com/PrPlanIT/StageFreight) on GitLab CI with automated vulnerability scanning (Trivy + Grype), SBOM generation, and release notes. Source is mirrored to GitHub, images published to [Docker Hub](https://hub.docker.com/u/hlhd).

---

## Featured Projects

<table>
<tr>
<td width="50%">

#### [ansible](https://github.com/HomeLabHD/ansible)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
[![Docker Pulls](https://img.shields.io/docker/pulls/hlhd/ansible)](https://hub.docker.com/r/hlhd/ansible)

Lightweight Alpine-based Ansible image with ansible-core, ansible-lint, WinRM support, SOPS, and community collections preinstalled. Built for CI playbook execution and local automation.

</td>
<td width="50%">

#### [apt-cacher-ng](https://github.com/HomeLabHD/apt-cacher-ng)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
[![Docker Pulls](https://img.shields.io/docker/pulls/hlhd/apt-cacher-ng)](https://hub.docker.com/r/hlhd/apt-cacher-ng)

APT caching proxy for Debian/Ubuntu package repositories. Reduces bandwidth and speeds up installs across your lab.

</td>
</tr>
<tr>
<td width="50%">

#### [nginx-extras](https://github.com/HomeLabHD/nginx-extras)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
[![Docker Pulls](https://img.shields.io/docker/pulls/hlhd/nginx-extras)](https://hub.docker.com/r/hlhd/nginx-extras)

Nginx with extras module compiled in — for when the official image doesn't ship the modules you need.

</td>
<td width="50%">

#### [PVE_Ceph-Disaster_Recovery](https://github.com/HomeLabHD/PVE_Ceph-Disaster_Recovery)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
[![Stars](https://img.shields.io/github/stars/HomeLabHD/PVE_Ceph-Disaster_Recovery?style=social)](https://github.com/HomeLabHD/PVE_Ceph-Disaster_Recovery)

Shell-based Ceph monitor store recovery for Proxmox clusters that have lost all monitors. Battle-tested on production clusters.

</td>
</tr>
</table>

Browse [Docker Hub](https://hub.docker.com/u/hlhd) or [GitHub](https://github.com/HomeLabHD) for the full list.

---

## Contributing

- Fork any repository and submit a Pull Request / Merge Request
- Open issues with ideas, bugs, or feature requests
- Suggest new projects you'd like to see in the catalog

---

## Disclaimer

Everything here is provided "as-is" without warranties of any kind. We run it all in our own infrastructure, but your mileage may vary. Not responsible if your homelab becomes so reliable you forget how to troubleshoot.

---

## License

Most projects are distributed under the **GPL-3.0** License. See each repository for specific licensing details.
