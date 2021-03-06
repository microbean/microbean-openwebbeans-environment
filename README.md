# microBean OpenWebBeans Environment

The microBean OpenWebBeans Environment project consists primarily of a
`pom.xml` file that describes runtime dependencies that together make
up a microBean environment with Apache's
[OpenWebBeans](http://openwebbeans.apache.org) project as the backing
CDI 2.0 implementation.

The `pom.xml` file also produces a Docker image that collects those
dependencies together in a root `/microbean` directory, together with
an Alpine Linux variant of the Java development kit.

Users of this project are either Java developers&mdash;who can include
the `pom.xml` directly as a dependency&mdash;or developers of Docker
images for microBean projects.

