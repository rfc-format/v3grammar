# v3grammar
This repository is used to archive versions of the v3 [RFCXML grammar](https://authors.ietf.org/en/rfcxml-vocabulary) used by [xml2rfc](https://github.com/ietf-tools/xml2rfc/) to render published RFCs.

The grammar is distributed in xml2rfc in two files for the two different forms of RelaxNG, v3.rnc and v3.rng, though only the .rnc file is used. These files were never assigned a version number when created and so the snapshots here have been renamed by appending the version number of the xml2rfc release that first introduced the change (e.g. the version of v3.rnc that was released with v2.32.0 of xml2rfc has been renamed v3-2.32.0.rnc).

Changes to the grammar were initially frequent and then in recent years have become infrequent and so there are normally multiple versions of xml2rfc that use the same grammar.  The table below lists the versions of the grammar and the versions of xml2rfc that used each version.

| .rnc file | released | changes                             | xml2rfc versions that use this file |
| --------- | -------- | ----------------------------------- | --------------- |
| v3-3.16.0.rnc | 2023-01-18 | - Add ```editorial``` to "submissionType" inside **\<rfc>**<br> - Add ```editorial``` to **\<stream>**<br> - Add ```editorial``` to "stream" inside **\<seriesInfo>** |  3.16.0 onwards |
| v3-3.0.0.rnc | 2020-09-02 | - Add "indent" to **\<t>**<br> - Add **\<blockquote>** to **\<aside>**<br> - Add ```adaptive``` for "indent" in **\<ol>**<br> - Add default of ```3``` for "indent" in **\<ul>**<br> - Add default of ```3``` for "indent" in **\<dl>**<br> - Add **\<aside>** inside **\<artwork>** inside **\<dd>**<br> - Add **\<sub>** and **\<sup>** inside **\<sub>** and **\<sup>** | 3.0.0<br> 3.1.0 3.1.1<br> 3.2.0 3.2.1<br> 3.3.0 3.4.0 3.5.0 3.6.0 3.7.0 3.8.0<br> 3.9.0 3.9.1<br> 3.10.0<br> 3.11.0 3.11.1<br> 3.12.0 3.12.1 3.12.2 3.12.3 3.12.4<br> 3.12.5 3.12.6 3.12.7 3.12.8<br> 3.12.9 3.12.10<br> 3.13.0 3.13.1<br> 3.14.0 3.14.1 3.14.2<br> 3.15.0 3.15.1 3.15.2 3.15.3 |
| v3-2.47.0.rnc | 2020-07-17 | **Only formatting changes** |  2.47.0 |
| v3-2.46.0.rnc | 2020-06-23 | - Allow multiple email addresses in **\<address>** | 2.46.0 |
| v3-2.40.0.rnc | 2020-02-18 | - Add **\<br>** back again<br> - Fix attribute grouping in **\<ul>** |  2.40.0 2.40.1<br> 2.41.0 2.42.0 2.43.0 2.44.0<br> 2.45.0 2.45.1 2.45.2 2.45.3 |
| v3-2.37.0.rnc | 2019-12-10 | - Add **\<contact>** | 2.37.0 2.37.1 2.37.2 2.37.3<br> 2.38.0 2.38.1<br> 2.39.0 |
| v3-2.36.0.rnc | 2019-12-02 | - Add **\<table>** inside **\<li>** and **\<dd>** | 2.36.0 |
| v3-2.35.0.rnc | 2019-11-12 | - Add text formatting to **\<xref>** | 2.35.0 |
| v3-2.34.0.rnc | 2019-10-23 | - Add **\<toc>**<br>  - Add "brackets" to **\<eref>**<br> - Fix **\<postal>** to remove order | 2.34.0 |
| v3-2.29.0.rnc | 2019-09-17 | - Add **\<artset>** to **\<td>** and **\<th>** | 2.29.0 |
| v3-2.24.0.rnc | 2019-08-10 | - Remove ```contributor``` as a "role"<br> - Fix empty **\<date>** | 2.24.0 2.25.0 2.26.0 2.70.0 2.27.1<br>2.28.0|
| v3-2.23.0.rnc | 2019-06-27 | - Require at least one **\<artwork>** inside **\<artset>** | 2.23.0 2.23.1 |
| v3-2.22.3.rnc | 2019-04-08 | - Add "indent" to **\<ol>** and **\<ul>** | 2.22.3 |
| v3-2.21.0.rnc | 2019-03-04 | - Add "showOnFrontPage" to **\<organization>** | 2.21.0 2.21.1 2.22.0 2.22.1 2.22.2 |
| v3-2.19.0.rnc | 2019-02-14 | - Add **\<artset>** | 2.19.0 2.19.1 2.20.0 |
| v3-2.18.0.rnc | 2019-02-06 | - Add "target" to **\<referencegroup>** | 2.18.0 |
| v3-2.15.0.rnc | 2018-11-30 | - Add "anchor" to **\<author>**<br> - Add ```contributor``` to "role"<br> - Change **\<postal>** order<br> - Add **\<u>**<br> - Add "quote-title" to **\<reference>**| 2.15.0 2.15.1 2.15.2 2.15.3 2.15.4<br> 2.15.5 2.16.0 2.16.1 2.16.2 2.16.3<br> 2.17.0 2.17.1 2.17.2 |
| v3-2.14.0.rnc | 2018-11-23 | - Add **\<iref>** to **\<table>**<br> - Add **\<stream>** | 2.14.0 2.14.1 |
| v3-2.13.0.rnc | 2018-11-17 | - Fix **\<postal>** order<br> - Add **\<extaddr>**<br> - Add **\<pobox>**<br> - Add **\<cityarea>**<br> - Add **\<sortingcode>**<br> - Add multiple elements to **\<name>**<br> - Change default for "newline" in **\<dl>**<br> - Remove **\<iref>** from **\<table>** (also see 2.14.0)<br> - Remove "derivedAnchor" from **\<refeerencegroup>** | 2.13.0 |
| v3-2.12.3.rnc | 2018-10-30 | - Add **\<pobox>**| 2.12.3 |
| v3-2.12.2.rnc | 2018-10-30 | - Reorder **\<postal>**<br> - Add **\<ext>** **\<cityarea>** **\<sortingcode>** and add to **\<postal>** | 2.12.2 |
| v3-2.12.1.rnc | 2018-10-29 | - Remove "iref" from **\<table>** | 2.12.1 |
| v3-2.12.0.rnc | 2018-10-28 | - Change inclusion of SVG grammar to use file in each release<br> - Change all "pn" from text to "xsd:ID"<br> - Remove "derivedAnchor" and "derivedCounter"<br> - Remove **\<blockquote>** from **\<li>**<br> - Change where **\<postalLine>** is allowed in **\<postal>**| 2.12.0 | 
| v3-2.11.1.rnc | 2018-10-11 | - Add "align" to **\<table>** | 2.11.1 |
| v3-2.11.0.rnc | 2018-10-07 | - Remove **\<br>**<br> - Replace "hanging" with "newline" in **\<dl>**<br> - Add "indent" to **\<dl>**| 2.11.0|
| v3-2.10.3.rnc | 2018-09-22 | - Add "markers" to **\<sourcecode>** | 2.10.3|
| v3-2.10.0.rnc | 2018-07-12 | - Allow **\<author>** inside **\<section>**<br> - Add "bare" to **\<ul>**<br> - Change "displayFormat" to "sectionFormat"<br> - Remove "derivedContent"<br> - Change table span defaults to "1"<br> - Allow multiple nesting of **\<reference>** | 2.10.0 2.10.1 2.10.2|
| v3-2.9.0.rnc | 2018-02-09 | - Change "category" to a fixed list<br> - Add support for section references in **\<xref>**<br> - Remove default for "stream"| 2.9.0 2.9.1 2.9.2 2.9.3 2.9.4 2.9.5<br>2.9.6 2.9.7 2.9.8 2.9.9|
| v3-2.7.0.rnc | 2017-07-01 | - Initial version of RFC 7991 grammar | 2.7.0<br> 2.8.0 2.8.1 2.8.2 2.8.3 2.8.4 2.8.5|

For more information on xml2rfc changes, see the [CHANGELOG](https://github.com/ietf-tools/xml2rfc/blob/main/CHANGELOG.md)