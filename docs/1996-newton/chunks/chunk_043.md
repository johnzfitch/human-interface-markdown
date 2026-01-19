<!-- Chunk 43 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 855 -->
Every container view is framed by a border. (A border is not visible if its view fills the screen.) Primarily, a view's border serves to demarcate what's in the view and what's not. Secondarily, certain borders identify special types of container views.  
In general, Newton views are rectangular and have rounded corners. Use square-cornered borders only when you have a specific need for a particular look.  
A view's border is not visible if the view completely covers the screen. For example, a MessagePad 120 user does not see the border of a view that measures 240 × 320 pixels. The view has a border, but it is off-screen.  
#### Matte Border 2  
The most common type of view border, called a **matte border,** consists of a thick gray band edged on the outside by a thin black line**.** Users expect views with matte borders to be movable (see ["Moving a View" on page 2-33](#page-76-0)). Figure 2-4 shows the matte border.  
**Figure 2-4** A matte border indicates a movable view  
![](images/_page_49_Picture_9.jpeg)  
On an Apple MessagePad a standard matte border is five pixels thick with a corner roundness of five pixels and an inset of one pixel.  
#### <span id="page-50-0"></span>Striped Border 2  
A border made of pairs of short, slanted lines edged by a thin black rectangle is used around views known as **routing slips** (see ["Routing Slips" on](#page-217-0)  [page 7-12](#page-217-0))**.** It's no accident that this border looks something like the border traditionally printed on airmail envelopes, because routing slips are analogous to postal envelopes. Figure 2-5 shows a routing slip border.  
**Figure 2-5** A striped border suggests routing  
![](images/_page_50_Picture_5.jpeg)  
The paired short lines in a striped border slant 45 degrees to the right.  
#### Wavy Border 2  
A view with a heavy black wavy border is called an **alert box.** It contains an important message that a user must acknowledge. There are two types of alert boxes; they are described in ["Notification Alerts" on page 2-17](#page-60-0) and ["Confirmation Alerts" on page 2-18](#page-61-0). [Figure 2-6](#page-51-0) shows the wavy border of an alert box.  
How Views Look **2-7**  
<span id="page-51-0"></span>**Figure 2-6** An alert box has a thick wavy border  
![](images/_page_51_Picture_3.jpeg)  
#### Plain Border 2  
For simplicity, some container views require a plain black border made of medium-weight lines. Figure 2-7 shows examples of views with plain borders.  
**Figure 2-7** Some views need the simplicity of a plain border  
![](images/_page_51_Picture_7.jpeg)  
![](images/_page_51_Picture_8.jpeg)  
#### Drop Shadows 2  
It's possible to add a drop shadow to a view's bottom and right borders, but this ersatz 3D look is not appropriate for Newton applications. Don't use drop shadows just because you like the way they look or because you want to make a Newton application look like a personal computer application. Although you shouldn't use drop shadows, you can use another type of shadow that tells users something about a view. For example, a shadow  
<span id="page-52-0"></span>reinforces the notion that there are two parts to a routing slip—an outer part above the shadow and an inner part below it. Figure 2-8 shows acceptable and unacceptable uses of shadows in the Newton interface.  
**Figure 2-8** Sparing use of some types of shadows is OK  
![](images/_page_52_Figure_4.jpeg)