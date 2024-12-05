# v3grammar
This repository is used to archive versions of the v3 [RFCXML grammar](https://authors.ietf.org/en/rfcxml-vocabulary) used by [xml2rfc](https://github.com/ietf-tools/xml2rfc/) to render published RFCs.

The grammar is distributed in xml2rfc in two files for the two different forms of RelaxNG, v3.rnc and v3.rng, though only the .rnc file is used. The snapshots here have been renamed by appending the version number of the xml2rfc release that first introduced the change.

Changes to the grammar are infrequent and so there are normally multiple versions of xml2rfc that use the same grammar.  The table below lists the versions of the grammar and the versions of xml2rfc that used each version.

| .rnc file | xml2rfc versions that use this file |
| --------- | ----------------------------------- |
| v3.rnc-2.32.0 | 2.32.0 |
| v3.rnc-2.34.0 | 2.34.0 |
| v3.rnc-2.35.0 | 2.35.0 |
| v3.rnc-2.37.0 | 2.37.0 2.37.1 2.37.2 2.37.3 2.38.0 2.38.1 2.39.0 |
| v3.rnc-2.40.0 | 2.40.0 2.40.1 2.41.0 2.42.0 2.43.0 2.44.0 2.45.1 2.45.3 |
| v3.rnc-2.46.0 | 2.46.0 |
| v3.rnc-2.47.0 | 2.47.0 |
| v3.rnc-3.0.0 | 3.0.0 3.1.0 3.1.1 3.2.0 3.2.1 3.3.0 3.4.0 3.5.0 3.6.0 3.7.0 3.8.0 3.9.0 3.9.1 3.10.0 3.11.0 3.11.1 3.12.0 3.12.1 3.12.2 3.12.3 3.12.4 3.12.5 3.12.6 3.12.7 3.12.8 3.12.9 3.12.10 3.13.0 3.13.1 3.14.0 3.14.1 3.14.2 3.15.0 3.15.1 3.15.2 3.15.3|
| v3.rnc-3.16.0 | 3.16.0 and all versions after |

For more information on xml2rfc changes, see the [CHANGELOG](https://github.com/ietf-tools/xml2rfc/blob/main/CHANGELOG.md)