# zeplin-extension
Exploration of Zeplin Extensions.

<p align="center">
<img src=".github/screenshot.png" />
</p>

## Features

- 🖍 Color pallette for iOS

<details><summary>Example</summary>
<p>

```swift
import UIKit

extension UIColor {

    static let electricBlue = UIColor(red: 0/255, green: 86/255, blue: 255/255, alpha: 1)
}
```

</p>
</details>

- ✏️ Fonts for iOS

<details><summary>Example</summary>
<p>

```swift
import UIKit

extension UIFont {

    static func BloggerSansBold(ofSize: CGFloat) -> UIFont {
        return UIFont(name: "BloggerSans-Bold", size: size)!
    }
}
```

</p>
</details>

- 🚧 Snippets for borders and corner radius

<details><summary>Example</summary>
<p>

```swift
view.layer.borderWidth = 4
view.layer.borderColor = UIColor.white.cgColor
view.layer.cornerRadius = 40
```

</p>
</details>

- 🌚 Snippets for shadows

<details><summary>Example</summary>
<p>

```swift
view.layer.shadowColor = UIColor.black8.cgColor
view.layer.shadowOffset = CGSize(width: 0, height: 4)
view.layer.shadowRadius = 8
```

</p>
</details>

## How to Install

The instruction from official [tutorial](https://github.com/zeplin/zeplin-extension-documentation/blob/master/tutorial.md#adding-a-local-extension).

## Author

Artem Novichkov, novichkoff93@gmail.com

[![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/artemnovichkov?utm_source=github&utm_medium=button&utm_term=artemnovichkov&utm_campaign=github)

## License

zeplin-extension is available under the MIT license. See the LICENSE file for more info.
