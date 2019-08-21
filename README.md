# MTSlideToOpen
A simple SlideToUnlock iOS UI component

<a href="url"><img src="https://raw.githubusercontent.com/michael-mcanulty/MTSlideToOpen/master/Screenshot.png" align="center" height="500" ></a>


## Requirements
* Swift 5.0
* iOS 9.0 or later

#### Manual install

Drag and drop file `MTSlideToOpenView.swift` to your project.


## Usage
```
let slide = MTSlideToOpenView(frame: CGRect(x: 30, y: 300, width: 340, height: 80), knobText: "SOS")
slide.sliderViewTopDistance = 10
slide.delegate = self
slide.defaultThumbnailColor = Color.red.create;
slide.defaultKnobTextSize = 26.0
slide.defaultSliderBackgroundColor = Color.red.create.withAlphaComponent(0.3).lighter()
slide.defaultSlidingColor = UIColor.white
slide.defaultLabelText = "Slide To Initiate SOS"
self.view.addSubview(slide);
```

## SwiftUI version

I built another version using SwiftUI. You can check it here [MTSlideToOpen-SwiftUI](https://github.com/lemanhtien/MTSlideToOpen-SwiftUI).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
