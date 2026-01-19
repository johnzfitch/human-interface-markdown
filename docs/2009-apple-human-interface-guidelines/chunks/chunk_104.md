<!-- Chunk 104 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 603 -->
The trackpad offers an alternative way to interact with applications on portable computers. People use their fingers on the trackpad to perform actions they might otherwise perform using a mouse, such as:  
- Move the pointer
- Select or activate user interface elements
- Scroll in either the active or a background window
- Display a contextual menu  
In addition to such actions, a Multi-Touch trackpad can support gestures that have more complex behaviors, such as:  
- Pinch open and pinch close—zooms in or out on the active image or view under the pointer
- Rotate—rotates the active view under the pointer in the direction of the user's movement
- Three-fingerswipe—navigatesforward or backward through a set of views or pagesin the active window
- Four-finger swipe—activates and deactivates Exposé or switches among running applications  
If you decide to support Multi-Touch gestures in your application, keep the following guidelines in mind to provide a great user experience:  
- **Respond to gestures in a consistent way so that users know what to expect**. In particular, avoid redefining the meaning of standard gestures in your application.
- **Handle gestures as responsively as possible**. Gestures should heighten the user's sense of direct manipulation and provide immediate, live feedback. To achieve this, aim to perform relatively inexpensive operations for the duration of the gesture.
- **Ensure that gestures apply to user interface elements of the appropriate granularity**. Gestures are usually most effective when they target a specific object or view in a window, because such views are usually the focus of the user's attention. Start by identifying the most specific object or view the user is likely to manipulate and make it the target of a gesture. Make a higher level or containing object a gesture target only if it makes sense in your application.
- **Define custom gestures cautiously**. A custom gesture can be difficult to discover and remember. If a custom gesture seems gratuitous, users are likely to avoid using it. If you feel you must define a custom gesture, be sure to make it easy to perform and easy to distinguish from standard gestures.  
<span id="page-98-2"></span><span id="page-98-0"></span>**Note:** Users can disable gestures in Trackpad preferences, so you should not rely on the availability of a specific gesture as the only way to perform an action.