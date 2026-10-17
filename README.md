# Glen Barber

**Release Engineering | Platform Engineering | Distributed Systems | Build Infrastructure**

I build and operate complex systems, make software delivery more predictable, and work to eliminate the failure modes that make infrastructure difficult to trust.

I have 17 years of Unix and infrastructure engineering experience, including nearly a decade as the FreeBSD Project Release Engineering Team Lead (2014-2023). My work has spanned multi-architecture build infrastructure, operating system releases, package creation, cloud image delivery, security-sensitive release coordination, and technical leadership across distributed contributors.

Today, I am building Go-based infrastructure and developer tooling, with particular interest in distributed systems, reliability engineering, and practical, accountable use of AI coding agents.

## Current projects

### [Apiary](https://github.com/glenjbarber/apiary)

A FreeBSD-native virtualization and cluster management platform, under active development. Apiary coordinates bhyve virtual machines and FreeBSD jails using Go services, a dedicated Raft consensus process, gRPC APIs, and an HTMX-based interface. It integrates ZFS-backed provisioning, HAST replication, cluster health reporting, recovery controls, and Kubernetes-oriented infrastructure.

The project is developed and tested against real FreeBSD systems. Its architecture and implementation trade-offs are recorded in [architecture decision records](https://github.com/glenjbarber/apiary/tree/main/docs/adr).

### [orcli](https://github.com/glenjbarber/orcli)

A pre-release, full-screen terminal client for AI-assisted engineering. Written in Go, orcli supports the OpenRouter and Liquid Console inference APIs, persistent SQLite sessions, permission-controlled filesystem/git/shell tools, and integrations including MCP, GitHub, Notion, and Apiary.

The design emphasizes explicit trust boundaries, controlled tool execution, testable behavior, and transparency about incomplete functionality. It is a working pre-release project, not a finished product.

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

I am interested in Principal, Staff, and senior individual-contributor roles in platform engineering, release engineering, build infrastructure, distributed systems, and infrastructure reliability. I am particularly drawn to teams where architectural judgment, operational accountability, and hands-on engineering belong together.

## Connect

- [LinkedIn](https://www.linkedin.com/in/glenjbarber)
- [GitHub repositories](https://github.com/glenjbarber)
- [Book a consultation on Every Expert](https://www.everyexpert.com/glenjbarber)
