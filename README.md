# Custom Checkbox Challenge
Take home exercise: create a custom-styled and accessible checkbox.

## Task
Using plain HTML, CSS, and JS (no third-party libraries and frameworks), create a styled
checkbox that preserves the accessibility of a native checkbox (keyboard toggle). Use as
little JS as possible/reasonable.

## Acceptance Criteria
- [x] The custom checkbox is styled similar to what you see in the [video](https://drive.google.com/file/d/1shYzkzHruC7gRQm1ixXVfd7u7OT07fnM/view?usp=sharing) (find a
checkmark SVG in Assets below).
- [x] Clicking the native checkbox, the custom checkbox is displayed and checked as
well.
- [x] Clicking the custom checkbox, the native checkbox is checked as well.
- [x] Using the keyboard (tab), when the native checkbox is focused, a blue line appears
around the custom checkbox.
- [x] Using the keyboard (tab), when the native checkbox has focus and the user presses
space, the native checkbox is selected as well as the custom checkbox.
- [x] When hiding the native checkbox, the native accessibility (keyboard navigation:
tab, space) is preserved for the custom checkbox.

## Assets
Checkmark SVG
```md
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256">
    <rect width="256" height="256" fill="none"></rect>
    <polyline
        points="216 72.005 104 184 48 128.005"
        fill="none"
        stroke="currentColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16">
    </polyline>
</svg>
```

## Executing code
Open `index.html` file in your browser.

## Notes on the solution
1. As the exercise stated that it's better to "use as little JS as possible/reasonable.", I took it as a challenge to solve the exercise with using none.
2. Please note, that I tried to keep the commit history as descriptive as possible, and you can find some relevant comments on the solutions choices over there.
3. Though I tried to copy as much as possible the styles from the video, some styles choices are dummy.