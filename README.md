# JavaUltimateTools Auth v2.0.0
[![Build Status](https://travis-ci.org/JGCompTech/JavaUltimateTools-Auth.svg?branch=master)](https://travis-ci.org/JGCompTech/JavaUltimateTools-Auth) [![CircleCI](https://circleci.com/gh/JGCompTech/JavaUltimateTools-Auth.svg?style=svg)](https://circleci.com/gh/JGCompTech/JavaUltimateTools-Auth) [![Language grade: Java](https://img.shields.io/lgtm/grade/java/g/JGCompTech/JavaUltimateTools-Auth.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/JGCompTech/JavaUltimateTools-Auth/context:java) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.jgcomptech.tools/java-ultimate-tools-auth/badge.svg?style=flat-square)](https://maven-badges.herokuapp.com/maven-central/com.jgcomptech.tools/java-ultimate-tools-auth/) [![Javadocs](http://www.javadoc.io/badge/com.jgcomptech.tools/java-ultimate-tools-auth.svg?style=flat-square)](http://www.javadoc.io/doc/com.jgcomptech.tools/java-ultimate-tools-auth)

Java Ultimate Tools Auth allows for creation of a fully customizable authentication system that leverages user sessions and permissions. It contains the following:
- Auth Manager - The central class that allows you to control the entire library from one location.
- User Manager - Allows management of all user objects and connects to Hibernate to store them in a database.
- User Role Manager - Allows user objects to be assigned a user role which is subsequently assigned permissions. These roles can be basic or very complex depending on the needs of the application. A user can have explicit permissions assigned to it in addition to one or more user roles.
- Permisssion Manager - Allows for a user to be assigned permissions that grant or deny access to certain parts of the application and allow or prevent login during certain circumstances. A user can have explicit permissions assigned to it in addition to one or more user roles.
- Session Manager - Allows a user to stay logged in to your application and store info about that state and length of login.
- Subject - Allows for the ability to manage multiple user accounts via a single singleton object. This object becomes a placeholder for the current user.
- And Much More!

**NOTE: This Project Has Now Been Updated To Use Java 11!!!**

# Development
Want to contribute? Great!
Any help with development is greatly appreciated. If you want to add something or fix any issues please submit a pull request and if it is helpful it may be merged. Please check out our [Code of Conduct for Contributors](https://github.com/JGCompTech/JavaUltimateTools/blob/master/code-of-conduct.md).

# Documentation
The documentation for JUT is currently a work in progress and new changes will be occurring soon.
To access the documentation site go to: [https://javatools.jgcomptech.com](https://javatools.jgcomptech.com).
If you would like to view the JavaDoc info, it is hosted at [github.io(Current GitHub Branch)](https://jgcomptech.github.io/JavaUltimateTools-Auth/) and at [javadoc.io(Current Maven Release)](http://www.javadoc.io/doc/com.jgcomptech.tools/java-ultimate-tools-auth). The github.io version is what is stored in the doc folder in the project.

# Download
**[Download v2.0.0](https://github.com/JGCompTech/JavaUltimateTools-Databases/releases/tag/v2.0.0)**

The changelog can be found [here](https://javatools.jgcomptech.com/changelog/)

# Using with Maven
If you are familiar with [Maven](http://maven.apache.org), add the following XML
fragments into your pom.xml file. With those settings, your Maven will automatically download our library into your local Maven repository, since our libraries are synchronized with the [Maven central repository](http://repo1.maven.org/maven2/com/jgcomptech/tools/java-ultimate-tools/).

    <dependencies>
       <dependency>
          <groupId>com.jgcomptech.tools</groupId>
         <artifactId>java-ultimate-tools-auth</artifactId>
         <version>2.0.0</version>
       </dependency>
    </dependencies>

# License
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

JavaUltimateTools by J&G CompTech is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

&copy;2020 J&amp;G CompTech
