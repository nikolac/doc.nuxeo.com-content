---
title: Studio Overview and Concepts
review:
    comment: ''
    date: ''
    status: ok
toc: true
confluence:
    ajs-parent-page-id: '19793788'
    ajs-parent-page-title: Nuxeo Studio
    ajs-space-key: Studio
    ajs-space-name: Nuxeo Online Services
    canonical: Studio+Overview+and+Concepts
    canonical_source: 'https://doc.nuxeo.com/display/Studio/Studio+Overview+and+Concepts'
    page_id: '8192422'
    shortlink: pgF9
    shortlink_source: 'https://doc.nuxeo.com/x/pgF9'
    source_link: /display/Studio/Studio+Overview+and+Concepts
tree_item_index: 100
history:
    -
        author: Solen Guitter
        date: '2016-03-04 09:12'
        message: dd link to university cours
        version: '15'
    -
        author: Solen Guitter
        date: '2015-01-26 15:12'
        message: ''
        version: '14'
    -
        author: Solen Guitter
        date: '2014-11-27 11:59'
        message: ''
        version: '13'
    -
        author: Solen Guitter
        date: '2014-09-23 10:31'
        message: ''
        version: '12'
    -
        author: Solen Guitter
        date: '2014-03-11 18:01'
        message: ''
        version: '11'
    -
        author: jballina
        date: '2013-03-04 21:48'
        message: ''
        version: '10'
    -
        author: jballina
        date: '2013-03-04 21:48'
        message: ''
        version: '9'
    -
        author: Alain Escaffre
        date: '2012-12-31 00:55'
        message: ''
        version: '8'
    -
        author: Alain Escaffre
        date: '2012-12-31 00:55'
        message: ''
        version: '7'
    -
        author: Benjamin Jalon
        date: '2012-11-28 11:11'
        message: ''
        version: '6'
    -
        author: Benjamin Jalon
        date: '2012-11-28 11:11'
        message: ''
        version: '5'
    -
        author: Alain Escaffre
        date: '2011-09-06 01:42'
        message: Migrated to Confluence 4.0
        version: '4'
    -
        author: Alain Escaffre
        date: '2011-09-06 01:42'
        message: ''
        version: '3'
    -
        author: Solen Guitter
        date: '2011-08-05 18:36'
        message: ''
        version: '2'
    -
        author: Solen Guitter
        date: '2011-08-05 18:15'
        message: ''
        version: '1'
---
{{! excerpt}}
Nuxeo Studio is a SaaS (Software as a Service) application to configure the Nuxeo Platform easily which enables to develop new applications without writing code.
{{! /excerpt}}

**Nuxeo Studio consists in:**
- Studio Modeler, to configure your content models and business workflows
- Studio Designer, to configure your forms and layouts designs for Web UI

