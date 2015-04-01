These tests are based on [Best Practices by SSB BART Group](https://www.webaccessibility.com/) and on Level A and Level AA Success Criteria of the Web Content Accessibility Guidelines (WCAG) 2.0, W3C Recommendation, 11 December 2008, http://www.w3.org/TR/WCAG20/, as proposed by the U.S. Access Board, http://www.access-board.gov/sec508/refresh/draft-rule.htm.This checklist is inclusive of the Technical Standards of Subpart B of Section 508 of the Rehabilitation Act of 1973, as amended (29 U.S.C. 794d), http://section508.gov/index.cfm?fuseAction=stdsdoc.

## Test Case ID 1: Ensure audio does not disrupt text to speech functionality of assistive technologies.
Ensure controls that start audio do not speak when actuated so that audio plays without interruption. Ensure audio playback volume is lowered when text to speech is speaking

## Test Case ID 2: Ensure audio information is not the only method used to indicate completion or error
1.	Test application with volume muted. Are you able to determine all functionality visually?
2.	Test with sound not muted. Are there sounds used in the application? Are these sounds redundant for other visual clues?

## Test Case ID 3: Ensure visual multimedia content is sufficiently described in the audio portion of the multimedia
Verify the audio accurately describe the visual cues in the video. Verify that visual specific language such as “as seen here”, “this chart”, or “this image”, also supplies detailed audio descriptions of the subject. Verify that audio descriptions are synchronized with the video. If a secondary version of the multimedia is provided with a special audio track, verify that this can be activated from the same module that launches the multimedia and that the method of activation meets all relevant accessibility best practices for the media type.

## Test Case ID 4: Provide a text transcript for audio only presentations
Activate the application. Locate all audio-only media. Verify that the page where the audio resides provides a link or similar method to access a text transcript. Verify that the transcript matches the audio, including all narration, identification of each speaker and indication of any pauses, sounds or other non-decorative audio cues.
## Test Case ID 5: Ensure color and text formatting are not the sole means of communicating information
Activate the application. Locate objects, images, or elements that use color. Determine if color is the sole means of communicating information. Verify that there is a visual means of getting the same information that is in the color
## Test Case ID 6: Ensure color and text formatting are not the sole means of communicating selection
Check that a selected item is announced as selected using assistive technologies and a checkmark, bold font or other non-color method visually indicates selection.
## Test Case ID 7: Ensure content that provides meaning through color, also conveys this meaning without color, directly in the content, on-screen, and without additional user interaction
Activate the application. Locate objects, images, or elements that use color. Determine if color is the sole means of communicating information. Verify that there is a visual means of getting the same information that is in the color
## Test Case ID 8: Ensure text and images of text provide sufficient color contrast
Open the module in the application. Take a screen shot of the module. Email or sync the picture. View the element within the page. Determine the foreground and background color of the element. Use an eye dropper tool to obtain the color values for the background and foreground colors. Utilize the color contrast analyzer tool to determine if contrast is sufficient to determine if the color contrast requirements are met. Verify the luminosity requirements are met.
## Test Case ID 9: Ensure addition and removal of on-screen components are properly exposed to assistive technology
Interact with an object, element, or control that causes the content on the page to update without going to a whole new page. Verify that the content that was updated appears below the item that triggered the update in the reading order. Verify that the addition or removal was announced either by the controlling element or automatically when the content was added or removed.
## Test Case ID 10: Ensure animation content is sufficiently described in audio or text
Activate the application with an external keyboard. Determine if there are any splash screens, non-system pop-up dialogs, or lightboxes. Verify the following for all:
1.	Ensure they fit on the mobile screen. Or can be scrolled if needed.
2.	Focused when opened on user initiation
3.	The Keyboard is navigable.
4.	Prevent keyboard access of items behind the modal pop-up.
5.	Can be dismissed via the keyboard.
## Test Case ID 11: Ensure assistive technologies are aware of content changes in real time.
Ensure that all on-screen changes can be detected by a screen reader:
1.	Activate the application with the screen reader
2.	Gain focus on the individual object, element, or controls.
3.	Verify that the announced item label matches the on-screen text or contains additional supplementary information to assist with nonvisual access of the item.
4.	Verify that the state of the element is announced properly.
5.	If applicable, toggle the state of the item and verify that the screen reader announces the correct state change.
## Test Case ID 12: Ensure auto-updating dynamic content can be paused, stopped, or hidden
Activate the application. Determine if the screen contains dynamically updating, moving, blinking scrolling content or animation. If so, determine if there are controls to stop, hide, pause, or control the content. Verify that the controls correctly control the media in the indicated fashion. Verify that these controls can be accessed via assistive technology and that the dynamic content can be controlled using assistive technology. Verify that animated content that is decorative does not last for more than five seconds
## Test Case ID 13: Ensure elements blink or flash in a safe threshold
Open the Flash/Flex application. Does the movie contain flashing or blinking elements? Determine the speed in which the elements blink. Count the number of times the element blinks within 10 seconds by setting a timer and then counting or by having someone assist you with timing the duration of 10 seconds while you count. Divide the number of blinks by 10 (the number of seconds). Ensure this number is not greater than three. If the flash rate is greater than three, calculate the square number of pixels in the Flashing area and ensure it is less than 21,824 (if the application is designed to be viewed by large audiences other than the web the number of pixels must calculated manually). If the size is larger than the allowed threshold and the element flashes more than three times per second then use the tool.
## Test Case ID 14: Ensure screen transition and decorative animation settle within 5 seconds
Activate the application. Determine if the screen contains dynamically updating, moving, blinking scrolling content or animation. If so proceed to the next step. Time the screen transitions to ensure that all content is fully rendered and settled within 5 seconds of the new screen first appearing.
## Test Case ID 15: Provide a non-animated method to step through/control animation
Determine if an application uses animation to convey/display information. If the animation is used to display information, is the information provided in a generally stationary text-based form? Does content, scroll text, contain moving arrows and characters to describe actions such as workflow, or contain slides—text/images—that appear then disappear followed by additional text/images?
## Test Case ID 16: Ensure error messages are in a platform specific alert or focus is moved to the error message after submit
Activate the application. Trigger an alert or an error in the application, such as a time out, update notice, error contacting the server, or other application level errors or alerts. Verify that the alerts or error notifications appear.
## Test Case ID 17: Provide a clear indication of errors
Activate the application. Trigger an alert or error on an object, element, or control in the application and submit the form. Determine if the object, element, or control provides error messages that:
1.	Clearly identify specific fields in error
2.	Clearly identify the reason the fields are in error
3.	Clearly identify how to address the error for each field
## Test Case ID 18: Provide a consistent implementation of error and alert mechanisms
Trigger the error state on multiple forms within the test set. Determine if the forms share a consistent method of indicating an error.
## Test Case ID 19: Provide error prevention for legal commitments and financial data
Activate the application. Locate any pages that involve legal commitments or financial data transactions. If so, determine if one of the following error prevention methods are used:
1.	The submission is reversible
2.	The submission is checked for errors
3.	The submission is confirmed by the user
## Test Case ID 20: Provide suggestions for error messages when known
Activate the application. Trigger an error on an object, element, or control requiring a value by not entering a value or by entering an invalid value. If so, verify the form contain errors that are detected automatically. Verify that suggestions are given for how to enter correct values either prior to or after the value is entered.
## Test Case ID 21: Ensure all elements and controls can receive focus
Activate the application with a screen reader. Verify that each actionable element can be navigated to directly. Verify that each actionable element can be navigated to using the screen reader input device and/or mechanism.
## Test Case ID 22: Ensure content or focus is not changed when focus changes occur
Verify you can select all radio buttons in a group without focus shifting. Verify you can tab to all fields without focus shifting once you have reached the field. Verify you can tab to all fields without new windows opening up. Verify you can fill out a field without the focus shifting when you reach the end of the field.
## Test Case ID 23: Deprecated
This test case is no longer used.
## Test Case ID 24: Ensure focus is not forcibly shifted on input
Activate the application. Navigate through the active objects, element, or controls and make sure you arrow up/down in combo boxes or lists without focus shifting. Verify if an input causes a new window to appear. Verify an input causes a form to be submitted. Verify that you can enter text into an input field such as a telephone number field without focus shifting to another field.
## Test Case ID 25: Ensure navigation and input focus is accurately indicated visually
Navigate through the active on-screen components. For each active element that receives focus, verify where the text input location is. Verify that the focus location is indicated at all times and follows traversal of the user interface. Verify that the object, element, or control that has focus is indicated in a clear, visually distinguishable manner that meet the color contrast requirements outlined in this document.
## Test Case ID 26: Ensure elements are sufficiently described
Navigate to an action element such as a toggle button. Verify that the following can be determined:
1.	The current role/type of the control such as “button”
2.	The name of the control
3.	The state of the control such as “checked” or “not checked”
4.	The value of a control such as an edit field
## Test Case ID 27: Ensure form field constraints are clearly indicated
Open the application using a screen reader. Navigate through the form. Verify that field constraints are announced with the label of the field or in the hint text.
## Test Case ID 28: Ensure multi-part controls are accessible and provide context
Activate the application with voice output. Locate any forms within the screen. Determine if one or more logical groupings exist within the form. For each grouping, navigate to each field in the group and verify that the group name is announced prior to the field’s label. Verify each group of items, verify that the methods of interacting with the grouped controls works as expected with alternative input methods.
## Test Case ID 29: Provide explicit labels for all form elements
Activate the application with voice output running. Locate form fields and gain focus on the individual form field. Verify that all form fields have a visual label. Verify that all form field labels are announced by a screen reader
## Test Case ID 30: Enhancements that are provided for users with disabilities shall not be provided in a mutually exclusive fashion
Application functionality, input and output should be accessible to multiple disability types.
## Test Case ID 31: Ensure accessible usage of time based sessions
Application that times out after 20 seconds but displays a dialog at 19 minutes asking user if he/she needs additional time.
## Test Case ID 32: Ensure element role and state are correct
While navigating the user interface using assistive technologies the state and role should functional and visual role of the control.
## Test Case ID 33: Ensure non-decorative images provide informative alternative text
For all non-decorative images and controls made from images ensure that the accessible labels are concise and informative.
## Test Case ID 34: Provide textual equivalents for all non-text elements including sounds, and images.
Activate the application with voice output enabled. Identify any meaningful images, elements, or objects. Verify image and that the alternative that an equivalent alternative is provided for each meaningful is announced as expected.
## Test Case ID 35: Ensure changes in natural language are identified inline
Set the platform language. Activate the application with platform standard assistive technologies enabled. Verify that the application content is rendered in the currently selected system language.
## Test Case ID 36: Ensure hidden, decorative and duplicate content and artifact elements are not exposed to assistive technologies
Activate the application with a screen reader. Locate any images, objects, or elements on that do not have meaning, are visible disabled, or appear obscured. Attempt to move focus or navigate to the images that do not have meaning. Verify that the images, objects, or elements do not receive focus and are not rendered by voice output. If the images, objects, or elements can be navigated to, ensure that they are announced as “unavailable” or “disabled” and verify that they are not actionable.
## Test Case ID 37: Ensure instructions do not rely solely on sensory characteristics
Locate instructions. Verify that the following are not the sole method of communicating the instructions: shape, location, size, orientation, and sound.
## Test Case ID 38: Ensure shape and location are not the sole methods used to communicate information or hierarchy
Activate the application. Determine if any component is using visual formatting to convey meaning, including color, shape, size, location, and font attributes such as bold and italics. If so, ensure on-screen text, alternative text, or audio cues are also provided for these objects.
## Test Case ID 39: Provide consistent labels for controls, images and other common elements
Activate the application with a screen reader. Navigate to an image, object, element or control denoted by an image. Ensure that any image that is used two or more times across the application performs the same function and has the same textual representation
## Test Case ID 40: Ensure access to alternative input methods
Ensure controls can be accessed via multiple input methods such as touch screens, assistive technologies devices and keyboards. Ensure gesture based controls are functional while assistive technology is in use.
## Test Case ID 41: Ensure element text is meaningful within context
Locate the control. Determine the textual representation for the using assistive technology. Ensure the text is appropriate within context (take into account the sentence, paragraph, list item, heading immediately preceding the control, table cell that the control is in and the table header cell associated with the current cell if in a table cell). The text clearly describes the target of the control. If the control triggers an action the action should be described. Ensure the text is unique for each target or action that occurs.
## Test Case ID 42: Ensure scrolling occurs as needed when logical navigation is used
Navigate a scrollable view logically. Verify that the view scrolls as needed. Verify that the focus location remains accurate. Attempt to scroll using the screen reader scroll commands. Verify that the view scrolls as needed. Verify that pagination information is announced.
## Test Case ID 43: Ensure touch focus areas for active elements do not overlap
Examine controls visually with assistive technology running and ensure that all controls can be touched directly and the correct control is activated when navigated logically. Some assistive technologies provide a visual indication of accessible focus, this can be used to verify appropriate focus size as well.
## Test Case ID 44: Ensure touch screen actions are triggered on removal and not on initial touch
For simple controls such as buttons ensure activation does not occur unless the finger is removed within the touch area of the control. For complex gesture controls ensure users can abort control by a gesture such as moving off the control area or removing their finger without dragging.
## Test Case ID 45: Provide inactive space around touch screen elements
Using the touch screen ensure touchable areas of controls are not immediately adjacent to one another.
## Test Case ID 46: Provide sufficient size for touch screen elements
Controls that appear smaller than one fingertip width should be checked to ensure they are at least 3/8ths of an inch in size and can be easily located and activated by touch.
## Test Case ID 47: Ensure screens use a consistent navigation structure
Observe the screen within the application to compare it with other screens within the application with similar functionality. The module should be marked as violating this Best Practice if it does not contain the same navigation structure of other screens or if the navigation is differently placed than the rest of the screens in the application.
## Test Case ID 48: Ensure that the reading order of content is logical
Activate the screen reader. View the screen. Use logical navigation commands to review the content. Verify that content is announced in the correct order.
## Test Case ID 49: Provide a clear title for all screens
Examine the title of each screen on the application. Verify that a title exists. Determine if the title is relevant to the screen content and unique in the application. Navigate away from and return to the screen. Determine if the title of the page is the first element announced by the screen reader.
## Test Case ID 50: Provide for user control of font size
Determine whether there is an option to change the font size of the device. Determine if the option to change text size properly changes text size. If the option is provided or if the application provides adjustable font sizes:
1.	Ensure that it remains applied across all screens
2.	ensure that resized text properly reflows on the screen
3.	ensure that any elements that now require scrolling provide scrolling options
4.	Ensure that screen magnification works correctly with the application and all screens are readable.

