Badges go here (see [shields.io](https://shields.io/), for examples).

[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-incubating.svg)](https://finosfoundation.atlassian.net/wiki/display/FINOS/Incubating)

<img src="https://github.com/finos/finos-landscape/blob/master/hosted_logos/security-reference-data.svg" width="100">

# Securities Reference Data Project 

Welcome to the Securities Reference Data project, hosted and led by [FINOS, The Fintech Open Source Foundation](https://www.finos.org). The Securities Reference Data project was launched in 2018 by FINOS member Nomura. 

### Challenge
There are a range of trade identifiers used across financial services (ISIN, CUSIP, SEDOL, LEI, FIGI, RIC, BBID and many more) that serve a number of purposes, from validating the integrity of a security to providing common identifiers used during trading and settlement. The majority are either fully or partially “closed" codes, although there are some initiatives that are partially or fully open, like FIGI and OpenCorporates.

However, no single code covers all securities, while individual securities may be represented by multiple identifiers and the granularity of coverage at entity vs. corporate level also varies. This often necessitates costly and error prone mapping across identifiers. The extent of the problem is greater in some asset classes than others and certainly more prominent within the OTC market.
Additionaly, the existence of regionally focused bodies/companies responsible for issuing the identifiers and, in come cases, requiring licenses to access them contributes to the problem, as they minimize the possibility of consolidation onto one identifier, causing delays and reducing transparency. All of these factors impact market efficiency and contribute to trade breaks and errors.

### Current focus
The project is currently discussing the development of an open source cloud-based solution to map securities and issuer IDs. Doing this once collaboratively has the potential to significantly reduce the costs and effort of maintaining this individually. The group has also been discussing the creation of a Currency Data Standard.

## Roadmap

Access the SecRef Data Roadmap [here](https://github.com/finos/secref-data/issues/25)

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
