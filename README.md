# Welcome to MAG-COC 🎉

MAG-COC is more than just a GitHub account — it’s a governance-ready ecosystem built for community, clarity, and celebration.  
Every repo here is designed to empower contributors, ritualize delivery, and make milestones memorable.

---

## 🌌 Our Mission
We believe open-source should feel like a journey, not just a codebase.  
That’s why MAG-COC combines technical rigor with playful rituals:
- 🛡 Governance artifacts ensure compliance and traceability.
- 🏅 Contributors are recognized and celebrated in every merge.
- 📜 Milestones are logged in comic-strip style for teachable storytelling.
- 🎉 Delivery is treated as a community celebration, not just a deployment.

---

## 🚀 What You’ll Find Here
- **ClashComm-HOME** → Governance playbooks and audit logs  
- **Aggregated-COC-APIs** → Unified APIs for clan insights  
- **COC-Dashboard** → Task boards and stats dashboards  
- **CWL-Rosters** → Roster templates and lifecycle tracking  
- **Community-Noticeboard** → Announcements and events  
- **Community-Stats** → Analytics, war stats, CWL performance  

---

## 🎉 Our Culture
Contributors don’t just commit code — they join a ritual.  
Every issue, pull request, and merge is part of a lifecycle that celebrates progress, empowers stakeholders, and future-proofs the platform.

---

## 🌌 Our Governance Philosophy
- 🛡 Contribution rules → Ritualized and teachable
- 🏅 Contributor recognition → Every name celebrated
- 📜 Milestone logs → Comic-strip style CHANGELOGs
- ⚖️ Legal clarity → Apache 2.0 LICENSE + NOTICE attribution

---

## 📊 Repo Ecosystem
- 🌌 **ClashComm-HOME** → Governance playbooks, audit logs  
- 🔗 **Aggregated-COC-APIs** → Unified APIs for clan insights  
- 📊 **COC-Dashboard** → Task boards and stats dashboards  
- 🏆 **CWL-Rosters** → Roster templates and lifecycle tracking  
- 📣 **Community-Noticeboard** → Announcements and events  
- 📊 **Community-Stats** → Analytics, war stats, CWL performance  

---

## 🎉 Our Governance Lifecycle
- Contributions are celebrated with emoji legends.  
- Milestones are logged in comic‑strip style.  
- Governance artifacts ensure compliance and traceability.

```mermaid
flowchart TD
    A[Contributor] --> B[Open Issue]
    B --> C[Pull Request]
    C --> D[Governance Check]
    D --> E[CHANGELOG and Legends]
    E --> F[Update CONTRIBUTORS.md]
    F --> G[Build and Test with PHP Composer]
    G --> H[Deploy to Hostinger]
    H --> I[Celebratory Merge and Recognition]

    %% Assign classes
    class A,B,C contributor
    class D,E,F governance
    class G,H technical
    class I celebratory

    %% Define styles with black text
    classDef contributor fill:#f9f,color:#000,stroke:#333,stroke-width:2px;
    classDef governance fill:#bbf,color:#000,stroke:#333,stroke-width:2px;
    classDef technical fill:#bfb,color:#000,stroke:#333,stroke-width:2px;
    classDef celebratory fill:#ffb,color:#000,stroke:#333,stroke-width:2px;
```

---

## Repo Ecosystem Diagram

```mermaid
graph TD
    A[MAG-COC Hub] --> B[ClashComm-HOME]
    A --> C[Aggregated-COC-APIs]
    A --> D[COC-Dashboard]
    A --> E[CWL-Rosters]
    A --> F[Community-Noticeboard]
    A --> G[Community-Stats]

    %% Assign classes
    class B governance
    class C,D analytics
    class E,F,G community

    %% Define styles (high contrast for visibility)
    classDef governance fill:#4da6ff,color:#000,stroke:#333,stroke-width:2px;
    classDef analytics fill:#66cc66,color:#000,stroke:#333,stroke-width:2px;
    classDef community fill:#ffcc66,color:#000,stroke:#333,stroke-width:2px;
```

---

## Lifecycle + Repo Ecosystem Diagram

