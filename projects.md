---
layout: "page"
title: "Projects"
permalink: "/projects/"
---

Below you'll find interesting projects built against either [REDCap](http://www.project-redcap.org/)'s API, the Data Entry Trigger or some combination.

## API Libraries

Several libraries exist for communicating with REDCap's API.  If one of these languages is available to you, they can help make your development quicker and more robust.

| Project | Language<br/>(Documentation) | Description from its Repository|
| :------ | :------: | :----------------------------- |
| [GoCap](https://github.com/tjrivera/go-cap)<br/>[![GitHub release](https://img.shields.io/github/release/tjrivera/go-cap.svg)](https://github.com/tjrivera/go-cap) | Go | A golang based library for REDCap. It provides helpful abstractions for making requests to REDCap's REST API. The project is currently in development and not considered production-ready. |
| [nef-c-sharp](https://github.com/redcap-tools/nef-c-sharp)<br/>[![GitHub release](https://img.shields.io/github/release/redcap-tools/nef-c-sharp.svg)](https://github.com/redcap-tools/nef-c-sharp) | C# | These functions push/pull [DataTable](https://msdn.microsoft.com/en-us/library/system.data.datatable.aspx)s.  It can be used in an .aspx program, or in a windows desktop program, a DET program, etc. |
| [PhpCap](https://github.com/aarenson/PhpCap)<br/>[![GitHub release](https://img.shields.io/github/release/aarenson/PhpCap.svg)](https://github.com/aarenson/PhpCap) | PHP<br/>[(Documentation)](https://github.com/aarenson/PhpCap/blob/master/README.md) | Provides classes that simplify the use of the REDCap application programming interface (API) using PHP. |
| [PyCap](https://github.com/redcap-tools/PyCap)<br/>[![GitHub release](https://img.shields.io/github/release/redcap-tools/PyCap.svg)](https://github.com/redcap-tools/PyCap) | Python<br/>[(Documentation)](http://pycap.readthedocs.org) | A minimal wrapper around the REDCap API to export & import data and files. It natively works with [pandas](http://pandas.pydata.org). |
| [redcapAPI](https://github.com/nutterb/redcapAPI)<br/>[![GitHub release](https://img.shields.io/github/release/nutterb/redcapAPI.svg)](https://github.com/nutterb/redcapAPI) | R<br/>[(Documentation)](https://cran.r-project.org/web/packages/redcapAPI/redcapAPI.pdf) | An R interface to REDCap, and is an actively developed fork of [redcap](https://github.com/vubiostat/redcap), originally created by [Jeffrey Horner](https://github.com/jeffreyhorner). |
| [RedcapAPI](https://github.com/eugyev/RedcapAPI)<br/>[![GitHub release](https://img.shields.io/github/release/eugyev/RedcapAPI.svg)](https://github.com/eugyev/RedcapAPI) | Ruby | An interface for REDCAP using ruby. |
| [REDCap_API](https://github.com/james2012/REDCap_API)<br/>[![GitHub release](https://img.shields.io/github/release/james2012/REDCap_API.svg)](https://github.com/james2012/REDCap_API) | JavaScript | To Access REDCap by API. |
| [REDCapR](https://github.com/OuhscBbmc/REDCapR)<br/>[![GitHub release](https://img.shields.io/github/release/OuhscBbmc/REDCapR.svg)](https://github.com/OuhscBbmc/REDCapR) | R<br/>[(Documentation)](https://github.com/OuhscBbmc/REDCapR/blob/master/documentation_peek.pdf) | Encapsulates functions to streamline calls from R to the REDCap API. |

When you're choosing a library, consider if you need one that's been updated since REDCap's version 6.0.0 changes in Sept 2014.

## Common Resources

The some developers of different libraries have collaborated to create resources not tied to any specific library.  The finished products and the source code are available on GitHub, and any contributions or suggestions are welcomed.

| Resource | Description |
| :------: | :---------- |
| [redcap-tools](http://redcap-tools.github.io/) | REDCap-Tools is a GitHub organization that fosters interesting projects built against REDCap. Developers and projects in this organization have no official ties to REDCap other than looking to push the data management capabilities provided by REDCap’s more advanced tools (namely the API and Data Entry Triggers) to their fullest potential. [Edit the web site source code [here](https://github.com/redcap-tools/redcap-tools.github.io); view the repositories [here](https://github.com/redcap-tools).)]|
| [API Troubleshooting Vignette](https://cdn.rawgit.com/OuhscBbmc/REDCapR/master/inst/doc/TroubleshootingApiCalls.html) | There are many links in the pipeline between your institution's REDCap server and the API user. When the end result is unsuccessful, this document should help narrow the location of the possible problem. The first two sections will be relevant to almost any language interacting with the API. (Edit source code [here](https://github.com/OuhscBbmc/REDCapR/blob/master/vignettes/TroubleshootingApiCalls.Rmd).)|
