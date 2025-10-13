# [Nicks.Guru](https://nicks.guru) Commons BOM (Bill of Materials)

Commons modules versions for easy import.

## Usage

Pick the most recent version from
[Maven Central](https://central.sonatype.com/namespace/guru.nicks.commons), then use as follows:

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>guru.nicks.commons</groupId>
            <artifactId>bom</artifactId>
            <version>...</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>

<dependencies>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>cucumber-test-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>integration-test-starter</artifactId>
    </dependency>

    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>utils</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>design-patterns</artifactId>
    </dependency>

    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>qr-code-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>freemarker-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>notification-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>statemachine-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>rate-limit-starter</artifactId>
    </dependency>

    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>rest-dto</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>rest-security</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>swagger-starter</artifactId>
    </dependency>

    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>jpa-starter</artifactId>
    </dependency>
    <dependency>
        <groupId>guru.nicks.commons</groupId>
        <artifactId>redis-starter</artifactId>
    </dependency>
</dependencies>
```

## Disclaimer

THIS CODE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED
TO THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. USE AT YOUR OWN RISK.

Copyright © 2025 [nicks.guru](https://nicks.guru). All rights reserved.
