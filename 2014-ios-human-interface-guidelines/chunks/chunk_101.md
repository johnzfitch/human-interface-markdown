<!-- Chunk 101 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 522 -->
An **activity** represents a system-provided or custom service—accessible through an activity view controller—that can act on some specified content.  
![](images/_page_155_Picture_3.jpeg)  
**API Note:** To learn more about defining an activity in your code, see *UIActivity Class Reference* ; to learn how incorporate an activity view controller into your app, see "Activity View [Controller"](#page-157-0) (page 158).  
#### An **activity**:  
● Is a customizable object representing a service that an app can perform while users are in the app  
● Is represented by an icon that looks similar to a bar button icon  
![](images/_page_156_Picture_2.jpeg)  
Users initiate a service by tapping its activity icon in the activity view controller. In response, the activity either performs the service immediately, or if the service is complicated, it can request more information before performing the service.  
Use an activity to give users access to a custom service that your app can perform. Note that iOS provides several built-in services, such as Print, Twitter, Message, and AirPlay. You don't need to create a custom activity that performs a built-in service.  
**Create a streamlined template image that represents your service.** A template image is an image that iOS uses as a mask to create the final icon that users see. To create a template image that looks good in the final icon, follow these guidelines:  
- Use black or white with appropriate alpha transparency.
- Don't include a drop shadow.
- Use antialiasing.  
An activity template image should be centered in an area that measures about 70 x 70 pixels (high resolution).  
**Craft an activity title that succinctly describes your service.** The title is displayed below the activity's icon in the activity view controller. A short title is best, because it looks better onscreen and it's easier to localize. When a title is too long, iOS first shrinks the text and then—if the title is still too long—truncates it. In general, it's a good idea to avoid including your company or product name in the activity title.