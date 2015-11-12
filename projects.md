---
layout: "page"
title: "Projects"
permalink: "/projects/"
---

Below you'll find interesting projects that programmatically interact with [REDCap](http://www.project-redcap.org/).


##  Libraries

The following libraries can assist communication with REDCap's API.  They can help make your development quicker and more robust.  Unlike the code samples in a subsequent list, these libraries are reusable components (and not loose code that's copied and pasted into each caller).  Each library's readme will have instructions how the deployed instances can be updated after the developer releases a new version.

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
  {% for library in site.data.libraries %}
    <tr>
      <td><a href="{{ library.repo }}">{{ library.name }}</a></td>
	    <td>{{ library.language }}</td>
	    <td>{{ library.description }}</td>
      <td><img src="{{ library.repo_release }}" alt="GitHub Release"> {% if library.docs %} <br /> <a href="{{ library.docs }}">Documentation</a> {% endif %}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>

## Common Resources

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

## Code Samples and Snippets

These samples can be copied and pasted into a larger proram.  Some of the sample's code may have to be modified to work with your existing code.

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

## Remarks

* As a user choosing a resource, consider if you need one that's been updated since REDCap's version 6.0.0 (in Sept 2014), or since any other version that introduced API modifications and improvements.
* As a developer maintaining one of these resource, please tell us if you'd like changes to an entry below.  Help us keep the info current by editing the ["libraries"](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/libraries.yml), ["resources"](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/resources.yml), or ["samples"](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/samples.yml) yaml files (depending on which table above you'd like to modify), and submitting a [PR](https://github.com/redcap-tools/redcap-tools.github.io/pulls).  Alternatively, you can create a conventional [GitHub issue](https://github.com/redcap-tools/redcap-tools.github.io/issues) and tell us how your project can be more accurately described.
