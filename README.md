Testing pod rendering in github:

aa.win32, bb.pod and cc.win32, dd.win32 all contain the exact some content.

.gitattributes contains:

	cc.win32 linguist-language=Pod
	dd.win32 linguist-language=Pod linguist-documentation

I would've expected(/hoped) that this would be enough to make rendering
of cc.win32 and bb.pod the same but it isn't. :-(

The .gitattribute does appear to have an effect since aa.win32 and cc.win32
are rendered differently.

ee.win32 is yet another test and uses a vim modeline with 'syntax=pod'.
