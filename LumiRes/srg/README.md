# Changes
This is the list of changes from the original mapping.
## Class Names
### Replace Packet Class Names
~~~regex
[S,C][0-9][0-9A-F]Packet -> [S,C]Packet
~~~
## Field Names
### Replace player field in new mcp_stable map to thePlayer like old map
field_71439_g and some other fields are always called thePlayer