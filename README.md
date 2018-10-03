# docx4j-export-FO
Export docx to PDF via XSL FO, using FOP

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.docx4j/docx4j-export-fo/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.docx4j/docx4j-export-fo)

Up until docx4j v3.3.0, this was part of docx4j itself.  From 3.3.0 onwards, it is an optional separate sub-project.

docx4j will use export-FO automatically if it finds it in your classpath.

## Java 6 support

v6.x series is the last which will support Java 6.

## Alternatives

In docx4j v3.3.0, the default PDF Converter is an eval version of Plutext's commercial renderer, which offers
much better fidelity and performance.  For more on this, please see https://converter-eval.plutext.com/

