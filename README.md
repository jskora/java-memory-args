# Introduction

The `java-memory-args` application demonstrates the affects of Java memory arguments on
the JVM based on the argument positions in the command line.  

There does not appear to be a requirement for preference if multiple arguments 
are provided for the same setting, this tool demonstrates the memory 
configuration at JVM startup for testing the preference for a given JVM and 
operating system. 

## Building and running

To build and run the tool.

1. Checkout the source and build the source.
    ```bash
    git clone https://github.com/jskora/java-memory-args.git
    cd java-memory-args
    mvn clean package
    ```
1. Uncompress the distribution tar file.
    ```bash
    tar -xf target/java-memory-args-*.tar.gz
    ```
1. Execute the test script
    ```bash
    cd java-memory-args
    ./java-memory-args.sh
    ```