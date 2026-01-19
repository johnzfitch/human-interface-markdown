<!-- Chunk 261 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 744 -->
Each checkbox label should clearly imply two opposite states so it's clear what happens when the option is selected or deselected. Ifyou can't find an unambiguous label, consider usinga pair of radio buttons so you can clarify the states with two different labels.  
Checkbox labels should have sentence-style capitalization (see ["Capitalization](#page-135-0) of Interface Element [Labels](#page-135-0) and Text" (page 136) for more on this style), unless the state or value is the title of some other element in the interface that is capitalized.  
When a user selection comprises more than one state, use a dash in the appropriate checkboxes. This symbol is consistent with the mixed-state indicator in menus, as described in "Using [Symbols](#page-169-0) in [Menus"](#page-169-0) (page 170).  
#### Checkbox Specifications  
**Control sizes**: The dimensions of the checkbox itself are fixed for each size, but you determine the length of the introductory label and checkbox label.  
**Label spacing and fonts**: Checkbox text (both the introductory label and control label) should be in a font that is proportional to the size of the control. The following fonts are supplied automatically by Interface Builder:  
#### **C HAPTER 1 5**  
Controls  
- Regular size: System font.
- Small: Small system font.
- Mini: Mini system font.  
If you display an introductory label on the same line as the first checkbox, use the following metrics to position it correctly:  
- Regular size: 8 pixels from the end of the label (the colon) to the control.
- Small: 6 pixels from the end of the label (the colon) to the control.
- <span id="page-287-1"></span>■ Mini: 5 pixels from the end of the label (the colon) to the control.  
<span id="page-287-0"></span>Be sure to align the baseline of the introductorylabelwith the baseline of the closest checkbox's label, as shown in Figure 15-25.  
**Figure 15-25** Checkbox label alignment  
![](images/_page_287_Picture_11.jpeg)  
If you display an introductory label above a group of checkboxes, leave 8 pixels between the label and the first checkbox.  
**Control spacing**: Typically, checkboxes are arranged vertically, because this arrangement makes it easier for users to distinguish one state from another. As described in ["Checkbox](#page-285-2) Usage" (page 286), you should align a set of independent checkboxes so that all appear to be at the same level. If one checkbox describes a state or action that depends on the state of another checkbox, you can indent the dependent checkbox below the controlling one.  
Use the following metrics when you lay out checkboxes in your window:  
- Regular size: 8 pixels between controls when stacked.
- Small: 8 pixels between controls when stacked.
- Mini: 7 pixels between controls when stacked.  
#### Checkbox Implementation  
Checkboxes are available in Interface Builder. To create one using Application Kit programming interfaces, create an NSButton object of type NSSwitchButton.