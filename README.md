This package allows you to create an outlined Material design search bar.

[![pub package](https://img.shields.io/pub/v/outline_search_bar.svg)](https://pub.dev/packages/outline_search_bar)

## Screenshots
<img src="https://user-images.githubusercontent.com/47127353/105262760-902c9500-5bd3-11eb-9f24-88bbf48d4845.png">

## Getting started

To use this package, add `outline_search_bar` as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/). For example:

```yaml
dependencies:
  outline_search_bar: ^2.1.1
```

## OutlineSearchBar

| Parameter | Description |
|---|---|
| `textEditingController` | The keyword of `OutlineSearchBar` can be controlled with a `TextEditingController`. |
| `keyboardType` | Set keyboard type. <br> Default value is `TextInputType.text`. |
| `textInputAction` | Set keyboard action. <br> Default value is `TextInputAction.search`. |
| `maxHeight` | Set the maximum height of `OutlineSearchBar`. |
| `icon` | Set the icon of `OutlineSearchBar`. |
| `backgroundColor` | Set the color of `OutlineSearchBar`. <br> Default value is `Theme.of(context).scaffoldBackgroundColor`. |
| `borderColor` | Set the border color of `OutlineSearchBar`. If value is null and theme brightness is light, use primaryColor, if dark, use accentColor. |
| `borderWidth` | Set the border thickness of `OutlineSearchBar`. <br> Default value is `1.0`. |
| `borderRadius` | Set the border radius of `OutlineSearchBar`. <br> Default value is `BorderRadius.all(Radius.circular(4.0))`. |
| `margin` | Set the margin value of `OutlineSearchBar`. <br> Default value is `EdgeInsets.only()`. |
| `padding` | Set the padding value of `OutlineSearchBar`. <br> Default value is `EdgeInsets.symmetric(horizontal: 5.0)`. |
| `textPadding` | Set the text padding value of `OutlineSearchBar`. <br> Default value is `EdgeInsets.symmetric(horizontal: 5.0)`. |
| `elevation` | Set the elevation of `OutlineSearchBar`. <br> Default value is `0.0`. |
| `initText` | Set the keyword to be initially entered. If initial text is set in `textEditingController`, this value is ignored. |
| `hintText` | Set the text to be displayed when the keyword is empty. |
| `textStyle` | Set the input text style. |
| `hintStyle` | Set the style of `hintText`. |
| `maxLength` | Set the maximum length of text to be entered. |
| `cursorColor` | Set the color of cursor. |
| `cursorWidth` | Set the width of cursor. <br> Default value is `2.0`. |
| `cursorHeight` | Set the height of cursor. |
| `cursorRadius` | Set the radius of cursor. |
| `clearButtonColor` | Set the background color of the clear button. <br> Default value is `Color(0xFFDDDDDD)`. |
| `clearButtonIconColor` | Set the icon color inside the clear button. <br> Default value is `Color(0xFFFEFEFE)`. |
| `searchButtonSplashColor` | Set the splash color that appears when the search button is pressed. |
| `searchButtonIconColor` | Set the icon color inside the search button. If value is null and theme brightness is light, use primaryColor, if dark, use accentColor. |
| `searchButtonPosition` | Set the position of the search button. Default value is `SearchButtonPosition.trailing`. |
| `autoCorrect` | Whether to use autoCorrect option. <br> Default value is `false`. |
| `hideSearchButton` | Whether to hide the search button. <br> Default value is `false`. |
| `ignoreWhiteSpace` | Whether to ignore input of white space. <br> Default value is `false`. |
| `ignoreSpecialChar` | Whether to ignore input of special characters. <br> Default value is `false`. |
| `onTap` | Called when `OutlineSearchBar` is tapped. |
| `onKeywordChanged` | Called whenever a keyword is entered. |
| `onClearButtonPressed` | When the clear button is pressed, it is called with the previous keyword. |
| `onSearchButtonPressed` | When the search button is pressed, it is called with the entered keyword. |
