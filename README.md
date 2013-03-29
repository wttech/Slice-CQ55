Slice-CQ55
========

## Purpose

This is Slice Add-on which extends Slice functionality to support CQ version 5.5.

Slice is a framework that glues Sling and Google Guice together. It eases mapping between
resources to classed and to using dependency injection inside Sling and CQ applications.
Slice repository: https://github.com/Cognifide/Slice-CQ

## Prerequisites

* CQ / Apache Sling 2
* Maven 2.x, 3.x

## Installation

Slice is available from Maven Central Repo. However if you want to check out the newest development version, do the folling:

Checkout the source code:

    cd [folder of your choice]
    git clone git://github.com/Cognifide/Slice-CQ55.git
    cd Slice-CQ55

Compile and install:

    mvn clean package install

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