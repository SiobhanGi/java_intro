Java (compile then link execute)

does not have the dependance to the platform as compiled languages do.

Java doesn't create an object file. The Java compiled creates a bytecode which is
essentially an object file for a virtual machine.

The compiler is called JVM (Java Virtual Machine)

You can write java on any platform and use a jvm compiler to generate the bytecode but this bytecode is not an executable. To execute bytecode you need an interpreter called java. Every platform has its own java interpreter which will address the platform specific issues.

It is possible to get java to run faster by compiled the bytecode into an executable but this will make it platform specific.

Java is one of the first library based languages.
