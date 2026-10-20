# Hi, I'm Filip

**Cybersecurity Specialist, Secure SDLC** · DevSecOps · Vulnerability Management · Cloud Security (GCP) · IAM

I help product teams ship secure software, from the first commit to the cloud it runs on. Day to day I triage vulnerabilities in containers and dependencies, review GitLab CI/CD pipelines, check GCP configuration and IAM, and turn findings into fixes developers can actually act on.

This GitHub is where I build the tooling behind that work, in the open and often with Claude as a pair-programmer.

---

### What I work on

- **Vulnerability management**: triaging container and dependency findings across several product teams, separating real risk from noise, tracking fixes to closure
- **Pipeline security**: secrets, SAST, dependency and image scanning, SBOMs and quality gates in GitLab CI
- **Cloud security (GCP)**: configuration and IAM reviews, least privilege, who has access to what
- **Security communication**: turning CVEs and scan results into clear, prioritised tickets and briefs for engineering teams

### Currently building

| Project | What it does | Status |
|---|---|---|
| `vuln-triage` | CLI that takes Trivy, Grype or Xray JSON, enriches each CVE with **EPSS** and **CISA KEV**, and outputs a prioritised report with the reason behind every priority. Optional Claude-written summary for the dev team | Coming soon |
| `gitlab-ci-security` | Reusable GitLab CI templates: gitleaks, Semgrep, Trivy, Syft SBOM and a priority gate powered by `vuln-triage` | Coming soon |
| `claude-security-skills` | Claude Skills for AppSec work: CVE briefs for dev teams, CI pipeline security review, remediation ticket drafting | Coming soon |

### Toolbox

**Security:** Trivy · Grype · Semgrep · gitleaks · Syft · OWASP Top 10 · threat modelling  
**Platforms:** GitLab CI/CD · Google Cloud · Docker · Linux  
**Code:** Python · Bash · YAML · SQL  
**AI:** Claude (Claude Code, Skills, MCP) for security automation and review

### Background

- BSc Computer Science (First Class), Queen Mary University of London: where cryptography and TryHackMe got me into security
- Identity & Access Management in banking: 100+ access requests a week, Segregation of Duties conflicts, Python automations for access data
- TryHackMe **Jr Penetration Tester** certificate

### Learning right now

- Google Cloud **Associate Cloud Engineer**, first step towards cloud security engineering
- Prioritising vulnerabilities beyond CVSS: EPSS, KEV, reachability
- Software supply-chain security: SBOMs, SLSA, artifact signing

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/filip-szumotalski/) · happy to talk cloud security, DevSecOps and AppSec

<sub>Code and opinions here are my own. No employer code or data.</sub>
