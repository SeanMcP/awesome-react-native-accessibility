# awesome-react-native-accessibility
🎁 A curated list of React Native accessibility resources

## Table of Contents

- [Official documentation](#official-documentation)

## Official documentation
Resources provided by Facebook for React Native accessibility

### [Accessibility - React Native](https://facebook.github.io/react-native/docs/accessibility)
The accessibility page of the React Native docs.

 **Takeaway**: React Native aids accessibility by providing standardized properties that convert to native accessibility code on iOS and Android.

### [Accessibility API Updates - React Native](https://facebook.github.io/react-native/blog/2018/08/13/react-native-accessibility-updates)
An update to the API that combined `accessibilityComponentType` and `accessibilityTraits` into one cross-platform property, and added `accessibilityHint` and `accessibilityIgnoresInvertColors`.

**Takeaway**: `accessibilityRole` has fewer options than `accessibilityTraits` on iOS, but works for both platforms.

### [Making React Native apps accessible - Facebook](https://code.fb.com/android/making-react-native-apps-accessible/)
A (now dated) summary of how Facebook made their Ads Manager app more accessible.

**Takeaway**: A lot can be accomplished using `accessible` and `accessibilityLabel` props.
