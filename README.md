OSIS Bibles
===========

A collection of freely licensed translations of biblical text in OSIS formt.

More information on OSIS available here: http://www.bibletechnologies.net/


Contributing
===========

Please use the following naming convention (lowercase):

/[language code]/[osisIDWork].xml

Additionally "_whatever" may be appended to the file base name if needed for clarification. For example "kjv_strongs.xml" for Strong's study version. "kjv_nt.xml" for New-Testament-only (if there is not already a osisIDWork for this specific version).

Other Formats
===========

OSIS version split into seperate XML files by book:

https://github.com/lookitscook/osis-bibles/tree/split

(for use with github hosted ajax applications, etc.. so entire text does not need to be loaded up front)

If there is interest in hosting other formats additional branches can be created and the project re-organized accordingly. 

JSON
===========
Generated from XML.
Texts are in UTF-8 (sans BOM)

Book with one chapter is still an array (not reduced to an object).

Double quotes (") are escaped, see Mark.13.21

Path to text is:
_Bible.osis[0].osisText[0].div[0].chapter[0].verse[0]._text

"Au commencement, Dieu créa les cieux et la terre."

_Bible.osis[0].osisText[0].div[0].chapter[0].verse[0].osisID._value

"Gen.1.1"
