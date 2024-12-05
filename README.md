# v3grammar
This repository is used to archive versions of the v3 [RFCXML grammar](https://authors.ietf.org/en/rfcxml-vocabulary) used by [xml2rfc](https://github.com/ietf-tools/xml2rfc/) to render published RFCs.

The grammar is distributed in xml2rfc in two files for the two different forms of RelaxNG, v3.rnc and v3.rng, though only the .rnc file is used. The snapshots here have been renamed by appending the version number of the xml2rfc release that first introduced the change.

Changes to the grammar are infrequent and so there are normally multiple versions of xml2rfc that use the same grammar.  The table below lists the versions of the grammar and the versions of xml2rfc that used each version.

| .rnc file | released | changes                             | xml2rfc versions that use this file |
| --------- | -------- | ----------------------------------- | --------------- |
| v3.rnc-2.32.0 | 2019-10-04 | | 2.32.0 |
| v3.rnc-2.34.0 | 2019-10-23 | - Add **\<toc>**<br>  - Add "brackets" to **\<eref>**<br> - Fix **\<postal>** to remove order | 2.34.0 |
| v3.rnc-2.35.0 | 2019-11-12 | - Add text formatting to **\<xref>** | 2.35.0 |
| v3.rnc-2.36.0 (missing) | 2019-12-02 | - Add **\<table>** inside **\<li>** and **\<dd>** | 2.36.0 |
| v3.rnc-2.37.0 | 2019-12-10 | - Add **\<contact>** | 2.37.0 2.37.1 2.37.2 2.37.3<br> 2.38.0 2.38.1<br> 2.39.0 |
| v3.rnc-2.40.0 | 2020-02-18 | - Add **\<br>**<br> - Fix attribute grouping in **\<ul>** |  2.40.0 2.40.1<br> 2.41.0 2.42.0 2.43.0 2.44.0<br> 2.45.0 2.45.1 2.45.2 2.45.3 |
| v3.rnc-2.46.0 | 2020-06-23 | - Fix multiple email addresses in **\<address>** | 2.46.0 |
| v3.rnc-2.47.0 | 2020-07-17 | **Only formatting changes** |  2.47.0 |
| v3.rnc-3.0.0 | 2020-09-02 | - Add "indent" to **\<t>**<br> - Add **\<blockquote>** to **\<aside>**<br> - Add ```adaptive``` for "indent" in **\<ol>**<br> - Add default of ```3``` for "indent" in **\<ul>**<br> - Add default of ```3``` for "indent" in **\<dl>**<br> - Add **\<aside>** inside **\<artwork>** inside **\<dd>**<br> - Add **\<sub>** and **\<sup>** inside **\<sub>** and **\<sup>** | 3.0.0<br> 3.1.0 3.1.1<br> 3.2.0 3.2.1<br> 3.3.0 3.4.0 3.5.0 3.6.0 3.7.0 3.8.0<br> 3.9.0 3.9.1<br> 3.10.0<br> 3.11.0 3.11.1<br> 3.12.0 3.12.1 3.12.2 3.12.3 3.12.4<br> 3.12.5 3.12.6 3.12.7 3.12.8<br> 3.12.9 3.12.10<br> 3.13.0 3.13.1<br> 3.14.0 3.14.1 3.14.2<br> 3.15.0 3.15.1 3.15.2 3.15.3 |
| v3.rnc-3.16.0 | 2023-01-18 | - Add ```editorial``` to "submissionType" inside **\<rfc>**<br> - Add ```editorial``` to **\<stream>**<br> - Add ```editorial``` to "stream" inside **\<seriesInfo>** |  3.16.0 onwards |

For more information on xml2rfc changes, see the [CHANGELOG](https://github.com/ietf-tools/xml2rfc/blob/main/CHANGELOG.md)