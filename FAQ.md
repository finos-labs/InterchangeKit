# Favourite Anticipated Questions

### Why build a new library for XML?
The C and C++ XML libraries including libxml2, libexpat and Apache Xerces-c++ have issues with recruiting and retaining maintainers. A major source of maintainer load and frustration is reports of vulnerabilities (mainly denial of service lately) from memory management or access issues. Current memory-safe implementations in Rust, which will avoid at least some of the memory management issues affecting the C and C++ libraries, are currently limited in scope, and roxmltree and xml-rs are also experiencing maintainer churn.

### Why a FINOS project?
To ensure that the project has long term maintainers, we aim to build a community of contributors from organisations where XML data exchange is a creator of, or close to the creation of, value. Financial institutions, and maybe their regulators, fit this bill. This, admittedly bold, claim about where this project can endure where others have fizzled is based on:

- Observed patterns of how project maintainers have found successors. Of the projects listed above, libxml2, roxmltree and xml-rs are all maintained by people who build software on top of them.
- The idea that corporate engagement in open source is most secure when it aligns closely with the organisation’s creation of value

### Is "parity" with an existing library a useful notion?
Feature parity, or even building for compatibility with an existing Application Binary Interface (ABI), is not a great staring point for a porject in an of itself. Building to a standardised API  (libxml2 is standardised in ISO/IEC 23360-1) does, however, have some advantages. Two advantages are tied for first place - avoiding design overhead and ease of getting first adopters. A new project could spend ages figuring out what to build, or it could get on with building something which downstream projects could use. Those downstream projects will have their own suites of tests, and provide an opportunity for recruiting contributors.
