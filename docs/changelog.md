## 2023.03.12
- Optimization
    - Hide the border around the window when in full screen mode;
    - Show the title bar and keep the three buttons in the upper-left corner visible (many users had trouble finding them);
    - Remove drag-and-drop for the Tab bar (it caused many unexpected bugs);
    - Simplify the style sheet
        - Previously, too many custom CSS styles were used to make the appearance match Arc as closely as possible, which caused some styles to break when Vivaldi was updated. Therefore, a principle was established this time to not blindly pursue perfect styling, but rather use as little CSS as possible;
    - There are now two style sheets available for everyone to choose from:
        - main_arc.css, which adds some styles on top of minimal to make it closer to Arc's appearance and is the default;
        - main_minimal.css, which has fewer styles, but already has a good effect when used alone. If you don't want to make too many changes, you can choose to use this one.

## 2022.10.01
- Other style sheets were added to the style.css file, which are commented out by default. You can choose which one to use according to your needs:
    - Uncomment panel_mode.css if you prefer to use the panel mode;
    - Uncomment new_tab.css if you want to show the new tab button.
