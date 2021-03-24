# vlingo-auth

[![Javadocs](http://javadoc.io/badge/io.vlingo/vlingo-auth.svg?color=brightgreen)](http://javadoc.io/doc/io.vlingo/vlingo-auth) [![Build](https://github.com/vlingo/vlingo-auth/workflows/Build/badge.svg)](https://github.com/vlingo/vlingo-auth/actions?query=workflow%3ABuild) [ ![Download](https://api.bintray.com/packages/vlingo/vlingo-platform-java/vlingo-auth/images/download.svg) ](https://bintray.com/vlingo/vlingo-platform-java/vlingo-auth/_latestVersion) [![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/vlingo-platform-java/community)

The VLINGO XOOM platform SDK authentication and authorization service. This can be used by XOOM platform components and also might be suitable for hosted platform services and applications.

Docs: https://docs.vlingo.io/vlingo-auth

### Important
If using snapshot builds [follow these instructions](https://github.com/vlingo/vlingo-platform#snapshots-repository) or you will experience failures.

### Bintray

```xml
  <repositories>
    <repository>
      <id>jcenter</id>
      <url>https://jcenter.bintray.com/</url>
    </repository>
  </repositories>
  <dependencies>
    <dependency>
      <groupId>io.vlingo</groupId>
      <artifactId>vlingo-auth</artifactId>
      <version>1.5.0</version>
      <scope>compile</scope>
    </dependency>
  </dependencies>
```

```gradle
dependencies {
    compile 'io.vlingo:vlingo-auth:1.5.0'
}

repositories {
    jcenter()
}
```

License (See LICENSE file for full license)
-------------------------------------------
Copyright © 2012-2020 VLINGO LABS. All rights reserved.

This Source Code Form is subject to the terms of the
Mozilla Public License, v. 2.0. If a copy of the MPL
was not distributed with this file, You can obtain
one at https://mozilla.org/MPL/2.0/.
