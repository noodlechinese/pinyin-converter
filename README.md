# Pinyin Converter

This is a swift fork of https://github.com/quizlet/pinyin-converter

```swift
PinyinConverter().convert("ni3hao3") // returns 'nǐhǎo'
```

# Getting Started

Just add the PinyinConverter.swift to your project. There are no external dependencies.

# Usage

PinyinConverter only has 1 function: ```func convert(pinyin: String) -> String```

```swift
let converter = PinyinConverter()

let pinyin = converter.convert("san1ren2xing2bi4you3wo3shi1");
// returns "sānrénxíngbìyǒuwǒshī"

// ü can be typed by using v
let pinyin = converter.convert("lv4");
// returns "lǜ"

// works with uppercase chars too
let pinyin = converter.convert("WO3 HEN3 XI3HUAN QUIZLET!");
// returns "WǑ HĚN XǏHUAN QUIZLET!"
```

Enjoy!
