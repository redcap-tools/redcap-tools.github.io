---
layout: "page"
title: "REDCap Tools Projects"
permalink: "/projects/"
---

Below you'll find interesting projects that programmatically interact with [REDCap](http://www.project-redcap.org/).

Libraries
---------------------

The following libraries can assist communication with REDCap's API.  They can help make your development quicker and more robust.  Unlike the code samples in a subsequent list, these libraries are reusable components (and not loose code that's copied and pasted into each caller).  Each library's readme will have instructions how the deployed instances can be updated after the developer releases a new version.

<table class="table table-striped">
  <thead>
    <tr>
      <th>Project</th>
      <th>Language</th>
      <th>Description</th>
      <th>Release</th>
      <th>GitHub Activity<br>Last 12 months</th>
    </tr>
  </thead>
  <tbody>
  {% for library in site.data.libraries %}
    <tr>
      <td><a href="{{ library.repo }}">{{ library.name }}</a></td>
      <td>{{ library.language }}</td>
      <td>{{ library.description }}</td>
      <td><img src="{{ library.repo_release }}" alt="GitHub Release"> {% if library.docs %} <br /> <a href="{{ library.docs }}">Documentation</a> {% endif %}</td>
      <td><img src="{{ library.repo_activity }}" alt="GitHub Activity"></td>
    </tr>
  {% endfor %}
  </tbody>
</table>

Common Resources
---------------------

The some developers of different libraries have collaborated to create resources not tied to any specific library.  The finished products and the source code are available on GitHub, and any contributions or suggestions are welcomed.

<table class="table table-striped">
  <thead>
    <tr>
      <th>Resource</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
  {% for resource in site.data.resources %}
    <tr>
      <td><a href="{{ resource.link }}">{{ resource.name }}</a></td>
      <td>{{ resource.description }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

Code Samples and Snippets
---------------------

These samples can be copied and pasted into a larger program.  Some of the sample's code may have to be modified to work with your existing code.

<table class="table table-striped">
  <thead>
    <tr>
      <th>Project</th>
      <th>Language</th>
      <th>Description</th>
      <th>Release</th>
    </tr>
  </thead>
  <tbody>
  {% for sample in site.data.samples %}
    <tr>
      <td><a href="{{ sample.repo }}">{{ sample.name }}</a></td>
      <td>{{ sample.language }}</td>
      <td>{{ sample.description }}</td>
      <td><img src="{{ sample.repo_release }}" alt="GitHub Release"> {% if sample.docs %} <br /> <a href="{{ sample.docs }}">Documentation</a> {% endif %}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

Applications
---------------------

These programs or scripts extend REDCap capabilities and facilitate integration with other systems.

<table class="table table-striped">
  <thead>
    <tr>
      <th>Project</th>
      <th>Language</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
  {% for application in site.data.applications %}
    <tr>
      <td><a href="{{ application.repo }}">{{ application.name }}</a></td>
      <td>{{ application.language }}</td>
      <td>{{ application.description }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

Remarks
---------------------

* As a user choosing a resource, consider if you need one that's been updated since REDCap's version 6.0.0 (in Sept 2014), or since any other version that introduced API modifications and improvements.
* As a developer maintaining one of these resource, please tell us if you'd like changes to an entry below.  Help us keep the info current by editing the [libraries](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/libraries.yml), [resources](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/resources.yml), [samples](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/samples.yml) , or [applications](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/applications.yml) yaml files (depending on which table above you'd like to modify), and submitting a [PR](https://github.com/redcap-tools/redcap-tools.github.io/pulls).  Alternatively, you can create a conventional [GitHub issue](https://github.com/redcap-tools/redcap-tools.github.io/issues) and tell us how your project can be more accurately described.

Purpose of REDCap-Tools
---------------------

(*repeated from the [home page](http://redcap-tools.github.io/)*.)

[REDCap-Tools](https://github.com/redcap-tools) is an organization that fosters interesting projects built against [REDCap](http://project-redcap.org). Developers and projects in this organization have no official ties to REDCap other than a motivation to promote the data management capabilities provided by REDCap's more advanced tools (namely the API and Data Entry Triggers) to their fullest potential. We hope to foster projects across a wide-range of programming languages.  Our other goal is to connect users to the best existing [libraries and resources](http://redcap-tools.github.io/projects/) for their needs.

If you have written a tool or application that helps improve reproducibility or accuracy in your a REDCap-based project, please consider housing it in this organization. This growing community of advanced REDCap end-users may find interest in your project and may want to help make it better. Also, if you move on in your career, placing your project under this organization will help to keep it growing and improving after you have moved on.

Notably REDCap-Tools takes no ownership over the projects hosted in this organization. That is left to the discretion of the author(s).

If you have a suggestion, please consider [creating an issue](https://github.com/redcap-tools/redcap-tools.github.io/issues?q=is%3Aissue) for it in this repository (click the green 'New Issue' button in the top right).

Website Contributors
---------------------

* [@sburns](https://github.com/sburns)
* [Will Beasley](https://github.com/wibeasley), University of Oklahoma Health Sciences Center, [BBMC](http://www.ouhsc.edu/bbmc/#about)
* [Hao Zhu](https://github.com/haozhu233), [Marcus Institute for Aging Research](https://www.marcusinstituteforaging.org/)
