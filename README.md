CircleView
==========

A Circle View containing Title and Subtitle

![CircleView](/Screenshots/Screenshot_8.png)

[![Android Arsenal](http://img.shields.io/badge/Android%20Arsenal-CircleView-blue.svg)](http://android-arsenal.com/details/1/796)


Attributes to choose from:

* `titleText` - The text in the first row.
* `subtitleText` - The text in the second row.
* `titleSize` - The size of the first row text.
* `subtitleSize` - The size of the second row text.
* `strokeWidth` - The size of the outter line surrounding the view.
* `fillRadius` - The radius of the inner circle.
* `titleColor` - The color of the first row text.
* `subtitleColor` - The color of the second row text.
* `fillColor` - The color of the inner circle.
* `strokeColorValue` - The color of the outter line circle.
* `backgroundColorValue` - the color between the circle and the stroke.
    
Example
=======
```xml
 <com.github.circleView
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="300dp"
        android:layout_height="300dp"
        app:titleText="title"
        app:subtitleText="subtitle"
        app:titleSize="12dp"
        app:subtitleSize="9dp"
        app:titleColor="@color/white"
        app:subtitleColor="@color/red"
        app:strokeColorValue="@color/blue"
        app:backgroundColorValue="@color/gray"
        app:fillColor="@color/green"
        app:fillRadius="0.9"
        app:strokeWidth="5"/>
```

How To Use
==========

You can search us on *Gradle,please* http://gradleplease.appspot.com/ or just add 

the dependency to your module's `build.gradle` file: 

```compile 'com.github.pavlospt:circleview:1.2' ```


Credits
=======
Author : Pavlos-Petros Tournaris (p.tournaris@gmail.com)

Google+ : [+Pavlos-Petros Tournaris](https://plus.google.com/u/0/+PavlosPetrosTournaris/)

Facebook : [Pavlos-Petros Tournaris](https://www.facebook.com/pavlospt)

LinkedIn : [Pavlos-Petros Tournaris](https://www.linkedin.com/pub/pavlos-petros-tournaris/44/abb/218)

Thanks to [+Filip Puđak](https://plus.google.com/u/0/117550349320705739707/) and his ProgressPieView that helped me think and create this View.

(In case you use this in your app let me know to make a list of apps that use it! )

Apps using this library
=======================

Hungry (https://play.google.com/store/apps/details?id=com.hungry)

License
=======

    Copyright 2014 Pavlos-Petros Tournaris

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
       http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
