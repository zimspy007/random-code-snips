---
id: android_kotlin_integration
title: Android Kotlin Integration
sidebar_label: Android
---

## Sign in to Paynow and get integration details

> Before you can start making requests to Paynow's API, you need to get an integration ID and integration Key from Paynow. Details about how you can retrieve the ID and key are explained in detail on [this page](generation.md)

## Prerequisites

In order to make use of this project, the following prerequisites must be met for it to work.

1. Java JDK 7 or higher

## Installation
To use the Java Paynow SDK, you need to add the latest release as a dependency to your project. The latest release will be in the [Maven Central Repository](https://mvnrepository.com/artifact/zw.co.paynow/java-sdk).

#### Gradle
```gradle
repositories {
	mavenCentral()
}
dependencies {
	implementation 'zw.co.paynow:java-sdk:1.1.0'
}
```
