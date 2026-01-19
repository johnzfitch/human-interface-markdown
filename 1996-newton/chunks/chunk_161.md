<!-- Chunk 161 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 505 -->
To receive items, a user can pick a routing action from the In Box's Receive picker, which pops up when the user taps the Receive button. The Receive picker lists all Newton transports capable of receiving data items from external sources. Figure 7-18 shows a sample Receive button and picker.  
**Figure 7-18** The Receive picker lists the transports available for receiving  
![](images/_page_230_Picture_5.jpeg)  
When a user picks a routing action from the Receive picker, the corresponding transport connects to its source of incoming data. Each transport may have a different procedure for connecting. For example, the fax transport displays a slip asking whether the user wants to wait for a fax call or connect manually. An e-mail transport might display a slip in which a user sets up the phone number to dial, specifies what items to retrieve, and taps a Connect button when ready. The beam transport tries to connect immediately. [Figure 7-19](#page-231-0) shows the connection slips for the fax transport and an example e-mail transport.  
Some transports can connect automatically when the system detects incoming data items for them. For example, the beam transport can connect automatically to another Newton device that is sending through its beam transport. A transport that can connect automatically should allow users to disable automatic connection by setting preferences in the In/Out Box application, as described in ["Transport Preferences" on page 7-32.](#page-237-0)  
<span id="page-231-0"></span>**Figure 7-19** Connection setup varies by transport  
![](images/_page_231_Figure_3.jpeg)  
![](images/_page_231_Figure_4.jpeg)  
Built-in fax transport displays this slip  
An e-mail transport might display this slip  
A transport can also allow users to schedule times when it automatically connects and receives incoming items. Users schedule connect times by setting preferences in the In/Out Box application, as described in ["Transport](#page-237-0)  [Preferences" on page 7-32](#page-237-0).