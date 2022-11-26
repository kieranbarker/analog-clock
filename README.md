# Analog Clock

This project is adapted from [the clock in the list of Svelte examples](https://svelte.dev/examples/clock). All I did was rewrite it in standard HTML, CSS and JavaScript.

[View demo](https://kieranbarker.github.io/analog-clock/)

## Accessibility

I used [a visually hidden element](https://www.a11yproject.com/posts/how-to-hide-content/) to make the time accessible to screen readers. I have tested this using:

- <b>VoiceOver in Safari 16.1 on macOS Monterey 12.6.1.</b> For example, it reads as "6 hours, 42 minutes and 14 seconds".
- <b>VoiceOver in Safari 16.1 on iOS 16.1.1.</b> For example, it reads as "6 hours, 42 minutes and 14 seconds".
- <b>Narrator in Edge 107 on Windows 10 21H2.</b> For example, it reads as "6:42 and 14 seconds".
- <b>TalkBack in Chrome 107 on Android 13.</b> For example, it reads as "6 hours, 42 minutes and 14 seconds".

I welcome feedback from people who find that this clock not work well with their chosen operating system, browser and/or screen reader.
