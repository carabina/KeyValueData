# KeyValueData

[![CI Status](http://img.shields.io/travis/1Fr3dG/KeyValueData.svg?style=flat)](https://travis-ci.org/Alfred Gao/KeyValueData)
[![Version](https://img.shields.io/cocoapods/v/KeyValueData.svg?style=flat)](http://cocoapods.org/pods/KeyValueData)
[![License](https://img.shields.io/cocoapods/l/KeyValueData.svg?style=flat)](http://cocoapods.org/pods/KeyValueData)
[![Platform](https://img.shields.io/cocoapods/p/KeyValueData.svg?style=flat)](http://cocoapods.org/pods/KeyValueData)

用来存储 Key-Value 型数据。可针对不同情况使用不同的后端存储。

Manage key-value data with same protocol, for kinds of backends.

## Example

~~~swift
var _data: KeyValueData = KeyValueDictionaryInKeychain(withKey: "account")

_data["accountid"] = "12345678"

let id = _data["accountid"] as! String
~~~

## Requirements

* iOS 9.0+

## Installation

可通过[CocoaPods](http://cocoapods.org)安装：

KeyValueData is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "KeyValueData"
```

## Author

[Alfred Gao](http://alfredg.org), [alfredg@alfredg.cn](mailto:alfredg@alfredg.cn)

## License

KeyValueData is available under the MIT license. See the LICENSE file for more info.
