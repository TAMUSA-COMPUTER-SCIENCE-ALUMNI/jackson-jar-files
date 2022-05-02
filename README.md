# Jackson .jar Files

## What is the Jackson Library?

Jackson has been known as "the Java JSON library" or "the best JSON parser for Java". Or simply as "JSON for Java".

More than that, Jackson is a suite of data-processing tools for Java (and the JVM platform), including the flagship streaming JSON parser / generator library, matching data-binding library (POJOs to and from JSON) and additional data format modules to process data encoded in Avro, BSON, CBOR, CSV, Smile, (Java) Properties, Protobuf, TOML, XML or YAML; and even the large set of data format modules to support data types of widely used data types such as Guava, Joda, PCollections and many, many more (see below).

While the actual core components live under their own projects -- including the three core packages (streaming, databind, annotations); data format libraries; data type libraries; JAX-RS provider; and a miscellaneous set of other extension modules -- this project act as the central hub for linking all the pieces together.

A good companion to this README is the [Jackson Project FAQ](https://github.com/FasterXML/jackson/wiki/FAQ).

## Instructions

1. Download the repo .zip to your local machine
2. Unzip the file
3. Move the new folder's contents to your project folder
4. In Intellij, under 'File', click on the 'Project Structure' selection in the left column, select 'Libraries'
5. At the top of the center column, click on the '+' icon
6. Select 'Java' in the pop-up window
7. Use the pop-up window to navigate to the location of the new folder you previously moved into the project folder
8. Select all three files and click on 'Open'
9. The files should appear in the right column and a new file in the center column named 'jackson-annotations-2.13.2'
10. Click the 'Apply' button and then the 'Ok' button
11. In your project folder or module folder, create a new directory called 'test'
12. In the left column, select Modules and in the right column and ensure the checkbox to left of 'jackson-annotations-2.13.2' is checked and 'Compile' is selected in dropdown menu to the right
13. Click the 'Apply' button and then the 'Ok' button

## Jackon Documentation
* [Jackson Core](https://javadoc.io/doc/com.fasterxml.jackson.core/jackson-core/latest/index.html)
* [Jackson Annotations](https://javadoc.io/doc/com.fasterxml.jackson.core/jackson-annotations/latest/index.html)
* [Jackson Databind](https://javadoc.io/doc/com.fasterxml.jackson.core/jackson-databind/latest/index.html)
