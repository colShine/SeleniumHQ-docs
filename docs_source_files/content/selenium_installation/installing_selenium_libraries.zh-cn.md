---
title: "Installing Selenium libraries"
weight: 1
---

{{% notice info %}}
<i class="fas fa-language"></i> 页面需要从英语翻译为简体中文。
您熟悉英语与简体中文吗？帮助我们翻译它，通过 pull requests 给我们！
{{% /notice %}}

First you need to install the Selenium bindings for your automation project.
The installation process for libraries depends on the language you choose to use.

## Java
Installation of Selenium libraries for Java can be done using Maven.
Add the _selenium-java_ dependency in your project pom.xml:

```xml
<dependency>
  <groupId>org.seleniumhq.selenium</groupId>
  <artifactId>selenium-java</artifactId>
  <version>3.X</version>
</dependency>
```

The _selenium-java_ dependency supports running your automation
project with all Selenium supported browsers. If you want to run tests
only in a specific browser, you can add the dependency for that browser
in your _pom.xml_ file.
For example, you should add following dependency in your _pom.xml_
file to run your tests only in Firefox:

```xml
<dependency>
  <groupId>org.seleniumhq.selenium</groupId>
  <artifactId>selenium-firefox-driver</artifactId>
  <version>3.X</version>
</dependency>
```

In a similar manner, if you want to run tests only in Chrome,
you should add the following dependency:

```xml
<dependency>
  <groupId>org.seleniumhq.selenium</groupId>
  <artifactId>selenium-chrome-driver</artifactId>
  <version>3.X</version>
</dependency>
```

## Python
Installation of Selenium libraries for Python can be done using pip:

```shell
pip install selenium
```

Alternatively you can download the [PyPI source archive](https://pypi.org/project/selenium/#files)
(selenium-x.x.x.tar.gz) and install it using _setup.py_:

```shell
python setup.py install
```

## C#
Installation of Selenium libraries for C# can be done using NuGet:

```shell
# Using package manager
Install-Package Selenium.WebDriver
# or using .Net CLI
dotnet add package Selenium.WebDriver
```

## Ruby
Installation of Selenium libraries for Ruby can be done using gem:

```shell
gem install selenium-webdriver
```

## JavaScript
Installation of Selenium libraries for JavaScript can be done using npm:

```shell
npm install selenium-webdriver
```




