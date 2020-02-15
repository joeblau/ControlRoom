<p align="center">
    <img src=".github/assets/header@2x.png" alt="Control Room Header"/>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Swift-5.1-brightgreen.svg" />
    <a href="https://twitter.com/twostraws">
        <img src="https://img.shields.io/badge/Contact-@twostraws-lightgrey.svg?style=flat" alt="Twitter: @twostraws" />
    </a>
</p>

Control Room is a macOS app that lets you control the simulators for iOS, tvOS, and watchOS – their UI appearance, status bar configuration, and more. It wraps Apple’s own **simctl** command-line tool, so you’ll need Xcode installed.

Some features, such as sending example push notifications or move between light and dark mode, require Xcode 11.4 or later.


## Installation

To try Control Room yourself, download the code and build it through Xcode. It’s built using SwiftUI, so you’ll need macOS Catalina in order to run it. You will also need Xcode installed, because it relies on the **simctl** command being present.

**Warning:** SwiftUI on macOS is a little flaky at times, so I highly recommend you update to the very latest macOS version if you want to avoid any surprises.

Control Room was written as a personal project to solve an immediate problem, but when [I showed a demo on Twitter](https://twitter.com/twostraws/status/1227619436187803648) a lot folks seemed keen to try it themselves, so here you go. I’ve made no attempt to report errors; again, this was originally just for me.


## Contribution guide

Any help you can offer with this project is most welcome – there are opportunities big and small so that someone with only a small amount of Swift experience can help.

Some suggestions you might want to explore:

- Handle errors in a meaningful way.
- Handle blocking operations, such as recording video or launching an app.
- Add documentation in the code or here in the README.
- Did I mention handling errors in a meaningful way?

You’re also welcome to try adding some tests, although given our underlying use of simctl that might be tricky.

If you spot any errors please open an issue and let us know which macOS and Xcode versions you’re using.

**Please ensure that SwiftLint returns no errors or warnings before you send in changes.**


## Credits

Control Room was designed and built by Paul Hudson, and is copyright © Paul Hudson 2020. Control Room is licensed under the MIT license; for the full license please see the LICENSE file.

Control Room is built on top of Apple’s **simctl** command – the team who built that deserve the real credit here.

Swift, the Swift logo, and Xcode are trademarks of Apple Inc., registered in the U.S. and other countries.

If you find Control Room useful, you might find my website full of Swift tutorials equally useful: [Hacking with Swift](https://www.hackingwithswift.com).
