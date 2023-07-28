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
