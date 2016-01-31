# Awesome Wicket
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome projects powered by [Apache Wicket](http://wicket.apache.org) 

Your contributions are always welcome!

- [Libraries](#libraries)
  - [WicketStuff](#wicketstuff)
- [Web Frameworks](#web-frameworks)
- [Solutions](#solutions)

## Libraries
List of libraries and components which can be used in your application

- [wicket-akka](https://github.com/l0rdn1kk0n/wicket-akka) - integration of Akka for Wicket
- [wicket-autowire](https://github.com/wicket-acc/wicket-autowire) - makes your life easier by automatic creation of component according to provided annotation
- [wicket-bootstrap](https://github.com/l0rdn1kk0n/wicket-bootstrap) - integration of Bootstrap Toolkit for Wicket
- [wicket-clientside-logging](https://github.com/l0rdn1kk0n/wicket-clientside-logging) - helper library that allows javascript logging on client side, all log messages will be stored on server side too
- [wicket-console](https://github.com/PhantomYdn/wicket-console) - lightweight AJAX-enabled web console for runtime execution JS scripts on server side
- [wicket-dnd](https://github.com/svenmeier/wicket-dnd) - generic Drag&Drop framework for Wicket
- [wicket-fullcalendar](https://github.com/42Lines/wicket-fullcalendar) - integration of [FullCalendar](http://fullcalendar.io/) javascript lib with Wicket
- [wicket-jquery-selectors](https://github.com/l0rdn1kk0n/wicket-jquery-selectors) - library for working with JQuery and Wicket
- [wicket-modelfactory](http://wicketeer.org/wicket-modelfactory/) - Wicket-modelfactory is an API to create Wicket PropertyModels in a typesafe and refactoring-safe way
- [wicket-mustache](https://github.com/l0rdn1kk0n/wicket-mustache) - provides a specialized panel and some related utilities that enables users to work with Mustache and Wicket
- [wicket-orientdb](https://github.com/OrienteerDW/wicket-orientdb) - integration of Wicket with [OrientDB](http://orientdb.com/)
- [wicket-requirejs](https://github.com/l0rdn1kk0n/wicket-requirejs) - helper to use require.js in your Wicket application
- [wicket-shieldui](https://github.com/shieldui/wicket-shieldui) - components leveraging the use of the [Shield UI](http://www.shieldui.com/) JavaScript library
- [wicket-spring-boot](https://github.com/MarcGiffing/wicket-spring-boot) - makes it easy to create Wicket projects with a minimum of configuration effort by using Sprint Boot
- [wicket-webjars](https://github.com/l0rdn1kk0n/wicket-webjars) - integration of webjars for Wicket
- [wicked-charts](https://github.com/thombergs/wicked-charts) - beautiful and interactive javascript charts for Java-based web applications

### WicketStuff
[WicketStuff](https://github.com/wicketstuff/core) based libraries

- [Annotation](https://github.com/wicketstuff/core/wiki/Annotation) - mount your pages declarativly by java annotations
- [Annotation Event Dispatcher](https://github.com/wicketstuff/core/tree/master/annotationeventdispatcher-parent) - improves events handling in Wicket by annotations
- [Async Tasks](https://github.com/wicketstuff/core/wiki/Async-tasks) -  control a background process within a Wicket application
- [Autocomplete TagIt](https://github.com/wicketstuff/core/wiki/Autocomplete-TagIt) - [TagIt](http://aehlke.github.com/tag-it/) integration with Wicket
- [BrowserId](https://github.com/wicketstuff/core/wiki/BrowserId) - [Mozilla Persona](https://login.persona.org/) integration with Wicket
- [Console](https://github.com/wicketstuff/core/wiki/Console) - provides support for executing code dynamically (at runtime)
- [Context](https://github.com/wicketstuff/core/wiki/Context) - is used to locate components,models and models' objects declaratively with @Context annotation.
- [Dashboard](https://github.com/wicketstuff/core/tree/master/dashboard-parent) - support of dashboards for Wicket for quick access to required information in widgets
- [DataStores](https://github.com/wicketstuff/core/wiki/DataStores) - collection of various implementation of [IDataStore](https://github.com/apache/wicket/blob/master/wicket-core/src/main/java/org/apache/wicket/pageStore/IDataStore.java): [MemCached](http://memcached.org/), [Apache Cassandra](http://cassandra.apache.org/), [Redis](http://redis.io/), [Hazelcast](http://www.hazelcast.com/)
- [Datatable Autocomplete](https://github.com/wicketstuff/core/wiki/Datatable-Autocomplete) - provides a search data structure known as a [Trie](http://en.wikipedia.org/wiki/Trie) that allows AJAX searches on large datasets fast
- [DataTables](https://github.com/wicketstuff/core/wiki/DataTables) - [DataTables jQuery](http://www.datatables.net/) Plugin Integration
- [Editable Grid](https://github.com/wicketstuff/core/wiki/Editable-Grid) - a grid component with add/edit/delete feature all at once, apart from supporting sorting/filtering/paging
- [Eidogo](https://github.com/wicketstuff/core/wiki/Eidogo) - SGF viewer and editor for GO game (also called baduk, igo or weiqi). 
- [Facebook](https://github.com/wicketstuff/core/wiki/Facebook) - contains wicket components and behaviors to use the [Facebook](https://facebook.com) social plugins with wicket
- [Fast Serializer](https://github.com/wicketstuff/core/wiki/FastSerializer) - Wicket Serializer using the Fast 1.x (FST) library
- [Fast Serializer 2](https://github.com/wicketstuff/core/wiki/FastSerializer2) - Wicket Serializer using the Fast 2.x (FST) library
- [GMap3](https://github.com/wicketstuff/core/wiki/Gmap3) - offers a component to use Google Maps v3 within Wicket applications
- [Google AppEngine Initializer](https://github.com/wicketstuff/core/wiki/Google-AppEngine-Initializer) - provides Wicket's org.apache.wicket.IInitializer implementation that auto-configures the Wicket Application to be runable at Google AppEngine
- [Google Charts](https://github.com/wicketstuff/core/wiki/GoogleCharts) - allows creation of charts using the [Google Chart API](https://developers.google.com/chart/)
- [HTML5](https://github.com/wicketstuff/core/wiki/Html5) - contains classes that give wicket support for using exciting new Html5 features
- [HTML Compressor](https://github.com/wicketstuff/core/wiki/Htmlcompressor) - integration library for Wicket and [htmlcompressor](http://code.google.com/p/htmlcompressor)
- [InMethodGrid](https://github.com/wicketstuff/core/wiki/InMethodGrid) - data grid component
- [Java EE Inject](https://github.com/wicketstuff/core/wiki/Java-EE-Inject) - provides integration through Java EE 5 resource injection
- [JEE Web Integration](https://github.com/wicketstuff/core/wiki/JEE-Web-Integration) - embed Servlet, JSP abd JSF content into wicked HTML pages
- [JqPlot Plugin Integration](https://github.com/wicketstuff/core/wiki/JqPlot-Plugin-Integration) - produces beautiful line, bar and pie charts with many features
- [JWicket UI Toolip](https://github.com/wicketstuff/core/wiki/jWicket-UI-Tooltip) - generate the JavaScript needed to provide a Wicket Component with a jQuery UI tooltip
- [Kryo Serializer](https://github.com/wicketstuff/core/wiki/Kryo-Serializer) - an implementation of org.apache.wicket.serialize.ISerializer for Wicket
- [Kryo2 Serializer](https://github.com/wicketstuff/core/tree/master/serializer-kryo2) - an implementation of org.apache.wicket.serialize.ISerializer for Wicket
- [LazyModel](https://github.com/wicketstuff/core/wiki/LazyModel) - type-safe model implementation
- [Lightbox2 Plugin Integration](https://github.com/wicketstuff/core/wiki/Lightbox2-Plugin-Integration) - simple, unobtrusive script used to overlay images on top of the current page
- [Logback](https://github.com/wicketstuff/core/wiki/Logback) - the home for classes that can help with using wicket and [logback](http://logback.qos.ch/) together
- [MBeanView](https://github.com/wicketstuff/core/wiki/MBeanView) - JMX panel, to view and operate the applications mbeans
- [Minis](https://github.com/wicketstuff/core/wiki/Minis) - collection of assorted components and behaviors that are too small to warrant their own project
- [ModalX](https://github.com/wicketstuff/core/wiki/ModalX) - a lightweight extension to Wicket's ModalWindow capabilities that comes with standardized MessageBox class and allows easy definition of Modal dialog box classes
- [OSGI](https://github.com/wicketstuff/core/wiki/Osgi) - lets you use Wicket in OSGi environments
- [Open Layers 3](https://github.com/wicketstuff/core/tree/master/openlayers3-parent) - provides a set of components that may be used to add interactive maps to a Wicket application
- [POI](https://github.com/wicketstuff/core/wiki/POI) - integrates Wicket projects to Apache POI
- [Progressbar](https://github.com/wicketstuff/core/wiki/Progressbar) - provides a progress bar component for Wicket
- [Push](https://github.com/wicketstuff/core/wiki/Push) - provides support for Reverse AJAX in Wicket applications and allows them to "push" partial Web page updates to the Web browser
- [Scala Extensions](https://github.com/wicketstuff/core/wiki/ScalaExtensions) - improves the syntax of Wicket models when using the Scala programming language
- [Select2](https://github.com/wicketstuff/core/tree/master/select2-parent) - provides Apache Wicket components that leverage [Select2](http://ivaynberg.github.com/select2) JavaScript library to build select boxes that provide Ajax choice filtering, custom rendering and etc.
- [Servlet Container Authentication and Authorization](https://github.com/wicketstuff/core/wiki/Servlet-Container-Authentication-and-Authorization) - simplify the integration of wicket-auth-roles with the servlet 3 security container
- [Spring Reference](https://github.com/wicketstuff/core/wiki/SpringReference) - can be used to integrate a wicket web application with spring
- [Stateless](https://github.com/wicketstuff/core/tree/master/stateless-parent) - adds a few components that provide more comprehensive stateless features for Wicket
- [TinyMCE Integration](https://github.com/wicketstuff/core/wiki/TinyMCE-Integration) - integration of the well-known TinyMCE WYSIWYG editor in Wicket
- [Twitter](https://github.com/wicketstuff/core/wiki/Twitter) - contains wicket components and behaviors to use the Twitter widgets with wicket
- [UrlFragment](https://github.com/wicketstuff/core/tree/master/urlfragment-parent) - with this you can build bookmarkable AJAX features and still support the back button
- [WHighCharts](https://github.com/wicketstuff/wiquery-highcharts) - provides WiQuery bindings for HighCharts
- [Whiteboard](https://github.com/wicketstuff/core/wiki/Whiteboard) - provides a Whiteboard which can be integrated in any wicket application
- [wicket-foundation](https://github.com/wicketstuff/core/tree/master/wicket-foundation) - integrates Wicket and [Zurb Foundation](http://foundation.zurb.com/)
- [Wicket Rest Annotations](https://github.com/wicketstuff/core/tree/master/wicketstuff-restannotations-parent) - provides a special resource class and a set of annotations to implement REST API/services in much the same way as we do it with Spring MVC or with the standard JAX-RS
- [WiQuery](https://github.com/wicketstuff/wiquery) - Wicket integration with jQuery and jQuery UI
- [WqPlot](https://github.com/wicketstuff/wiquery-jqplot) - provides WiQuery bindings for JqPlot

## Web Frameworks
Web Framework on top of wicket which allow you to build your system easily and smoothly

- [Apache Isis](https://isis.apache.org/) - a framework for rapidly developing domain-driven apps in Java
- [BrixCMS](http://www.brixcms.org/) - wicket based CMS (seems to be dead)
- [Orienteer](https://github.com/OrienteerDW/Orienteer) - web framework on top of Wicket and [OrientDB](http://orientdb.com/) to build you own CRM, CMS, ERP, mobile app backend or just common site
- [Wicketopia](https://github.com/jwcarman/Wicketopia) - Rapid Application Development (RAD) library for the Wicket

## Solutions
End-to-end solution based on wicket and derived [Web Frameworks](#web-frameworks)

- [eHour](https://ehour.nl/index.phtml) - open source time tracking tool
- [Estatio](https://github.com/estatio/estatio) - open source estate management built on Apache Isis and wicket
- [NextReports](http://www.next-reports.com/) - smart business reportins
- [Orienteer](https://github.com/OrienteerDW/Orienteer) - open source customizable data warehouse, CRM, ERP, app/site backend system for small and medium businesses