{{#> callout type='info' heading='Nuxeo University'}}
Watch the related courses on Nuxeo University:<br>
[Video on Nuxeo Studio Concepts](https://university.nuxeo.com/learn/public/course/view/elearning/142/nuxeo-platform-quickstart-nuxeo-studio-concepts)
![]({{file name='university-nuxeo-studio-concepts.png' page='nxdoc/university'}} ?w=450,border=true)
{{/callout}}

**Nuxeo Studio is a graphical configuration tool**. You can configure and design everything that builds your business logic (document types, views, forms and workflows) without writing code or XML configuration, thus preventing time-consuming development issues.<br>

**Nuxeo Studio makes the deployment of your applications easier**. Configurations can be deployed in a click, without even restarting your server. Studio generates a single JAR file that holds all your configurations.

**Nuxeo Studio enables you to upgrade your Nuxeo-based applications easily**. Your configurations are guaranteed compatible with the future versions of Nuxeo Platform. Our auto-migration tools ensure a safe and transparent path to new technologies. Nuxeo Studio also runs consistency checks to handle errors before deployment.

Since you can quickly configure the platform and safely make it evolve, Nuxeo Studio lowers the maintenance cost of your business applications and makes them easy to scale.

![](https://www.lucidchart.com/publicSegments/view/54c64fa0-9150-4b14-b7e0-572f0a009cea/image.png ?w=600,border=true)

## Making Nuxeo Platform Your Own

Nuxeo Studio enables you to adapt the Nuxeo Platform to your business application, from graphical configurations to the creation of new business workflows.

Using Nuxeo Studio you can:

- [Brand your application]({{page version='' space='studio' page='branding'}})
- [Add new document types, with new metadata and lifecycle]({{page version='' space='studio' page='content-model'}})
- [Create forms tailored to your document types]({{page version='' space='studio' page='form-layouts'}})
- [Display business content you need on customized views]({{page version='' space='studio' page='content-views'}})
- [Define your own search forms]({{page version='' space='studio' page='search-advanced-search'}})
- [Add new buttons, tabs, icons in the UI]({{page version='' space='studio' page='user-actions'}})
- [Automatize simple to complex actions on documents]({{page version='' space='studio' page='automation'}})
- [Define business workflows with manual and automated transitions, a dedicated dashboard, specific forms]({{page version='' space='studio' page='workflows'}})

## Getting Started

Here is a list of resources to start working with Nuxeo Studio:

- [Nuxeo Studio Concepts video](https://university.nuxeo.com/learn/public/course/view/elearning/142/nuxeo-platform-quickstart-nuxeo-studio-concepts): Our Nuxeo University video dedicated to the discovery of Nuxeo Studio
- [Working in Studio Modeler]({{page page='working-in-studio'}}): Discover screen by screen descriptions of the tool
- [Working in Studio Designer]({{page page='working-in-view-designer'}}): Discover the tool and its capabilities
- [Essential Nuxeo Platform Terminology]({{page space='nxdoc' page='essential-nuxeo-platform-terminology'}}): Get familiar with the concepts and terms used in the Platform
- [Quick Start Dev Guide]({{page space='nxdoc' page='configure-nuxeo-platform'}}): Start configuring a Nuxeo Platform project

## Browser Support

Nuxeo Studio Designer and parts of Modeler use the recent W3C standard Web Components and Google Polymer 2.0 framework (legacy mode). The [Google Polymer framework](https://www.polymer-project.org/) comes with [polyfills for Web Components](https://www.webcomponents.org/polyfills), a library that extends the support of web components standard to more browsers.
Nevertheless, due to browser support to some shadow DOM features and third-party libraries used in Nuxeo Studio, some browsers are not supported.

Supported browsers are:
{{! multiexcerpt name='webui-supported-browsers'}}
 - Google Chrome
 - Firefox
{{! /multiexcerpt}}

{{#> callout type='warning' heading='Exceptions on Firefox'}}
Firefox is not fully supported on Nuxeo Studio Designer. Currently, view editors - with widget preview on forms - are not supported.
{{/callout}}

## Exporting a Studio Project in Eclipse

From your instructions, Nuxeo Studio generates XML configurations. The plugin you can download from Nuxeo Studio is a strict set of XML files and pictures. To have a closer look: rename the downloaded JAR and unzip it. You can find the sources of your project. Technically, nothing prevents you from importing these files in Eclipse, modify them and commit changes in your own source repository.

**Yet, we do not recommend it because there is no reverse path:**
- You will **definitively** lose the ability to maintain your project in Studio. For example, you will no longer be able to configure any feature in a more recent version, or use drag and drop to modify an automation chain.
- You will lose the ease of maintenance. Indeed, to upgrade a plugin made with Studio, all you need is to change the version of the distribution of your project. Nuxeo Studio generates the XML according to your target application version.

If you consider switching your project to Eclipse because:

**You are blocked in Studio and cannot do something you want:**
- Try contributing an external declaration in the Advanced Settings.
- Submit your problem through the Help Request form or to your Nuxeo Support Team. We value your feedback, we build the Studio roadmap priorities around it!

 **You want to export the code to maintain configuration sources more easily:**
- Take a look at the Branch Management. You can commit your changes, track them and create tagged versions of your project, as well as manage several branches of the configuration.

{{#> callout type='tip' }}
Any other reason still leading you to import the project into Eclipse? Please share it in the feedback section of this page!
{{/callout}}
