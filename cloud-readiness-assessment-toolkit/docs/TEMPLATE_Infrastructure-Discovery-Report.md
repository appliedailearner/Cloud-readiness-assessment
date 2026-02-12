# [CLIENT NAME] - Infrastructure Discovery Report
<!-- 
INSTRUCTION: 
This report is the technical foundation of the assessment. 
Summarize tool outputs (e.g., Azure Migrate, RVTools, CloudHealth).
-->

## 1. Executive Summary
Overview of the current scanned environment and utilization trends.

## 2. Inventory Summary
- **In-Scope VM Count:** [NUMBER]
- **Storage Profile:** [TB] (Block vs Object)
- **Network Scopes:** [NUMBER OF SEGMENTS]

## 3. Efficiency & "Zombie" Server Analysis
- **Zombie Servers identified:** [COUNT] (Servers with <1% CPU/IO for 30 days)
- **Potential Decommissioning Savings:** [ESTIMATED %]

## 4. Modernization Candidates (IaaS to PaaS)
<!-- 
Identifying workloads that can skip "Lift & Shift" to reduce TCO.
-->
- **SQL / Database Candidates:** [COUNT] (Target: Azure SQL MI / AWS RDS)
- **Web/App Tier Candidates:** [COUNT] (Target: App Service / Beanstalk)

## 5. Dependency & Affinity Mapping
- **Critical Application Groups:** [LIST]
<!-- 
NOTE: Grouping must be driven by Application Affinity (latency/shared-DB) 
rather than simple IP subnet ranges.
-->

## 6. Hardware Lifecycle / Aging
[List EOL/EOS servers requiring immediate replacement]
