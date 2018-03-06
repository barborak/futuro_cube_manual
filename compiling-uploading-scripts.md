## Compiling, uploading and erasing scripts

Scripts can be uploaded into two destinations:

* [Ram](compiling-uploading-scripts/ram.md)  - suitable for smaller scripts and quick tests. CODE and DATA segments share the same space in RAM, but content of the FLASH kept intouched
* [Flash](compiling-uploading-scripts/flash.md) - larger scripts needs to be uploaed into FLASH, during the development process the script after compilation is usually immediately uploaded into FLASH and STARTED. See [Compile and Run Hello World](/hello-world/compile-and-run-hello-world.md).This is has one minor disadvantage, if there are some games or scripts previously updated using RFCSuite, they will be erased. Other option is not to upload after compilation and use RFCSuite to correctly add the scripts into FLASH image, but this way slows development.

## Available memory space

```plantuml

bob->alice
alice->bob



```



