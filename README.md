## Open Journal of Astrophysics LaTeX document class file with the option to rotate tables!

Since OJAp does not support table rotation [by default](http://www.thphys.nuim.ie/staff/pcoles/openjournal.cls), I've merged \rotatetable commands into the OJAp template document class file. (Disclaimer: These commands are much simpler and less comprehensive/sophisticated than what's included in [AASTeX](https://journals.aas.org/aastex-v6-3-author-guide/).)

To rotate your table for an OJAp submission, set `\documentclass[]{openjournal_deluxetable}` and then use `\begin{rotatetable} .... \end{rotatetable}` where you would usually use deluxtable. (The multi-column alternative command is also supported.)

I've also made an **UNOFFICIAL** [Overleaf template](https://www.overleaf.com/read/wbccszxrgzbz#b84e18) available that includes this option. To have the added table functionality available, simply set your document class to "openjournal_deluxetable".

If you use this class file to rotate tables in a publication, please add a link to this repository in your acknowledgements.
