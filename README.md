# Specification Template

This is the working area for the Trust over IP specification template.

* [Editor's Copy](https://trustoverip.github.io/specification-template/)

#### Contributing

All Trust Over IP Foundation Technical Stack Working Group contributions are done so under the following licenses:

* [Patent and Copyright Grants](CONTRIBUTING.md)
* [Source Code](SOURCE_CODE.md)

#### Licensing

All Trust Over IP Foundation Technical Stack Working Group deliverables are published under the following licenses:

* [Patent and Copyright Grants](LICENSE.md)
* [Source Code](SOURCE_CODE.md)

#### Getting involved

Join a community of individuals and organizations solving the toughest technical and human-centric problems in digital trust. https://trustoverip.org/get-involved/membership/


#### SpecUp Impacts

The shift to using SpecUp has some immediate impacts:

* Finding "the definition" via the published repository is not simple as there is no index of terms. 
* Explanatory text in a term requires a simpler definition to be added for use by `ref:` and `xref:` tags. For example the following required the addiiton of a simple `authentication` term in order to maintain the explanatory text in the heading: 
```
[[def: authentication (of a user; process; or device), authentication]]:
~ Verifying the [[ref: identity]] of a user, process, or device, often as a prerequisite to allowing access to resources in an information system.
``` 