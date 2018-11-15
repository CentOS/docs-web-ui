# docs-web-ui

This repository contains sources for the CentOS Docs web user interface - javascript, CSS styling, templates, etc. Open issues and pull request against this repository for **UI fixes** only. For other issues or fixes, use:

* [CentOS_Docs](https://github.com/CentOS/docs) - the builder repository for the entire website, including for example structure configuration
* [CentOS_Installation_Guide](https://github.com/CentOS/docs-installation-guide) - the content repository for the Installation Guide

## Local preview

Follow [upstream instructions](https://docs.antora.org/antora-ui-default/build-preview-ui/) to build a UI bundle using this repository.

## Publishing a new UI version

To get an updated version of the UI on the website, package the sources using `gulp pack` (see the link in Local preview for instructions). Then, move the package to the [CentOS_Docs_Web](https://github.com/CentOS/docs-web) repository on branch `prod`. From there it has to be published manually at the moment; we don't have CI set up yet.
