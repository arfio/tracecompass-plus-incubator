# TraceCompass With Incubator

## Prerequisites

### Java 8
`sudo apt-get install openjdk-8-jdk`

### Maven
`sudo apt-get install maven`

## Compiling

```
git clone --recursive https://github.com/arfio/tracecompass-plus-incubator.git
cd tracecompass-plus-incubator/tracecompass
mvn clean install -DskipTests && cd ../tracecompass-incubator && mvn clean install -DskipTests
```
The TraceCompass executable should be available at the following path:
`./tracecompass-incubator/rcp/org.eclipse.tracecompass.incubator.rcp.product/target/products/org.eclipse.tracecompass.incubator.rcp/linux/gtk/x86_64/trace-compass/`
