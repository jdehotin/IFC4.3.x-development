IfcTextLiteral
==============
The text literal is a geometric representation item which describes a text
string using a string literal and additional position and path information.
The text size and appearance is determined by the _IfcTextStyle_ that is
associated to the _IfcTextLiteral_ through an _IfcStyledItem_.  
  
The text string is placed within the planar extent (the box) defined within
the subtype _IfcTextLiteralWithExtent_.  
  
> NOTE  Entity adapted from **text_literal** defined in ISO10303-46  
  
> HISTORY  New entity in IFC2x2.  
  
{ .change-ifc2x3}  
> IFC2x3 CHANGE  The _IfcTextLiteral_ has been changed by removing _Font_ and
> _Alignment_.  
  
{ .deprecated}  
> DEPRECATION  The use of _IfcTextLiteral_ is deprecated and it will be made
> abstract.  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcpresentationdefinitionresource/lexical/ifctextliteral.htm)

