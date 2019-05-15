# zyrejni-example

Demo using zyrejni on linux

# Pre-requisites

* Build and install zyre on linux: https://github.com/zeromq/zyre
* Install jni binding for linux: https://github.com/zeromq/zyre/tree/master/bindings/jni

# Running the example

Run with maven:exec or "gradle run" as shown below

## Execute with maven

     mvn exec:java -Dexec.mainClass="org.zyre.example.Main"

## Execute with gradle

    ./gradlew run -PmainClass="org.zyre.example.Main"
