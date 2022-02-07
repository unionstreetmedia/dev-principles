# Use Descriptive Names and Comments

Classes, functions, and methods are given descriptive comments to describe use case and include
expected inputs and outputs.

Good naming conventions should be used for methods, variables, parameters and classes.

Descriptive comments should never replace good naming conventions for methods, variables,
parameters or classes. When used in conjunction someone new to the codebase should be able to use
existing code without stepping though every line of the method.

## Good Example:

```
/**
* Schema module for use with MinimalListings objects, ex List View. Constructs JSON-LD structure to
* describe a listing (physical traits) or a listing related event (open house).
*
* @param object $listing | Intakes an object of MinimalListing
* @param object $type | Intakes an enumerated type to determine what is being described.
* Ex: physical, openHouse
*
* @return none | Echos output schema content directly to DOM
**/
private function renderMinimalSchemaListing( \RealEstate\MinimalListing $listing, SchemaType $type) {}
```

## Bad Example:

```
private function renderSchemaListingMinimal( \RealEstate\MinimalListing $l, int $t) {}
```

## Resources

This document uses inspiration from
[this article](https://hackernoon.com/how-to-write-clean-code-d557d998bb08) by Luan Nguyen
summarizing Robert C. Martin's approach to writing clean code.
