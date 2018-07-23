# compiler-track
A tool to track compiler versions in complex multi-language projects

# Precis

Given the increase in languages used in modern projects, especially in the web ecosystem, it has become impossible to use a single languages dependency management software to track the underlying dependencies of the project. For example in a Scala and Web projects the Scala file will depend on a certain scala compiler version being installed and the web project will require a certain version of Node.

Build files may be written in other languages (shell, Python, etc) which also have required versions.

To resolve this a tracking file needs to store at minimum the required compilers and potentially version information.

The intended target of this is a docker file or user wishing to set-up the correct environment for building. Therefore the file must be both human and machine readable.

For this pupose the ideal language is thus YAML.

# Specification

