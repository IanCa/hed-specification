## Changes proposed for 8.2.0

* Added `Property/Agent-property/Agent-trait/Race` and `Property/Agent-property/Agent-trait/Ethnicity`.
Did not specify any children or the takesValue child. Expect users are going to extend or use a `Label` until
a BIDS or another standard specifies details.
* Added `Relation/Logical-relation`, `Relation/Logical-relation/And`, and `Relation/Logical-relation/Or`.
* Updated the descriptions of the major `Relation` subgroups to include idea of focus.
* Added `Relation/Spatial-relation/Left-center-of` and `Relation/Spatial-relation/Right-center-of`
and updated the `relatedTags` of other spatial relationship tags.
* Added a `deprecated` schema attribute to indicate that this tag should no longer be used.
  This boolean attribute was added to provide a schema evolution path without removing any tags.
* Corrected missing open parenthesis in description for `Relation/Connective-relation/Performed-using`.