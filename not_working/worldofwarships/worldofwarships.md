World Of Warships

Tested on build from April 3rd 2019

Launch options used (if any):

Symptoms:
Crashes upon attempted launch

Remarks:
See logs

How to force dx9:

preferences.xml:
replace
<label>	GRAPHICS_API	</label>
<activeOption>	1	</activeOption>

with

<label>	GRAPHICS_API	</label>
<activeOption>	0	</activeOption>
