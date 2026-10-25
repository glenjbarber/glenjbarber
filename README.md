# Glen Barber

**Release Engineering | Platform Engineering | Distributed Systems | Build Infrastructure**

I build infrastructure software with reliability, recovery, and operational consequences in mind. My current work in Go and FreeBSD brings together virtualization, distributed coordination, storage, and developer tooling.

That approach comes from nearly a decade leading FreeBSD production release engineering. Release leadership meant deciding what needed to change, which risks justified a delay, and when software was actually ready to ship. I created release automation, coordinated contributors across major branches, and remained accountable for the resulting artifacts.

Before that, I built and operated the Unix infrastructure behind software delivery. Seventeen years of hands-on systems work taught me to recognize failure modes, not just implement fixes. I bring those layers together today: identify the problem that matters, make a defensible technical decision, and build something repeatable and recoverable.

## Current projects

### [Apiary](https://github.com/glenjbarber/apiary)

A FreeBSD-native virtualization and cluster management platform, under active development. Apiary coordinates bhyve virtual machines and FreeBSD jails using Go services, a dedicated Raft consensus process, gRPC APIs, and an HTMX-based interface. It integrates ZFS-backed provisioning, HAST replication, cluster health reporting, recovery controls, and Kubernetes-oriented infrastructure.

The project is developed and tested against real FreeBSD systems. Its architecture and implementation trade-offs are recorded in [architecture decision records](https://github.com/glenjbarber/apiary/tree/main/docs/adr).

### [orcli](https://github.com/glenjbarber/orcli)

A pre-release, full-screen terminal client for AI-assisted engineering. Written in Go, orcli supports the OpenRouter and Liquid Console inference APIs, persistent SQLite sessions, permission-controlled filesystem/git/shell tools, and integrations including MCP, GitHub, Notion, and Apiary.

The design emphasizes explicit trust boundaries, controlled tool execution, testable behavior, and transparency about incomplete functionality. It is a working pre-release project, not a finished product.

### [openrouter-cli](https://github.com/glenjbarber/openrouter-cli)

An enhanced command-line interface for the OpenRouter AI platform, with argument completion, notmuch integration for email search, and improved shell allowlist management. It includes a posArgument completion type and a WithArguments method for merging argument sets.

### [Thermite](https://thermite.sh)

The open-source FreeBSD release automation framework I designed and maintained. Thermite uses configuration-driven, isolated, ZFS-backed build environments for multi-architecture release builds, artifact staging, checksums, and cloud image publication.

## Engineering focus

- **Build and release systems:** reproducible builds, CI/CD architecture, release governance, package infrastructure, artifact distribution, and delivery pipelines.
- **Distributed infrastructure:** Go, gRPC/Protocol Buffers, Raft, ZFS, HAST, bhyve, FreeBSD jails, and operational recovery.
- **Reliability and security:** failure analysis, incident response, observability, change control, risk assessment, and security-sensitive delivery.
- **Engineering leadership:** architectural decision-making, technical documentation, mentoring, roadmap trade-offs, and coordination without direct authority.
- **AI-assisted development:** agentic coding workflows, tool permissions, integration design, and practical verification of generated changes.

## FreeBSD and open source

I served as a [FreeBSD Project Committer](https://github.com/freebsd) from September 2010 through December 2023, with contributions across Source, Ports, and Documentation. I led Release Engineering from March 2014 through November 2023, concluding with 14.0-RELEASE.

My FreeBSD work included:

- Coordinating production releases across simultaneously supported major branches and distributed contributors.
- Designing release automation and maintaining build and artifact delivery infrastructure.
- Adapting release engineering processes during the project's Subversion-to-Git migration without interrupting the release cadence.
- Coordinating security-sensitive release work, change approvals, and high-impact release decisions.
- Mentoring deputy leads and completing a planned leadership transition.
- Contributing to the Documentation Engineering, Security, and Cluster Administration Teams.

My project history includes more than 6,600 commits and 2,600 change approvals across FreeBSD Source, Ports, and Documentation. The underlying work is publicly traceable through FreeBSD repositories and project records.

## What I am looking for

I am interested in Staff, Principal, and senior engineering roles spanning release engineering, platform infrastructure, build systems, distributed systems, and reliability. I do my best work where technical judgment and hands-on implementation are inseparable: defining the right problem, understanding the operational risk, and following through on delivery.

## Connect

- [LinkedIn](https://www.linkedin.com/in/glenjbarber)
- [GitHub repositories](https://github.com/glenjbarber)
- [Book a consultation on Every Expert](https://www.everyexpert.com/glenjbarber)
