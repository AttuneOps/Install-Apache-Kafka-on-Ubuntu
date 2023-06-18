Let's proceed with the following steps to download and extract the Kafka 
binaries into dedicated folders within the home directory of your kafka user.

1. First, create a directory called `Downloads` in `/home/kafka` to serve as 
the storage location for your downloads.
2. Utilise the curl command to download the Kafka binaries.
3. Create a directory named `kafka` and navigate to this newly created 
directory. This directory will act as the base directory for your Kafka 
installation.
4. Extract the downloaded archive using the tar command. Ensure that the 
contents of the archive are extracted directly into `~/kafka/` by specifying 
the `--strip 1` flag.