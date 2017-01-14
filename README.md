# js-NodeIterator

The NodeIterator.pointerBeforeReferenceNode read-only property returns a Boolean flag that indicates 
whether the NodeFilter is anchored before (if this value is true) or after (if this value is false) the anchor node 
indicated by the NodeIterator.referenceNode property.
The NodeIterator.referenceNode read-only returns the Node to which the iterator is anchored; 
as new nodes are inserted, the iterator remains anchored to the reference node as specified by this property.


NodeFilter.FILTER_(ACCEPT:1 ⌇ REJECT:2 ⌇ SKIP:3);
/123/

NodeFilter.SHOW_(ALL:-1 ⌇ ELEMENT:1 ⌇ ATTRIBUTE:2* ⌇ TEXT:4 ⌇ CDATA_SECTION:8 ⌇ ENTITY_REFERENCE:16 ⌇ ENTITY:32* ⌇ PROCESSING_INSTRUCTION:64 ⌇ COMMENT:128 ⌇ DOCUMENT:256 ⌇ DOCUMENT_TYPE:512 ⌇ DOCUMENT_FRAGMENT:1024 ⌇ NOTATIONS:2048*);
/-1|1|2|4|8|16|32|64|128|256|512|1024|2048/
