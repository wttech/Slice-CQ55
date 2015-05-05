![Cognifide logo](http://cognifide.github.io/Carty/assets/media/cognifide_logo.png)

Slice-CQ55
========

## Purpose

This is add-on which extends [Slice](https://github.com/Cognifide/Slice) functionality to support CQ version 5.5. It defines additional Guice modules which provides AEM-specific objects like Page, PageManager, etc.

Slice - a framework which simplifies Sling/AEM development by using dependency injection pattern and mapping Sling resources into Java objects. Slice repository: https://github.com/Cognifide/Slice

This add-on is no longer actively maintained.

## Prerequisites

* Slice 3.2
* CQ 5.5
* Apache Sling 2
* Maven 2.x, 3.x

## Installation

Slice is available from Maven Central Repo. However if you want to check out the newest development version, do the folling:

Checkout the source code:

    cd [folder of your choice]
    git clone git://github.com/Cognifide/Slice-CQ55.git
    cd Slice-CQ55

Compile and install:

    mvn clean install

## Usage

Add dependencied to your POM file:

   
    <dependency>
        <groupId>com.cognifide.slice-addon</groupId>
        <artifactId>slice-cq55</artifactId>
        <version>1.0.0</version>
        <scope>compile</scope>
    </dependency>
    <dependency>
        <groupId>com.cognifide.slice-addon</groupId>
        <artifactId>slice-cq55-taglib</artifactId>
        <version>1.0.0</version>
        <scope>compile</scope>
    </dependency>
