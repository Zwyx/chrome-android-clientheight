# Observe the bug

- Open Chrome on an Android phone,
- open a new tab,
- enter the address https://zwyx.github.io/chrome-android-clientheight/ **and press the Enter key of your keyboard to navigate to this address**,
- notice that the fixed div containing the buttons is not vertically centered,
- click the green button,
- notice that the RED BUTTON is actually the one being clicked,
- notice that the dialog is now vertically centered.

<div align="center">

<img src="https://github.com/Zwyx/chrome-android-clientheight/assets/29386932/3becbb27-a59a-4ad0-9bbd-e0fac4e08fee" width="350">

</div>

If, in your case, the red button isn't clicked (it might depend on the height of your device), you should still observe the dialog jumping up to be vertically centered.

- When the page is refreshed, the bug doesn't happen.
- If your keyboard is not visible when navigating to the page (hide your keyboard, and tap the entry in Chrome dropdown menu just below the address bar), then the bug doesn't happen either.

This has been observed by others:
- https://github.com/vercel/next.js/issues/47839
