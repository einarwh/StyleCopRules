SaneCop
=======

StyleCop settings intended to help rather than harm your project.

# Assessment of rules


## Documentation Rules (SA1600-)

### Sane

* [SA1603: DocumentationMustContainValidXml](http://www.stylecop.com/docs/SA1603.html)
  Worthwhile checking, there is no reason to ever accept invalid XML.

### Insane

* [SA1600: ElementsMustBeDocumented](http://www.stylecop.com/docs/SA1600.html)
  No, I don't think they must. Mandatory documentation of all code elements inevitably leads to autogeneration of documentation based on the code elements themselves - hence the documentation can obviously not tell you anything not already in the code, obviating the need for the documentation in the first place. The result is "undocumentation" that clutters the code and harms readability.


## Layout Rules (SA1500-)

### Sane

### Insane


## Maintainability Rules (SA1400-)


## Naming Rules (SA1300-)


## Ordering Rules (SA1200-)


## Readability Rules (SA1100-)


## Spacing Rules (SA1000-)
