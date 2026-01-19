<!-- Chunk 3 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 3223 -->
#### **xi Introduction**  
| 1  | Chapter 1: A Visual Guide to the User Interface |
|----|-------------------------------------------------|
| 3  | An Application's Windows                        |
| 3  | Standard Windows                                |
| 4  | Panels                                          |
| 5  | Menus                                           |
| 6  | Miniwindows                                     |
| 6  | Application Icons                               |
| 7  | Controls                                        |
| 8  | Buttons                                         |
| 9  | Text Fields                                     |
| 9  | Sliders                                         |
| 10 | Color Wells                                     |
| 10 | Scrollers                                       |  
**11** Browsers and Selection Lists  
| 13 | Chapter 2: Design Philosophy                    |
|----|-------------------------------------------------|
| 14 | Basic Principles                                |
| 14 | Consistency                                     |
| 14 | User Control                                    |
| 15 | Modes                                           |
| 15 | Acting for the User                             |
| 15 | Naturalness                                     |
| 16 | Using the Mouse                                 |
| 17 | Action Paradigms                                |
| 17 | Direct Manipulation                             |
| 18 | Targeted Action                                 |
| 19 | Modal Tool                                      |
| 20 | Extensions                                      |
| 20 | Testing User Interfaces                         |
| 21 | Chapter 3: User Actions: The Keyboard and Mouse |
| 22 | How the Keyboard and Mouse Work                 |
| 22 | The Keyboard                                    |
| 22 | Modifier Keys                                   |
| 23 | Keyboard Alternatives                           |
| 24 | The Mouse                                       |
| 25 | Clicking                                        |
| 25 | Multiple-Clicking                               |
| 26 | Dragging                                        |
| 26 | Pressing                                        |
| 26 | Mouse Responsiveness                            |
| 26 | Left and Right Orientation                      |
| 27 | Selection                                       |
| 27 | Dragging to Select                              |
| 28 | . Clicking to Select                            |
| 28 | Multiple-Clicking to Select                     |
| 28 | Extending the Selection                         |
| 29 | Continuous Extension                            |
| 30 | Discontinuous Extension                         |
| 31 | How the Arrow Keys Affect a Text Selection      |  
| 32 | Implementing Special Keys                           |
|----|-----------------------------------------------------|
| 32 | Special Character Keys                              |
| 33 | Handling Arrow Characters                           |
| 33 | Special Command-Key Combinations                    |
| 34 | Choosing Keyboard Alternatives                      |
| 34 | Reserved Keyboard Alternatives                      |
| 35 | Required Keyboard Alternatives                      |
| 36 | Recommended Keyboard Alternatives                   |
| 36 | Creating Application-Specific Keyboard Alternatives |
| 37 | Choosing the Character                              |
| 37 | Using the Alternate Key                             |
| 38 | Determining the Action that Is Performed            |
| 39 | Implementing Mouse Actions                          |
| 39 | Reacting to Clicking                                |
| 40 | The First Click in a Window                         |
| 40 | When Dragging Shouldn't Imply Clicking              |
| 41 | When to Use Multiple-Clicking                       |
| 42 | Dragging from a Multiple-Click                      |
| 42 | How to Use Dragging                                 |
| 43 | Moving an Object                                    |
| 43 | Defining a Range                                    |
| 44 | Sliding from Object to Object                       |
| 44 | When to Use Pressing                                |
| 45 | U sing Modifier Keys with the Mouse                 |
| 46 | Managing the Cursor                                 |
| 46 | Changing the Cursor                                 |
| 47 | Hiding the Cursor                                   |
| 47 | Implementing Selection                              |
| 48 | When Discontinuous Selection Isn't Implemented      |
| 48 | The Range that Dragging Should Select               |
| 49 | Implementing the Modified Arrow Keys                |
| 49 | Control-Arrow Combinations                          |
| 49 | Shift-Arrow Combinations                            |
| 50 | Alternate-Arrow Combinations                        |
| 50 | Other Arrow Key Combinations                        |  
| 51   | Chapter 4: The Window Interface to Applications   |
|------|---------------------------------------------------|
| 52   | How Windows Work                                  |
| 53   | Window Order'                                     |
| 54   | Window Behavior                                   |
| . 55 | Reordering                                        |
| 56   | Moving                                            |
| 56   | Resizing                                          |
| 57   | Closing                                           |
| 58   | Miniaturizing                                     |
| 58   | Hiding and Retrieving Windows                     |
| 59   | Application and Window Status                     |
| 60   | The Active Application                            |
| 60   | Application Activation                            |
| 61   | Application Deactivation                          |
| 62   | The Key Window                                    |
| 63   | The Main Window                                   |
| 65   | How Windows Become the Key Window and Main Window |
| 65   | In the Active Application                         |
| 65   | When an Application Is Activated                  |
| 66   | The Results of Clicking in a Window               |
| 67   | Implementing Windows                              |
| 67   | Designing Windows                                 |
| 67   | Placing Windows                                   |
| 69   | Implementing Standard Windows                     |
| 69   | Choosing a Title                                  |
| 70   | Using the Resize Bar                              |
| 70   | Using the Miniaturize Button                      |
| 71   | Using the Close Button                            |
| 72   | Implementing Window and Application Status        |
| 72   | Choosing the Key Window                           |
| 73   | Activating an Application                         |
| 74   | Avoiding Activation when Dragging                 |  
| 75 | Chapter 5: Panels                           |
|----|---------------------------------------------|
| 76 | How Panels Work                             |
| 76 | Ordinary Panels                             |
| 77 | Attention Panels                            |
| 78 | Implementing Ordinary Panels                |
| 78 | Window Considerations                       |
| 78 | Using the Resize Bar                        |
| 78 | Using the Miniaturize Button                |
| 78 | Using the Close Button                      |
| 79 | Becoming the Key Window                     |
| 80 | Relinquishing Key-Window Status             |
| 80 | Exceptions to Ordinary Panel Behavior       |
| 80 | Persisting Panels                           |
| 81 | Floating Panels                             |
| 81 | Panels with Variable Contents               |
| 82 | Multiform Panels                            |
| 83 | Inspector Panels                            |
| 84 | Implementing Attention Panels               |
| 84 | Naming an Attention Panel                   |
| 85 | The Default Option in an Attention Panel    |
| 85 | Dismissing an Attention Panel               |
| 86 | Naming Buttons in an Attention Panel        |
| 87 | Optional Explanations in an Attention Panel |
| 88 | Standard Panels                             |
| 91 | Implementing the Close Panel                |
| 92 | Implementing the Find Panel                 |
| 93 | U sing the Help Panel                       |
| 95 | Implementing the Info Panel                 |
| 95 | U sing the Link Inspector Panel             |
| 96 | U sing the Open Panel                       |
| 96 | Implementing the Preferences Panel          |
| 97 | Implementing the Quit Panel                 |
| 98 | Using the Save Panel                        |  
| 99  | Chapter 6: Menus                        |  |
|-----|-----------------------------------------|--|
| 100 | How Menus Work                          |  |
| 100 | The Main Menu                           |  |
| 101 | Bringing the Main Menu to the Cursor    |  |
| 102 | Submenus                                |  |
| 103 | Keeping a Submenu Attached              |  |
| 103 | Tearing Off an Attached Submenu         |  |
| 104 | Removing a Submenu from the Screen      |  |
| 105 | Commands                                |  |
| 106 | Implementing Menus                      |  |
| 106 | Designing the Menu Hierarchy            |  |
| 107 | Choosing Command Names                  |  |
| 107 | Commands that Perform Actions           |  |
| 108 | Commands that Bring Up Panels           |  |
| 109 | Commands that Bring Up Submenus         |  |
| 109 | Commands that Bring Up Standard Windows |  |
| 109 | Sample Command Names                    |  |
| 110 | Disabling Invalid Commands              |  |
| 110 | Graphical Devices in Menu Commands      |  |
| 111 | Standard Menus and Commands             |  |
| 111 | The Main Menu                           |  |
| 114 | Adding to the Main Menu                 |  |
| 115 | The Info Menu                           |  |
| 116 | The Document Menu                       |  |
| 117 | Performing an Implicit New Command      |  |
| 118 | Uneditable Documents                    |  |
| 118 | The Edit Menu                           |  |
| 120 | The Paste As Menu                       |  |
| 120 | Checking Spelling                       |  |
| 121 | The Link Menu                           |  |
| 123 | The Find Menu                           |  |
| 124 | The Format Menu                         |  |
| 125 | The Font Menu                           |  |
| 128 | The Text Menu                           |  |
| 129 | The Windows Menu                        |  |
| 130 | The Services Menu                       |  |
| 131 | Providing Services                      |  |
| 132 | Adding a Tools Menu                     |  |  
| 133 | Chapter 7: Controls                                  |
|-----|------------------------------------------------------|
| 135 | Buttons                                              |
| 135 | How Buttons Work                                     |
| 136 | Buttons that Bring Up Lists                          |
| 136 | Pop-Up Lists                                         |
| 137 | Pull-Down Lists                                      |
| 137 | Implementing Buttons                                 |
| 137 | Choosing the Button's Result                         |
| 138 | Choosing the Button's Image or Label                 |
| 140 | Changing the Button's Appearance during a Click      |
| 141 | Implementing Pop-Up and Pull-Down Lists              |
| 142 | Implementing Link Buttons                            |
| 142 | Implementing Stop Buttons                            |
| 143 | Text Fields                                          |
| 145 | Sliders                                              |
| 146 | Color Wells                                          |
| 147 | Scrollers                                            |
| 148 | How Scrollers Work                                   |
| 148 | The Knob and Bar                                     |
| 149 | The Scroll Buttons                                   |
| 150 | Automatic Scrolling                                  |
| 150 | Fine-Tuning Mode                                     |
| 150 | Implementing Scrollers                               |
| 152 | Browsers and Selection Lists                         |
| 153 | Choosing the Appropriate Control                     |
| 153 | Controls that Start Actions                          |
| 154 | Controls that Show State                             |
| 154 | Displaying a Single Option                           |
| 154 | Displaying a Group with an Unrestricted Relationship |  
155 Displaying a Group with a One-of-Many Relationship