---
layout: "page"
title: "Projects"
permalink: "/projects/"
---

Below you'll find interesting projects built against either [REDCap](http://www.project-redcap.org/)'s API, the Data Entry Trigger or some combination.


## API Libraries

Several libraries exist for communicating with REDCap's API.  If one of these languages is available to you, they can help make your development quicker and more robust.

<table class="table table-striped">
  <thead>
    <tr>
      <th>Project</th>
      <th>Language</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
  {% for project in site.data.projects %}
    <tr>
      <td><a href="{{ project.repo }}">{{ project.name }}</a> <br /> <img src="{{ project.repo_release }}" alt="Github Release"></td>
	  <td>{{ project.language }} {% if project.docs %} <br /> <a href="{{ project.docs }}">Documentation</a> {% endif %}</td>
	  <td>{{ project.description }}</td>
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

## Remarks


* As a user choosing a resource, consider if you need one that's been updated since REDCap's version 6.0.0 (in Sept 2014), or since any other version that introduced API modifications and improvements.
* As a developer maintaining one of these resource, please tell us if you'd like changes to an entry below.  Help us keep the info current by editing the ["libraries" yaml file](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/projects.yml) or the ["resources" yaml file](https://github.com/redcap-tools/redcap-tools.github.io/blob/master/_data/resources.yml) (depending on which table above you'd like to modify), and submitting a [PR](https://github.com/redcap-tools/redcap-tools.github.io/pulls).  Alternatively, you can create a conventional [GitHub issue](https://github.com/redcap-tools/redcap-tools.github.io/issues) and tell us how your project can be more accurately described.
