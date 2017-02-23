# CarthagePlayground

![Swift 3.0.2](https://img.shields.io/badge/Swift-3.0.2-orange.svg)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)


Template of Xcode Playground for testing Carthage libraries.

This Xcode project helps to try Xcode Playground with Carthage libraries.

## Usage

### Clone repositry

Clone this repositry everywhere as you like.

### Setup Carthage

ex) [Nirma/Attribted](https://github.com/Nirma/Attributed)

```
# Cartfile
github "Nirma/Attributed"
```

```sh
$ carthage update --platform iOS --use-submodules
```

### Install Libraries in project

#### 1. Open `CarthagePlayground.xcworkspace`

#### 2. Drag and drop `.xcodeproj` of the library in Xcode Project Navigator.

![path to xcodeproj](https://dl2.pushbulletusercontent.com/vIcvO19K2Xeo2N2X8P8mwSQEWtuxHEHH/screenshot1.png)

<img src="https://dl2.pushbulletusercontent.com/p81LcprwAVAYZ23DVJ5uzTQQ3i0XcSfd/screenshot2.png" alt="project navigator" width="300px" />

#### 3. Add `.framework` to `Embedded Binaries` in `Carthage/Build/iOS/`.

![path to framework](https://dl2.pushbulletusercontent.com/qPJqFXltiAmvZfOathxkWRlrWkykixUA/screenshot3.png)

<img src="https://dl2.pushbulletusercontent.com/x6z6f3MpTUn0B5QPmv2ywY5czI8eDGJg/screenshot4.png" alt="choose options" width="600px" />

<img src="https://dl2.pushbulletusercontent.com/1qPDFKOzPanYV7pSYUFLAn58IqegUN1W/screenshot5.png" alt="Embedded Binaries" width="600px" />


#### 4. Build
Run workspace. (⌘R)

### Playground

You can use the library in Playground.

![Xcode Playground](https://dl2.pushbulletusercontent.com/2ucFG9UNhFpqSm7n8FGLPOxi3mw5ODlM/screenshot6.png)


## Requirements
- Xcode 8.2+
- Swift 3.0+


## Reference
- [【iOS】Carthageで入れたframeworkをPlaygroundで使用する - Qiita](http://qiita.com/ryokosuge/items/2551cd4faa9dca324342)

## License

CarthagePlayground is free software, and may be redistributed under the terms specified in the [LICENSE](https://github.com/WorldDownTown/CarthagePlayground/blob/master/LICENSE) file.

