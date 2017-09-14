![Tomcat Logo](https://raw.githubusercontent.com/ZHCNTEAM/Tomcat/master/images/tomcat.png)

## Apache Tomcat

The Apache Tomcat® software is an open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket technologies. The Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket specifications are developed under the Java Community Process.

The Apache Tomcat software is developed in an open and participatory environment and released under the Apache License version 2. The Apache Tomcat project is intended to be a collaboration of the best-of-breed developers from around the world. We invite you to participate in this open development project. To learn more about getting involved, click here.

Apache Tomcat software powers numerous large-scale, mission-critical web applications across a diverse range of industries and organizations. Some of these users and their stories are listed on the PoweredBy wiki page.

Apache Tomcat, Tomcat, Apache, the Apache feather, and the Apache Tomcat project logo are trademarks of the Apache Software Foundation.


## TomcatCon London 2017(2017-08-22)

The Apache Tomcat PMC is delighted to announce that registration for TomcatCon London is now open.

This one day conference will be held on Tuesday 26th September in central London and features talks from:

Mark Thomas (markt)
Rémy Maucherat (remm)
Jean-Frederic Clere (jfclere)
Full details, including the schedule is available on the conference page.

We hope to see you there!

2017-09-04 
## Tomcat Native 1.2.14 Released

The Apache Tomcat Project is proud to announce the release of version 1.2.14 of Tomcat Native. The notable changes since 1.2.12 include:

Windows binaries built with APR 1.6.2 and OpenSSL 1.0.2l.
Support for the SSL_CONF_cmd API.
Support for specifying trusted certificates in raw form.
Note that users should now be using 1.2.x in preference to 1.1.x.

Download | ChangeLog for 1.2.14

2017-08-18 
## Tomcat 8.0.46 Released

The Apache Tomcat Project is proud to announce the release of version 8.0.46 of Apache Tomcat. Apache Tomcat 8.0.46 includes fixes for issues identified in 8.0.45 as well as other enhancements and changes. The notable changes compared to 8.0.45 include:

Add the ability to set the defaults used by the Windows installer from a configuration file. Patch provided by Sandra Madden.
Add support to the WebSocket client for following redirects when attempting to establish a WebSocket connection. Patch provided by J Fernandez.
Full details of these changes, and all the other changes, are available in the Tomcat 8 changelog.

Note: End of life date for Apache Tomcat 8.0.x is announced. Read more...

Download

2017-08-16 
## Tomcat 7.0.81 Released

The Apache Tomcat Project is proud to announce the release of version 7.0.81 of Apache Tomcat. This release contains a number of bug fixes and improvements compared to version 7.0.79. The notable changes compared to 7.0.79 include:

Add the ability to set the defaults used by the Windows installer from a configuration file. Patch provided by Sandra Madden.
Add support to the WebSocket client for following redirects when attempting to establish a WebSocket connection. Patch provided by J Fernandez.
Full details of these changes, and all the other changes, are available in the Tomcat 7 changelog.

Download

2017-08-08 
## Tomcat 8.5.20 Released

The Apache Tomcat Project is proud to announce the release of version 8.5.20 of Apache Tomcat. Apache Tomcat 8.5.x is intended to replace 8.0.x and includes new features pulled forward from Tomcat 9.0.x. The minimum Java version and implemented specification versions remain unchanged. The notable changes compared to 8.5.16 include:

Add the ability to set the defaults used by the Windows installer from a configuration file. Patch provided by Sandra Madden.
Add support to the WebSocket client for following redirects when attempting to establish a WebSocket connection. Patch provided by J Fernandez.
Add support for the %X pattern in the AccessLogValve that reports the connection status at the end of the request. Patch provided by Zemian Deng.
Full details of these changes, and all the other changes, are available in the Tomcat 8.5 changelog.

Download

2017-08-08 
## Tomcat 9.0.0.M26 (alpha) Released

The Apache Tomcat Project is proud to announce the release of version 9.0.0.M26 (alpha) of Apache Tomcat. The is a milestone release of the 9.0.x branch and has been made to provide users with early access to the new features in Apache Tomcat 9.0.x so that they may provide feedback. The notable changes compared to 9.0.0.M22 include:

When generating JSP runtime error messages that quote the relevant JSP source code, switch from using the results of the JSP page parsing process to using the JSR 045 source map data to identify the correct part of the JSP source from the stack trace. This significantly reduces the memory footprint of Jasper in development mode, provides a small performance improvement for error page generation and enables source quotes to continue to be provided after a Tomcat restart.
Add LoadBalancerDrainingValve, a Valve designed to reduce the amount of time required for a node to drain its authenticated users
Improve the Default Servlet's handling of static files when the file encoding is not compatible with the required response encoding.
Add support for a Tomcat specific deployment descriptor, /WEB-INF/tomcat-web.xml. This descriptor has an identical format to /WEB-INF/web.xml. The Tomcat descriptor takes precedence over any settings in conf/web.xml but does not take precedence over any settings in /WEB-INF/web.xml.
Add ExtractingRoot, a new WebResourceRoot implementation that extracts JARs to the work directory for improved performance when deploying packed WAR files.
Add support to the WebSocket client for following redirects when attempting to establish a WebSocket connection. Patch provided by J Fernandez.
Add support for the %X pattern in the AccessLogValve that reports the connection status at the end of the request. Patch provided by Zemian Deng.
Full details of these changes, and all the other changes, are available in the Tomcat 9 changelog.

Download

2016-10-05 
## Tomcat Connectors 1.2.42 Released

The Apache Tomcat Project is proud to announce the release of version 1.2.42 of Apache Tomcat Connectors. This version fixes a number of bugs found in previous releases.

Download | ChangeLog for 1.2.42

2015-12-15 
## Tomcat Native 1.1.34 Released

The Apache Tomcat Project is proud to announce the release of version 1.1.34 of Tomcat Native. The notable changes since 1.1.33 include:

Unconditionally disable export Ciphers
Improve ephemeral key handling for DH and ECDH
Various fixes to build with newer OpenSSL versions
Note that, unless a regression is discovered in 1.2.x, users should now be using 1.2.x in preference to 1.1.x.

Download | ChangeLog for 1.1.34

2015-03-17 
## Apache Standard Taglib 1.2.5 Released

The Apache Tomcat Project is proud to announce the release of version 1.2.5 of the Standard Taglib. This tag library provides Apache's implementation of the JSTL 1.2 specification.

Version 1.2.5 is a minor bug fix release reverting a change made in 1.2.1 where <c:import> modified the HTTP method during POST operations, and fixing an issues that resulted in an AccessControlException during startup unless permission was granted to read the accessExternalEntity property.

Please see the Taglibs section for more details.

Download | Changes

2013-11-11 
## Tomcat Maven Plugin 2.2 Released

The Apache Tomcat team is pleased to announce the release of Tomcat Maven Plugin 2.2. Changelog available here.

The Apache Tomcat Maven Plugin provides goals to manipulate WAR projects within the Apache Tomcat servlet container.

The binaries are available from Maven repositories. You should specify the version in your project's plugin configuration:
```
<plugin>
  <groupId>org.apache.tomcat.maven</groupId>
  <artifactId>tomcat7-maven-plugin</artifactId>
  <version>2.2</version>
</plugin>
```
or
```
<plugin>
  <groupId>org.apache.tomcat.maven</groupId>
  <artifactId>tomcat6-maven-plugin</artifactId>
  <version>2.2</version>
</plugin>
```

## Old news

See former announcements.
