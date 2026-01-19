<!-- Chunk 111 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 250 -->
A **gradient button** performs an instantaneous action related to a view, such as a source list.  
![](images/_page_183_Picture_5.jpeg)  
**API Note:** To define a gradient button in your code, use the setBezelStyle: method of NSButtonCell with NSSmallSquareBezelStyle as the argument.  
#### A gradient button:  
- Can have push-button, toggle, or pop-up menu behavior
- Contains only images; in particular, a gradient button doesn't contain text  
Use a gradient button to offer functionality that's directly related to a source list or other view,such as a browser or column view.  
Because the function of a gradient button is closely tied to the view with which it's associated, there's little need to describe its action in a label.  
<span id="page-183-1"></span>When possible, use system-provided images, such as the Action and the Add images, because their meaning is familiar to users. For more information on the system-provided images, see [System-Provided](#page-328-0) Images (page 329).