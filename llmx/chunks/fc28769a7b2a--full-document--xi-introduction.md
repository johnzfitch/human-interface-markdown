---
chunk_index: 3933
ref: "fc28769a7b2a"
id: "fc28769a7b2a5844a4cdcd92007245c302b06281f9e987a2edb99eaf7ac5065b"
slug: "full-document--xi-introduction"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [43, 186]
token_estimate: 2006
content_sha256: "ed6221a019040ba90c92bfb8030d510c6a0ec6b26ab4a2f6ad2ea17344c320e6"
compacted: false
heading_path: ["NeXTSTEP<sup>™</sup> USER INTERFACE GUIDELINES","*Contents*","**xi Introduction**"]
symbol: null
address: null
asset_path: null
---

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