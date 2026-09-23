# Saxon Regular Expressions translator code used by Elemental

[![Java 8](https://img.shields.io/badge/java-8+-blue.svg)](https://adoptopenjdk.net/)
[![License](https://img.shields.io/badge/license-MPL%201.1-blue.svg)](https://opensource.org/licenses/MPL-1.1)
[![Maven Central](https://img.shields.io/maven-central/v/xyz.elemental.fork.saxon/saxon-regex-translator?logo=apachemaven&label=maven+central&color=green)](https://central.sonatype.com/search?namespace=xyz.elemental.fork.saxon)

This is a slight modification of the regular expressions code from the package `net.sf.saxon.functions.regex` of Saxon-HE 9.4.0-9.
The original code is Copyright Saxonica Limited and is released by them under the [Mozilla Public License 1.1](https://www.mozilla.org/en-US/MPL/1.1/).

Thanks to [Saxonica](https://www.saxonica.com/) for the excellent [Saxon](http://saxon.sourceforge.net/).

This modified code is used by Elemental in its implementation of the XQuery functions: `fn:analyze-string`, `fn:matches`, `fn:replace`, and `fn:tokenize`.

The modifications:
 
1. change the package name of the classes (from `net.sf.saxon.functions.regex` to `org.exist.thirdparty.net.sf.saxon.functions.regex`),
2. added an MPL 1.1 license declaration to the files,
2. update the code for use with a newer Saxon dependency,
3. are released under the same Mozilla Public License 1.1.
