# local_ceteicean
This repository supports my teaching of XML and GitHub publishing tools for an Introduction to Digital Humanities course.

It contains a fork of Barry Clark's Jekyll Now repository (https://github.com/barryclark/jekyll-now), plus a localized version of the TEI CETEIcean tool (https://github.com/TEIC/CETEIcean) for publishing XML in a browser. The localized version is modified so that it can work with students' own XML rather than with TEI.

The localized components are as follows:
* /js/CETEI_local.js: This is a copy of the CETEI.js file which has been be modified to process elements from non-TEI namespaces. 
* /xml/CETEIcean_mine.css: This is a copy of the CETEIcean.css file that can be used to create styles that work with the localized element names. 
* /xml/template.html: This is a version of the CETEIcean HTML template that points to the localized CSS and Javascript files.
