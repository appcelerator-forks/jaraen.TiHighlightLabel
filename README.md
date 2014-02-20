
TiHighlightLabel Widget and demo project
=======

This Titanium + Alloy project demonstrates the use of AttributedString component introduced in Titanium 3.2 for iOS7.

TiHighlightLabel is a normal label that allows to highlight dynamically part of its text.

![Screenshot](https://raw2.github.com/jaraen/TiHighlightLabel/master/screenshot.png "TiHighlightLabel")

It implements a search method to easily highlight all the occurrences in its text.

All its behaviour is like a normal label. Look into index.tss to see an example on how to style the label and the highlighted parts and index.xml to see how to use it in a view.

Note that for initializing the label you can set the text property in your tss file. But for initializing or setting the text from the controller, you need to access to the widget's view, which means call to $.yourlabel.getView().text = 'new value';


License
===
Code and project under MIT License

Original code, documentation and example by Javier Rayon - 2014
twitter: @jrayon
http://www.criteriastudio.com
javier at criteriastudio ' com 