# Project Plan

## Key Dates

- **Project due:** Friday 2 October 2026, 11:45pm AEST (30% of unit grade)
- **plan.md required in GitHub:** by end of Week 6 (23 Aug 2026)

## Communication Plan

- **Frequency:** Weekly, every Friday evening.
- **Time:** ~5:00–6:00 pm AEST (Graham) / ~7:00–8:00 pm Fiji
- **Platform for calls:** Google Meet
- **First sync:** Friday 28 August 2026

## Schedule
The plan of tasks for each group member for the remainder of the project is:

- Week 5: We will each go through the assignment requirements and when we meet break down the requirements and create a plan.
- Week 6: Meet and go through the assignment requirements and notes we have taken. Prepare a plan for future weeks. Assumptions to be completed
- Week 7: Hans to setup the Network in Open WRT. Graham to complete IP Addressing Requirements 
- Week 8: Hans to complete Firewall Rules. Graham to complete the Network Diagram
- Week 9: Harden the WRT system. Capture and Analyse Network Traffic. Allocation TBD
- Week 10: Risk Assessment.  Allocation TBD
- Week 11: Reflection, written report and recorded demonstration.  Allocation TBD

## Schedule - WIP

## Schedule

```mermaid
gantt
    title COIT20246 Project Schedule - DST Group 1
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d

    section Planning
    Review spec and take notes         :done, w5, 2026-08-10, 7d
    Meet, compare notes, draft plan    :done, w6, 2026-08-17, 7d
    First group meeting                :milestone, m1, 2026-08-28, 0d

    section Network Setup
    Network setup OpenWRT - Hans            :active, w7a, 2026-08-31, 7d
    IP Addressing Requirements - Graham     :active, w7b, 2026-08-31, 7d
    Firewall Rules - Hans                   :w8a, after w7a, 7d
    Production Network Diagram - Graham     :w8b, after w7b, 7d

    section Hardening and Traffic Analysis
    Harden OpenWRT and analyse traffic      :w9, 2026-09-14, 7d

    section Risk Assessment
    Risk Assessment and Controls            :w10, 2026-09-21, 7d

    section Report and Submission
    Reflection, report, demo, package repo  :crit, w11, 2026-09-28, 5d
    Project due 2 Oct, 11.45pm AEST         :milestone, due, 2026-10-02, 0d
```


## Assumptions

- **Business:** Small accounting firm  (deals with sensitive client financial data, good fit for the risk assessment)
- **Staff:** 5 total
- **City:** Rockhampton, Australia
- **Staff roles:**
  1. Practice Manager (also handles admin)
  2. 2–3 Accountants/Tax Agents
  3. Bookkeeper
  4. IT Support (part-time)

- **Website content (draft — not yet confirmed):** services offered (tax prep, bookkeeping, business advisory), staff bios, contact form, client portal login for document exchange.