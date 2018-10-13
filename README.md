# simple-servlet
A simple example of a Java servlet and a JSP. 



## Servlets

Java servlets are compiled Java classes that implement all or part of a web application. They are not standalone Java programs but must be run by a suitable web server.  Though this might seem complicated it actually makes creating and deploying web based applications easier.

![Example servlet architecture](images/servlet-diag.gif)

## Java Servlet Pages (JSP)

JSP is a document format combining HTML and Java to create "dynamic" web pages. These pages are delivered by the web server to the client as HTML, but before that the Java code is run to replace variables with actual values.  For example a JSP web page might look up order details from a data base and insert the results in an HTML table. 

If you've used PHP or ASPnet then you will see some strong similarities, at least in the approach to creating web content.

Servlets are usually packaged as ``WAR`` (web archive) files. Like a zip, jar or other archive these files contain a directory structure and multiple files that make up the web application.  Typically there will be .class, .jsp, and .html files. There will also be a web.xml file that describes the mapping of URLs to servlets.

## Running the servet

To run the servlet build the war file, then deploy using Jetty or Tomcat.

There are many ways test and run servlets, here are some suggestions.

1. From the command line.

1. As a Maven build.

1. Using the VS Code Jetty extension.

1. Using Tomcat.

