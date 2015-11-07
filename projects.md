---
layout: "page"
title: "Projects"
permalink: "/projects/"
---

Below you'll find interesting projects built against either REDCap's API, the Data Entry Trigger or some combination.

#### PyCap
* Author: [@sburns](https://github.com/sburns)
* [Docs](http://pycap.readthedocs.org)
* [Source](http://github.com/sburns/PyCap)
* Language: Python

PyCap is a minimal wrapper around the REDCap API to export & import data and files. It natively works with [pandas](http://pandas.pydata.org). Install with `pip install PyCap`.

Also a few other libraries exist for communicating with REDCap:

| Project | Language | Description from its Repository|
| :------ | :------- | :----------------------------- |
| [GoCap](https://github.com/tjrivera/go-cap) | Go | A golang based library for REDCap. It provides helpful abstractions for making requests to REDCap's REST API. The project is currently in development and not considered production-ready. |
| [PhpCap](https://github.com/aarenson/PhpCap) | PHP | Provides classes that simplify the use of the REDCap application programming interface (API) using PHP. |
| [PyCap](https://github.com/redcap-tools/PyCap) | Python | A minimal wrapper around the REDCap API to export & import data and files. It natively works with [pandas](http://pandas.pydata.org). |
| [redcapAPI](https://github.com/nutterb/redcapAPI) | R | An R interface to REDCap (http://www.project-redcap.org/), and is an actively developed fork of [redcap](https://github.com/vubiostat/redcap), originally created by [Jeffrey Horner](https://github.com/jeffreyhorner). |
| [RedcapAPI](https://github.com/eugyev/RedcapAPI) | Ruby | An interface for REDCAP using ruby http://rubygems.org/gems/RedcapAPI |
| [REDCap_API](https://github.com/james2012/REDCap_API) | JavaScript | To Access REDCap by API |
| [REDCapR](https://github.com/OuhscBbmc/REDCapR) | R | Encapsulates functions to streamline calls from R to the REDCap API. |

(When you're choosing a library, consider if you need one that's been updated since REDCap's version 6.0.0 changes in Sept 2014).
