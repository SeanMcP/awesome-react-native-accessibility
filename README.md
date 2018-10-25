# awesome-react-native-accessibility
🎁 A curated list of React Native accessibility resources

## Table of Contents

- [Official documentation](#official-documentation)
- [Overviews](#overviews)
- [Tutorials](#tutorials)
- [Packages](#packages)
- [Tools](#tools)

## Official documentation
Resources provided by Facebook for React Native accessibility

### [Accessibility (React Native)](https://facebook.github.io/react-native/docs/accessibility)
The accessibility page of the React Native docs.

 **Takeaway**: React Native aids accessibility by providing standardized properties that convert to native accessibility code on iOS and Android.

### [Accessibility API Updates (React Native)](https://facebook.github.io/react-native/blog/2018/08/13/react-native-accessibility-updates)
An update to the API that combined `accessibilityComponentType` and `accessibilityTraits` into one cross-platform property, and added `accessibilityHint` and `accessibilityIgnoresInvertColors`.

**Takeaway**: `accessibilityRole` has fewer options than `accessibilityTraits` on iOS, but works for both platforms.

### [Making React Native apps accessible (Facebook)](https://code.fb.com/android/making-react-native-apps-accessible/)
A (now dated) summary of how Facebook made their Ads Manager app more accessible.

**Takeaway**: A lot can be accomplished using `accessible` and `accessibilityLabel` props.

## Overviews
Thorough looks into React Native accessibility

### [Creating inclusive apps in React Native (Medium)](https://medium.com/@larenelg/creating-inclusive-apps-in-react-native-the-coding-bit-bd3832349009)
Larene Lg summarizes the best practices in React Native accessibility.

**Takeaway**: `accessible` and `accessibilityLabel` are the most common and useful accessibility props.

## Tutorials
Step-by-step guides to making accessible React Native apps

### [Making accessible React Native apps (Pusher)](https://pusher.com/tutorials/accessible-react-native)
Wern Ancheta makes an inaccessible app more accessible.

**Takeaway**: Don't neglect the visual contrast and text size in addition to the React Native accessibility props.

## Packages
Packages that provide helpful accessibility resources

### [`react-native-accessibility` (GitHub)](https://github.com/MaxToyberman/react-native-accessibility)
Provides utilities for triggering the screen reader and autofocusing views.

**Takeaway**: There are instances when you may want to trigger the screen reader, but it should be used sparingly.

## Tools
Online resources, software, and applications to aid in accessibility development and testing

### [Mobile Accessibility Resources (Medium)](https://medium.com/@larenelg/mobile-accessibility-resources-dab97a739080)
Larene Lg's list of resources and applications for mobile accessibility

**Takeaway**: Tech companies and governments have made resources available to help you on your quest.

### Mobile Apps

#### Android

- [Accessibility Scanner (Google Play)](https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.auditor&hl=en_US) - "Accessibility Scanner is a tool that suggests accessibility improvements for Android apps without requiring technical skills. Just open the app you want to scan, then tap the Accessibility Scanner button to find items in the app that might benefit from accessibility improvements."
- TalkBack

#### iOS
- VoiceOver
