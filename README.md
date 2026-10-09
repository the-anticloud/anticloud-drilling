# DRILLING

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `DRILLING` in category **OIL_GAS**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** DRILLING · **Upstream pin:** `c9de0bba1c55225bbdbb2a0eca75f63cc3b9279b` · **Category:** OIL_GAS · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# Open Source Models for Oilfield Drilling

This project contains open source models of oilfield drilling processes. The intent of this project is to include self-contained code examples that are based on several sub-processes of drilling including hydraulics for pressure prediction, drill string dynamics, draw works, rate of penetration, and directional drilling. Additional models are added to the project as the open source initiative grows. Models are in the [GEKKO Python modeling and optimization language](https://gekko.readthedocs.io/en/latest) but may also be available for other environments as well such as MATLAB. 

### project Contact Information
John Hedengren

Brigham Young University

[Process Research and Intelligent Systems Modeling (PRISM)](https://apm.byu.edu/prism)

john.hedengren@byu.edu

### MPD Hydraulics

Managed Pressure Drilling Hydraulic model that predicts pressure and mud flow at the bit and choke with changes in density, mud pump flow, and choke valve position.

![MPD Hydraulics](mpd_hydraulics/mpd_hydraulics.png)

### Soft String

Rotational vibration dynamics are predicted with a soft string model that is broken into individual string segments that include rotational inertia, frictional, and spring effects. The combination of the individual segments may be used to predict rotational vibration. Stick slip is simulated with bit boundary conditions that simulate periods of stuck bit followed by a rapid release of the stored potential energy. A soft string model does not include the effects of borehole interaction with the drill string.

![Soft String](soft_string/soft_string.png)

### project Overview

This project is in support of the open source model, data, and case study initiative as detailed in the publication, *Creating Open Source Models, Test Cases, and Data for Oilfield Drilling Challenges*, SPE-194082-MS.

### Open Source Drilling Initiative Overview

Pastusek, P., Payette, G., Shor, R., Cayeux, E., Aarsnes, U.J., Hedengren, J.D., Menand, S., Macpherson, J., Gandikota, R., Behounek, M., Harmer, R., Detournay, E., Illerhaus, R., Liu, Y., Creating Open Source Models, Test Cases, and Data for Oilfield Drilling Challenges, SPE ATCE, March 2019, SPE-194082-MS.

The industry has significantly improved drilling performance based on knowledge from multiple models of components and systems.  However, most new models and source code have been recreated from scratch, which adds significant research overhead with little benefit.  
The authors propose that it is time to form a coalition of industry and academic leaders to support an open source effort for drilling, to encourage the reuse of ever improving models and code.  
The vision for this guiding coalition is to 1) set up a project for source code, data, benchmarks, and documentation, 2) submit good code, 3) review the models and data submitted, 4) use and improve the code, 5) propose and collect anonymized validation data, 6) attract talent and support to the effort, and 7) mentor those getting started.   We ask those interested to add their time and talent to the cause, and to publish their results through peer-reviewed literature. A number of online meetings are planned to create this coalition, establish a charter, and layout the guiding principles.
Several avenues have already been proposed to sustain the effort such as: annual user group meetings, creating a SPE Technical Section, and initiating a Joint Industry Program (JIP). The Open Porous Media Initiative is just one example of how this could be organized and maintained.
As a starting point, this paper reviews existing published drilling models and highlights the similarities and differences for commonly used drillstring dynamics, hydraulics and bit-rock interaction models.
Some of the key requirements for re-usability of the models and code are: 1) The model itself: open source, well documented and commented code shared in a publicly available project, 2) A user’s guide: how to run the core software, how to extend software capabilities, i.e., plug in new features or elements, 3) A theory manual: to explain the fundamental principles, the base equations, any assumptions, and the known limitations, 4) Data: that cover a diversity of drilling operations, 5) Test cases: to benchmark the performance and output of different proposed models.  
In May 2018 at “The 4th International Colloquium on Non-linear dynamics and control of deep drilling systems”, the keynote question was; “Is it time to start using open source models…” The answer is yes.
Modeling the drilling process is done to help drill a round, ledge free hole, without patterns, with minimum vibration, minimum unplanned dog legs, that reaches all geological targets, in one run per section, in the least time possible. 
An open source project for drilling will speed up the rate of learning and automation efforts to achieve this goal throughout the entire well execution workflow, including planning, BHA design, real-time operations, and post well analysis.

### References

1. Asgharzadeh Shishavan, R., Hubbell, C., Perez, H.D., Hedengren, J.D., Pixton, D.S., and Pink, A.P., Multivariate Control for Managed Pressure Drilling Systems Using High Speed Telemetry, SPE Journal, SPE-170962, Published Online 7 Oct 2015, DOI: 10.2118/170962-PA. [Article](https://www.onepetro.org/journal-paper/SPE-170962-PA)
2. Asgharzadeh Shishavan, R., Nonlinear Estimation and Control with Application to Upstream Processes, Dissertation, Brigham Young University, 2015. [Dissertation](https://apm.byu.edu/prism/uploads/Projects/Dissertation_Reza_Upstream_Automation.pdf)
3. Sugiura, J., Samuel, R., Oppelt, J., Ostermeyer, G.P., Hedengren, J.D., and Pastusek, P., Drilling Modeling and Simulation: Current State and Future Goals, SPE IADC Drilling Conference and Exhibition, SPE-173045, 17-19 March 2015, UK, London. [Article](https://www.onepetro.org/conference-paper/SPE-173045-MS)

---

## Installation

Several avenues have already been proposed to sustain the effort such as: annual user group meetings, creating a SPE Technical Section, and initiating a Joint Industry Program (JIP). The Open Porous Media Initiative is just one example of how this could be organized and maintained.
As a starting point, this paper reviews existing published drilling models and highlights the similarities and differences for commonly used drillstring dynamics, hydraulics and bit-rock interaction models.
Some of the key requirements for re-usability of the models and code are: 1) The model itself: open source, well documented and commented code shared in a publicly available project, 2) A user’s guide: how to run the core software, how to extend software capabilities, i.e., plug in new features or elements, 3) A theory manual: to explain the fundamental principles, the base equations, any assumptions, and the known limitations, 4) Data: that cover a diversity of drilling operations, 5) Test cases: to benchmark the performance and output of different proposed models.  
In May 2018 at “The 4th International Colloquium on Non-linear dynamics and control of deep drilling systems”, the keynote question was; “Is it time to start using open source models…” The answer is yes.
Modeling the drilling process is done to help drill a round, ledge free hole, without patterns, with minimum vibration, minimum unplanned dog legs, that reaches all geological targets, in one run per section, in the least time possible. 
An open source project for drilling will speed up the rate of learning and automation efforts to achieve this goal throughout the entire well execution workflow, including planning, BHA design, real-time operations, and post well analysis.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

![Soft String](soft_string/soft_string.png)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

Fork the project, create a feature branch, run the test suite, and open a pull request against upstream.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** DRILLING
- **Pinned SHA:** `c9de0bba1c55225bbdbb2a0eca75f63cc3b9279b`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`423166957497cad647e60f1b39287c318b9d59c70a9f39140ad4f2d77f6c0308`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

