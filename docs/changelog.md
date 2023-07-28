## 2023.07.23 
- Several users on Windows reported that they couldn't see the three window buttons, which was very awkward, so I added them back this time.
- The three buttons in the upper-left corner of the Mac are also added back, but for the sake of aesthetics, they are grayed out, and only colored when the mouse hovers over them.

## 2023.03.12
- Optimization
    - Hide the border around the window when in full screen mode;
    - Show the title bar and keep the three buttons in the upper-left corner visible (many users had trouble finding them);
    - Remove drag-and-drop for the Tab bar (it caused many unexpected bugs);
    - Simplify the style sheet
        - Previously, too many custom CSS styles were used to make the appearance match Arc as closely as possible, which caused some styles to break when Vivaldi was updated. Therefore, a principle was established this time to not blindly pursue perfect styling, but rather use as little CSS as possible;

## 2022.08.28 Background: Why I made this
To give some background, I've been using the Vivaldi browser as my primary browser for about a year now. Recently, I had the opportunity to try out the Arc browser, which was still in beta testing at the time, for about two weeks. The experience of using Arc during those two weeks was really good - the interactions felt intuitive, and the UI was very aesthetically pleasing.

However, I eventually switched back to Vivaldi primarily because Arc crashed a few times during use.

Later, I learned that Vivaldi actually allows for UI customization using CSS, so I decided to give it a try. The result is the configuration that is described on this webpage.

While the final result doesn't quite measure up to Arc's UI and attention to detail, I feel that this configuration provides a similar user experience. So I wanted to share this configuration with everyone who is still waiting to test out Arc, or who might be looking for an alternative due to Arc's memory usage.