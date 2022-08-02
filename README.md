<div align="center">
  <h3>Workshop</h3>
  <h1>Make It For Everyone</h1>
  <br />
  <a href="https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/discussions">Ask a Question</a>
  
</div>
  <br />
<p align="center">
  <a href="#" alt="Version">
    <img src="https://img.shields.io/static/v1?label=Version&message=2.0.0&color=brightgreen" />
  </a>
  <a href="#" alt="XCode Version">
    <img src="https://img.shields.io/static/v1?label=XCode%20Version&message=14.0&color=brightgreen&logo=xcode" />
  </a>        
  <a href="#" alt="Swift Version">
    <img src="https://img.shields.io/static/v1?label=Swift%20Version&message=5.0&color=brightgreen&logo=swift" />
  </a>
  <a href="#" alt="Framework used">
    <img src="https://img.shields.io/static/v1?label=Framework%20used&message=SwiftUI&color=brightgreen&logo=swift"
            alt="coverage">
  </a>          
</p>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [How to](#how-to)
- [Issues and Discussions](#issues-and-discussions)
- [Support](#support)
- [Authors & contributors](#authors--contributors)
- [License](#license)

</details>

---
<br />

## About

Discover how to design your app with accessibility in mind. You can empower everyone to use your app by making your app legible. Explore how colors, colors contrast ratio and fonts affect legibility of your app.
Explore how to improve VoiceOver experience for users with vision disabilities.

<br />

## Getting Started

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone
   ```

2. Open the ```.xcodeproj``` file

### How to

**Visuals**:

1. When using colors, it is important to have sufficient contrast between the background color and foreground color. According to guidelines, text should have a contrast ratio of at least 4.5:1 against its background. Change the foreground or background colors and make sure that the text is legible.
2. Red–green color blindness is the most common form of color blindness. Test the app screen using Sim Daltonism and selecting Deuteranopia as simulated vision. Change the colors to make sure that text is legible for everyone.
3. Using a font type with decorative elements will make your content more difficult to read. You have to allow adjusting the text size used on your app. Explore how apps that supports Dynamic Type will adjust to preferred reading size.


**Resources:**

- [Human Interface Guidelines. Accessibility. Color and Contrast] (https://developer.apple.com/design/human-interface-guidelines/accessibility/overview/color-and-contrast)
- [Human Interface Guidelines. Accessibility. Text Size and Weight] (https://developer.apple.com/design/human-interface-guidelines/accessibility/overview/text-size-and-weight)
- [App Store. Sim Daltonism](https://apps.apple.com/us/app/sim-daltonism/id1050503579)

**Starter Project**:
1. Turn on and practice VoiceOver using Vin Brulé app.
2. Use SwiftUI accessibility view modifiers `accessibilityLabel`, `accessibilityHidden` and `accessibilityHint` to improve VoiceOver experience in the app.
3. Find out what other SwiftUI accessibility view modifiers you can use to make the experience even better.


**Resources:**

- [iPhone User Guide. Turn on and practice VoiceOver on iPhone](https://support.apple.com/en-gb/guide/iphone/iph3e2e415f/15.0/ios/15.0)
- [Human Interface Guidelines. Accessibility. Navigation](https://developer.apple.com/design/human-interface-guidelines/accessibility/overview/navigation/)

<br />

## Issues and Discussions

You've found a bug in the source code, a mistake in the documentation or maybe you'd like a new feature? Take a look at [GitHub Discussions](https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/discussions) to see if it's already being discussed. You can help us by [submitting an issue on GitHub](https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/issues). Before you create an issue, make sure to search the issue archive -- your issue may have already been addressed!

Please try to create bug reports that are:

- _Reproducible._ Include steps to reproduce the problem.
- _Specific._ Include as much detail as possible: which version, what environment, etc.
- _Unique._ Do not duplicate existing opened issues.
- _Scoped to a Single Bug._ One bug per report.

<br />

## Support

Reach out to the maintainer at one of the following places:

- [GitHub Discussions](https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/discussions)
- [GitHub issues](https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+)
- Contact a Mentor for any other help

<br />

## Authors & contributors

The original setup of this repository is by [Pasquale Vittoriosi](https://github.com/PasqualeVittoriosi).

* [Vasily Martin](https://github.com/vmartindev)
* [Pasquale Vittoriosi](https://github.com/PasqualeVittoriosi)
* [Domenico De Luca](https://github.com/domedeluca)

For a full list of all authors and contributors, see [the contributors page](https://github.com/developer-academy-unina/Workshop-Make-It-For-Everyone/contributors).

<br />

## License

This project is licensed under the **MIT License**.

See [LICENSE](LICENSE) for more information.