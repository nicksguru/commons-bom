# Bill of Materials (BOM)

A comprehensive Maven Bill of Materials for managing dependency versions across all Commons modules.

## Overview

This BOM provides centralized dependency management for:
- **Spring Boot & Spring Cloud** - Core framework and microservices support
- **TestContainers** - Integration testing with containerized databases
- **Camunda BPM** - Business process management and workflow engine
- **AWS SDK** - Amazon Web Services integration
- **Other libraries** - Security, monitoring, caching, and more

## Usage

Add this BOM to your project's `pom.xml` picking the most recent version from
[Maven Central](https://central.sonatype.com/namespace/guru.nicks.commons):

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
```

## Disclaimer

THIS CODE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED
TO THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. USE AT YOUR OWN RISK.

Copyright © 2025 [nicks.guru](https://nicks.guru). All rights reserved.
