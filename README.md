# PUCustomUISlider - Framework

Customised UISlider in a single function call

## License

The MIT License (MIT)

Copyright (c) 2021 TheKarma

## Metadata

#### A framework is a hierarchical directory that encapsulates a dynamic library, header files, and resources, such as storyboards, image files, and localized strings, into a single package. Apps using frameworks need to embed the framework in the app's bundle.

#### PUCustomUIslider is also such kind of framework and using it you can apply customisation in your native slider such as background color or gradient background color, slider height, thumb color, thumb image, background image and its framing etc.

### Example project output

<img src="https://github.com/PayalUmraliya/PUCustomUIslider/blob/main/output.png" width="240" height="500" /> <img src="https://github.com/PayalUmraliya/PUCustomUIslider/blob/main/output2.png" width="240" height="500" />

## Usage

```
import PuGradientUISlider
```

Create an outlet for UISlider

```
@IBOutlet weak var slidernw: UISlider!
```

Use below code for customisation

```
PUGradientSlider.setSliderWithFrame(CGRect(x: 0.0, y: 0.0, width: slidernw.bounds.width, height: 12.0 ), sliderNamed: slidernw, withcolors: [UIColor.red.cgColor, UIColor.yellow.cgColor, UIColor.green.cgColor], thumbFrm: CGRect(x: 0, y: 0, width: 35.0, height: 35.0), thumbBgColor: UIColor.green,thumbImg: UIImage.init(named: "thumbtint")!)
```

* ###### Above function takes 6 parameters
* 1 - Frame for the slider (for height customisation)
* 2 - Outlet name for the UISlider
* 3 - Array of colors for Gradient or you can give single color as an array or same color in array as well
* 4 - Thumb indicator frame (Height and width)
* 5 - Thumb indicator background color
* 6 - Thumb image (UIImage - if you pass nil to the thumbImg then it will use thumbBgColor param else it will use the thumbImg)

### Add  framework into the project as following:

* 1 - Select the project file from the project navigator on the left side of the project window.
* 2 - Select the target for where you want to add frameworks in the project settings editor.
* 3 - Select the “Build Phases” tab, and click the small triangle next to “Link Binary With Libraries” to view all of the frameworks in your application.
* 4 - To Add frameworks, click the “+” below the list of frameworks.
* 5 - To select multiple frameworks, press and hold the command key while using the mouse to click the desired frameworks.

<img src="https://github.com/PayalUmraliya/PUCustomUIslider/blob/main/x6iMB.png"/>

### For more detail follow the link below :

https://developer.apple.com/library/archive/technotes/tn2435/_index.html

##### Make sure you embed the framework without signing as below image.

<img src="https://github.com/PayalUmraliya/PUCustomUIslider/blob/main/importaslikethis.png"/>

## Author

Payal Umraliya [behappy78600@gmail.com] 

ツツツツツツ