```mermaid
flowchart TD
    %% Governance Lifecycle
    A[Contributor] --> B[Open Issue]
    B --> C[Pull Request]
    C --> D[Governance Check]
    D --> E[CHANGELOG + Emoji Legends]
    E --> F[Update CONTRIBUTORS.md]
    F --> G[Build & Test PHP + Composer]
    G --> H[Deploy to Hostinger]
    H --> I[Celebratory Merge & Recognition]

    %% Repo Ecosystem
    I --> J[MAG-COC]
    J --> K[ClashComm-HOME]
    J --> L[Aggregated-COC-APIs]
    J --> M[COC-Dashboard]
    J --> N[CWL-Rosters]
    J --> O[Community-Noticeboard]
    J --> P[Community-Stats]

    %% Sub-nodes for clarity
    K --> K1[Governance Playbooks]
    K --> K2[Audit Logs]

    L --> L1[Clan APIs]
    L --> L2[Aggregated Insights]

    M --> M1[Task Boards]
    M --> M2[Stats Dashboards]

    N --> N1[Roster Templates]
    N --> N2[Lifecycle Tracking]

    O --> O1[Announcements]
    O --> O2[Events]

    P --> P1[Analytics]
    P --> P2[War Stats]
    P --> P3[CWL Performance]

    %% Explicit dependencies from Aggregated APIs
    L --> M
    L --> N
    L --> O
    L --> P

    %% Legend box
    subgraph Legend [Legend - Repo Categories]
        Lg1[Contributor]:::contributor
        Lg2[Governance]:::governance
        Lg3[Analytics]:::technical
        Lg4[Community]:::celebratory
    end

    %% Assign classes
    class A,B,C contributor
    class D,E,F governance
    class G,H technical
    class I celebratory

    %% Repo ecosystem classes
    class J,K,K1,K2 governance
    class L,L1,L2 technical
    class M,M1,M2 technical
    class N,N1,N2 celebratory
    class O,O1,O2 celebratory
    class P,P1,P2,P3 celebratory

    %% Define styles with black text
    classDef contributor fill:#f9f,color:#000,stroke:#333,stroke-width:2px;
    classDef governance fill:#bbf,color:#000,stroke:#333,stroke-width:2px;
    classDef technical fill:#bfb,color:#000,stroke:#333,stroke-width:2px;
    classDef celebratory fill:#ffb,color:#000,stroke:#333,stroke-width:2px;

```

---

## 📝 Contributor Quick‑Guide

Welcome to the project! This guide explains how contributions flow through governance, analytics, and community repos.

### Governance + Repo Ecosystem Flow
- Contributors begin by opening issues and submitting pull requests.
- Governance ensures compliance through checks, changelogs, and contributor updates.
- Technical repos handle builds, tests, and deployments.
- Celebratory milestones recognize merges and community achievements.
- Aggregated‑COC‑APIs act as the backbone service, feeding data into:
  - Analytics repos (green) → dashboards and insights.
  - Community repos (gold) → rosters, noticeboards, stats.
- Governance repos (blue) anchor the ecosystem with lifecycle tracking and playbooks.

### 📝 Contributor Onboarding Checklist
1. **Open an Issue** → Document bugs, features, or improvements clearly.  
2. **Submit a Pull Request** → Link PRs to issues and follow coding standards.  
3. **Governance Check** → Ensure CHANGELOG + emoji legends are updated.  
4. **Update Contributors** → Add yourself to `CONTRIBUTORS.md`.  
5. **Build & Test** → Run PHP + Composer builds and validate tests.  
6. **Deploy** → Push changes to Hostinger and confirm logs.  
7. **Merge & Celebrate** → Governance approves → PR merged → recognition milestone logged.  
8. **Repo Ecosystem Integration** → Your contribution flows into governance, analytics, and community repos via Aggregated APIs.  

---

## 🔹 Style Choices
- **Governance repos (blue)** → ClashComm‑HOME  
- **Analytics repos (green)** → APIs + Dashboard  
- **Community repos (gold)** → Rosters, Noticeboard, Stats  
- **Black text (`color:#000`)** → Ensures labels are always readable against bright fills.  
- **Dark stroke (`stroke:#333`)** → Keeps node outlines clear.  

---

## Emoji Legend Table
| Emoji | Meaning                  |
|-------|--------------------------|
| ✅    | Completed task           |
| 📊    | Stats update             |
| 🏆    | CWL milestone            |
| 📣    | Announcement             |
| 🛡    | Governance ritual        |
| 🎉    | Celebratory merge        |

---

## 📘 Governance Suite
- [CONTRIBUTORS.md](CONTRIBUTORS.md) → Celebrates every contributor
- [CHANGELOG.md](CHANGELOG.md) → Comic‑strip style milestone logs
- [LICENSE.md](LICENSE.md) → Apache 2.0 legal clarity
- [NOTICE](NOTICE) → Attribution + celebratory recognition
- 📘 Contributor Rituals → See [MAG‑COC/docs/Contributor-Rituals.md](../MAG-COC/docs/Contributor-Rituals.md)

