# polyglot-jakarta-ee-weblogic

This project demonstrates GraalVM's polyglot capabilities when running WebLogic on GraalVM.
As of version 14.1.1 this is now officially supported by Oracle.

Using Jakarte EE 8 a REST API (GET method, optional query parameter `name`) has been made
available for each the implemented polyglot capabilities:

- <http://localhost:7001/polyglot-jakarte-ee-weblogic/api/polyglot/javascript>

An index page is availabe at <http://localhost:7001/polyglot-jakarte-ee-weblogic>

Note: This project does not use any WebLogic dependencies or WebLogic specific features, so
it should also be possible to run this on any other Jakarte EE 8 complient application server
with GraalVM as it's JDK.

## Requirements

1. [GraalVM EE 19.3 based on Java 11](https://www.oracle.com/downloads/graalvm-downloads.html)
1. [WebLogic 14.1.1](https://www.oracle.com/middleware/technologies/weblogic-server-installers-downloads.html)

Install WebLogic using the GraalVM instructions: [Running Oracle WebLogic Server and Coherence on GraalVM Enterprise Edition](https://docs.oracle.com/en/middleware/standalone/weblogic-server/14.1.1.0/wlgvm/index.html)
