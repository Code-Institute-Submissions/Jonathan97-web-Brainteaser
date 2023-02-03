# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FJonathan97-web.github.io%2FBrainteaser%2Findex.html) |
![screenshot](documentation/images/index.png) | Pass: No Errors |
| Diagnosis | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FJonathan97-web.github.io%2FBrainteaser%2Fdiagnosis.html) |
![screenshot](documentation/images/diagnosis.png) | Pass: No Errors |
| Sign Up | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FJonathan97-web.github.io%2FBrainteaser%2Fsign-up.html) |
![screenshot](documentation/images/sign-up.png) | Pass: No Errors |
| Tips&Tricks | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FJonathan97-web.github.io%2FBrainteaser%2Ftips-tricks.html) |
![screenshot](documentation/images/tips-tricks.png) | Pass: No Errors |
| Thank you | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FJonathan97-web.github.io%2FBrainteaser%2Fthankyou.html) |
![screenshot](documentation/images/thankyou.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FJonathan97-web.github.io%2FBrainteaser) | ![screenshot](documentation/images/style-css.PNG) | Pass: No Errors (Warning's due to zoom)|

## Browser Compatibility

## Mozilla Firefox

- The bottom text for newsletter on the sign-up page spans outside of the box, I currently don't know the solution.

## Google Chrome

- Works as expected.

## Safari

- Works as expected.

## Edge

- Works as expected.

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/images/chrome-home.png) | Works as expected |
| Firefox (DE) | ![screenshot](documentation/images/Firefox-DE-home.png) | Difference in the sign-up page |
| Edge | ![screenshot](documentation/images/edge-home.png) | Works as expected |
| Safari | ![Safari-index](documentation/images/index-safari.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (DevTools) | ![Screenshot](documentation/images/responsive-mobile.png) | Works as expected |
| Tablet (DevTools) | ![Screenshot](documentation//images/responsive-tablet.png) | Works as expected |
| Desktop | ![Screenshot](documentation//images/responsive-desktop.png) | Works as expected |
| 4K Monitor | ![Screenshot](documentation//images/responsive-4k.png) | Minor scaling issues |
| iPhone 14 Pro | ![Screenshot](documentation/images/image-responsiveness-iphone.png) | Works as expected |
| Macbook Pro | ![Screenshot](documentation/images/responsive-macbook.png) | Works as expected |

## Lighthouse Audit

I have tested all the pages

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/images/mobile-lighthouse.png) | Some minor warnings |
| Home | Desktop | ![screenshot](documentation/images/desktop-lighthouse.png) | One minor warning on accessibility |
| Tips&Tricks | Mobile | ![screenshot](documentation/images/mobile-lighthouse.png) | Some minor warnings |
| Tips&Tricks | Desktop | ![screenshot](documentation/images/tips-tricks-lighthouse-desktop.png) | One warning |
| Diagnosis | Mobile | ![screenshot](documentation/images/mobile-diagnosis.png) | Minor warning |
| Diagnosis | Desktop | ![screenshot](documentation/images/desktop-diagnosis.png) | No warnings |
| Sign Up | Mobile | ![screenshot](documentation/images/mobile-signup.png) | Minor warnings |
| Sign Up | Desktop | ![screenshot](documentation/images/desktop-signup.png) | Minor warnings |
| Sign Up | Mobile | ![screenshot](documentation/images/mobile-signup.png) | Minor warnings |
| Sign Up | Desktop | ![screenshot](documentation/images/desktop-signup.png) | Minor warnings |

## Bugs

I have noticed one bug with the signup page currently other than that there are no remaining bugs that I am aware of.

- Text overflows from the textbox in the signup form.

    ![screenshot](documentation/images/bug-signup.png)

- To fix this, I need to check compability issues with Firefox Developer Edition.

## Unfixed Bugs

I have noticed one bug with the signup page currently other than that there are no remaining bugs that I am aware of.

- Text overflows from the textbox in the signup form.

    ![screenshot](documentation/images/bug-signup.png)

- Attempted fix: I tried to add padding-bottom: to the element but it was unsucessful, I need further testing of this.
