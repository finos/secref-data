Badges go here (see [shields.io](https://shields.io/), for examples).

[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-incubating.svg)](https://finosfoundation.atlassian.net/wiki/display/FINOS/Incubating)

<img src="https://github.com/finos/finos-landscape/blob/master/hosted_logos/security-reference-data.svg" width="100">

# Securities Reference Data Project 

Welcome to the Securities Reference Data project, hosted and led by [FINOS, The Fintech Open Source Foundation](https://www.finos.org). The Securities Reference Data project was launched in 2018 by FINOS member Nomura. 

The project currently has two work streams: **Securities Reference Data** and **Currency Reference Data**.

## Securities Reference Data

### Roadmap
The project is currently discussing the development of an [open source cloud-based solution to map securities and issuer IDs](https://github.com/finos/secref-data/blob/master/SecRef_%20Securities%20%26%20Issuer%20ID%20mapping_%20.pdf). Doing this once collaboratively has the potential to significantly reduce the costs and effort of maintaining this individually.

For more information see the [Securities Reference Data Roadmap](https://github.com/finos/secref-data/issues/25) .

#### Background
There are a range of trade identifiers used across financial services (ISIN, CUSIP, SEDOL, LEI, FIGI, RIC, BBID and many more) that serve a number of purposes, from validating the integrity of a security to providing common identifiers used during trading and settlement. The majority are either fully or partially “closed" codes, although there are some initiatives that are partially or fully open, like FIGI and OpenCorporates.

However, no single code covers all securities, while individual securities may be represented by multiple identifiers and the granularity of coverage at entity vs. corporate level also varies. This often necessitates costly and error prone mapping across identifiers. The extent of the problem is greater in some asset classes than others and certainly more prominent within the OTC market.
Additionaly, the existence of regionally focused bodies/companies responsible for issuing the identifiers and, in come cases, requiring licenses to access them contributes to the problem, as they minimize the possibility of consolidation onto one identifier, causing delays and reducing transparency. All of these factors impact market efficiency and contribute to trade breaks and errors.

### Contribute to SecRef Data
All Securities Reference Data project collaboration activities, including meeting minutes, are hosted on this SecRef Data GitHub repo. Activities prior to July 2020 can be found in the Securities Reference Data project [archive](https://finosfoundation.atlassian.net/wiki/spaces/DT/pages/656834673/Security+Reference+Data+Project). For more information about FINOS project materials and communication, please review the [FINOS Governance](https://github.com/finos/community/blob/master/governance/Collaborative-Principles.md).

There are several ways to contribute to SecRef Data:
* **Join the next meeting**: participants of the Security Reference Data project meet every second Tuesday at 11am ET / 4pm GMT. Find the next meeting on the [FINOS project meetings calendar](https://calendar.google.com/calendar/u/0/embed?src=finos.org_fac8mo1rfc6ehscg0d80fi8jig@group.calendar.google.com&ctz=America/New_York). 
and browse [past meeting minutes in GitHub](https://github.com/finos/secref-data/issues?q=label%3Ameeting+). If you're looking for meeting minutes dated June 2020 or earlier, please access the Security Reference Data project [archive](https://finosfoundation.atlassian.net/wiki/spaces/DT/pages/656834678/Minutes+of+the+Security+Reference+Data+Project).
* **Join the mailing list**
Communications for the Securities Reference Data project are conducted through the data-tech-sec-ref@finos.org mailing list. Please email [data-tech-sec-ref+subscribe@finos.org](mailto:data-tech-sec-ref+subscribe@finos.org) to join the mailing list.
* **Contribute use cases** at https://github.com/finos/secref-data/issues/33
* **Contribute code** or contribute to **building the mapping table**: reach out to data-tech-sec-ref@finos.org expressing your interest in contributing
* **Raise an issue**: if you have any questions or suggestions, please [raise an issue](https://github.com/finos/secref-data/issues/new/choose)

## Currency Reference Data 

### Roadmap
The objective of this work stream is to create a standard object to represent currency data and create a central cloud based repository of the currency data. 
Modeling is being done in the FINOS hosted instance of [Legend Studio](https://github.com/finos/legend-studio), and the current model can be accessed at https://legend.finos.org/studio/viewer/UAT-38 (see screenshot below) Please note that you will need to have an account on the FINOS hosted instance of Legend Studio in order to access it. You can request an account at [finos.org/legend](https://www.finos.org/legend). 

<img src="https://github.com/finos/secref-data/blob/master/CurRefModel_Screenshot.png" width="1000">

For more information see the **[Currency Reference Data Roadmap](https://github.com/finos/secref-data/issues/29)**.

#### Background
The Currency Reference Data work stream spawned off the [Legend Pilot FX Options working group](https://github.com/finos/legend#phase-1-january-2020---september-2020---completed), which identified the need to standardise currency data for several use cases.  In an example of cross pollination across FINOS projects, the FX Options working group connected with the Securities Reference Data project and participants from both groups decided to set up a Currency Reference Data work stream. 

### Contribute to CurRef Data
There are several ways to contribute to Currency Reference Data:

* **Join the next meeting**: participants of the Currency Reference Data workstream meet every second Tuesday at 10am ET / 3pm GMT. Find the next meeting on the [FINOS projects calendar](https://calendar.google.com/calendar/u/0/embed?src=finos.org_fac8mo1rfc6ehscg0d80fi8jig@group.calendar.google.com&ctz=America/New_York) and browse [past meeting minutes in GitHub](https://github.com/finos/secref-data/labels/meeting).
* **Propose changes to the model**: request an account on the FINOS Legend Studio hosted instance at [finos.org/legend](https://www.finos.org/legend) in order to access the model at https://legend.finos.org/studio/viewer/UAT-38
* **Contribute use cases** at https://github.com/finos/secref-data/issues/30
* **Raise an issue**: if you have any questions or suggestions, please [raise an issue](https://github.com/finos/secref-data/issues/new/choose)

## Contributing

1. Fork it (<https://github.com/finos/secref-data/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Read our [contribution guidelines](.github/CONTRIBUTING.md) and [Community Code of Conduct](https://www.finos.org/code-of-conduct)
4. Commit your changes (`git commit -am 'Add some fooBar'`)
5. Push to the branch (`git push origin feature/fooBar`)
6. Create a new Pull Request

_NOTE:_ Commits and pull requests to FINOS repositories will only be accepted from those contributors with an active, executed Individual Contributor License Agreement (ICLA) with FINOS OR who are covered under an existing and active Corporate Contribution License Agreement (CCLA) executed with FINOS. Commits from individuals not covered under an ICLA or CCLA will be flagged and blocked by the FINOS Clabot tool. Please note that some CCLAs require individuals/employees to be explicitly named on the CCLA.

*Need an ICLA? Unsure if you are covered under an existing CCLA? Email [help@finos.org](mailto:help@finos.org)*

## License

Copyright 2020 {name of copyright owner}

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
