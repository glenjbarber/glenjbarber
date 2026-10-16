# Glen Barber

Release Engineering Leader | Platform Engineering | Infrastructure Automation | Release Governance

I make complex systems more reliable, and releases more predictable.

Find me on [Every Expert](https://www.facebook.com/ApiaryVE/posts/pfbid02u46PkBLr9ja7jDfu8hEVgmPkVh6cdcJfkqdZLpvkmBMx7jmtx5gcyFyFkP4zKEkFl)

I am a release engineering and infrastructure leader with 17 years across Unix platform operations, including 9 years owning FreeBSD release engineering.
While employed at The FreeBSD Foundation and later at Netgate, I served as FreeBSD Project Release Engineering Team Lead from March 2014 through November 2023, closing with 14.0-RELEASE.
Across that decade I delivered 22 production releases: 9 while at Netgate, spanning three simultaneously supported major branches from 11.3 in 2019 through 13.2 in 2023, and 12 while at the Foundation, from 8.4 through 12.0.
The work meant owning release governance, change control, build and artifact pipelines, and public communication, and it required turning ambiguity into repeatable, accountable process.

## Areas of focus

- Release engineering and release governance
- Platform reliability and reproducible builds
- Change management and incident response
- Build and release automation, CI/CD architecture
- Unix/Linux and FreeBSD systems, ZFS, jails
- Infrastructure as code and configuration management
- Risk assessment and go/no-go decision frameworks
- Technical documentation, mentorship, and succession planning

## Selected background

- Software Release Engineer, Netgate, 2019-2023, continuing as FreeBSD Project Release Engineering Team Lead under employer-allocated time, a provision written into the job description at hire
- Systems Administrator, The FreeBSD Foundation, 2013-2019, becoming FreeBSD Project Release Engineering Team Lead in March 2014
- Delivered 22 production releases across the two roles: 9 at Netgate (11.3 through 13.2, across three simultaneously supported major branches) and 12 at the Foundation (8.4 through 12.0)
- Carried release engineering through the project's Subversion to Git migration in December 2020, converting the release automation and branching, tagging, and change-approval workflows to Git without interrupting the release cadence; 13.0 was the first major release produced from the Git repository
- Developed two deputy leads over nearly a decade and executed a planned handover, formally acknowledged by the project's governing body
- FreeBSD Project Committer, September 2010-December 2023, with full commit access across Source, Ports, and Documentation
- 6,600+ commits and 2,600+ change approvals granted to other developers across Source, Ports, and Documentation ([commit history](https://github.com/freebsd/freebsd-src/commits?author=glenjbarber))
- Also served on the Documentation Engineering, Security, and Cluster Administration Teams
- Independent contract engagement (Jan-Apr 2024): built an IoT device monitoring proof of concept for a connected-device manufacturer on Google Compute Engine, FreeBSD 14, service isolation via jails, Zabbix backed by PostgreSQL/TimescaleDB, and a Python integration for device telemetry, delivered with full documentation inside a fixed budget

## Projects

- **[Apiary](https://github.com/glenjbarber/apiary)** (2026-present) — a FreeBSD-native virtualization management platform for cluster management, VM and container orchestration, and storage replication.
  Go across the stack, built around bhyve and jails, with a dedicated raft-based consensus agent, ZFS and HAST-backed replication, and an HTMX web frontend with a live browser console into each VM.
  Active development against real FreeBSD hardware: raft consensus, node management, VM and jail lifecycle, and cross-node console tunnelling and failover all working end to end.
- **[Thermite](https://thermite.sh)** (2013-2023) — the FreeBSD release build automation, published standalone.
  Configuration-driven build matrix engine handling isolated release builds, artifact staging, checksum reporting, and cloud image publication.
- **[mailtools](https://github.com/glenjbarber/mailtools)** (2026) — utilities for large-scale Maildir migration and integrity verification.
  Applied to a 26-year, 2.34-million-message archive: per-month foldering, timestamp reconstruction from message headers, and a manifest-driven apply, verify, and rollback workflow.

## What I am looking for

I am interested in senior release engineering, platform engineering, and technical operations roles where ownership, reliability, and reproducibility are the job, not a side effect of it.

## Contact

- LinkedIn: <https://www.linkedin.com/in/glenjbarber>
