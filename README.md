# cluster_prop_example

## Usage

To run this sample you will need at least JAVA 1.6 and Gradle. 

Build:

    ./gradle fatJar

The above command will build a jar file that contains all of the dependencies needed to run the sample.

Next:

    java -jar build/libs/cluster_prop_example-1.0.jar administrator@vsphere.local password 172.16.214.143 DC0_C0

This will execute the sample. It will use administrator@vsphere.local as the username, password as the password, it will connect to the host 172.16.214.143 and gather info about the cluster named DC0_C0

