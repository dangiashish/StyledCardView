<p align="center">
<!-- <img src=""/> -->
</p>

<div align = "center">
<h1 align="center"> Styled Card View </h1>
<a href="https://www.codefactor.io/repository/github/dangiashish/styledcardview"><img src="https://www.codefactor.io/repository/github/dangiashish/styledcardview/badge" alt="CodeFactor" /></a>
<a href="https://jitpack.io/#dangiashish/StyledCardview"><img src="https://jitpack.io/v/dangiashish/StyledCardview.svg"/></a>
<a href="(https://developer.android.com/tools/sdkmanager"><img src="https://img.shields.io/badge/android--sdk-24%2B-green"/></a>
<a href="https://www.java.com/"><img src="https://img.shields.io/badge/compatible-java-blue"/></a>
<a href="https://kotlinlang.org/"><img src="https://img.shields.io/badge/compatible-kotlin-blueviolet"/></a>


</div>

### Gradle

Add repository in your `build.gradle` (project-level) file :
```gradle
allprojects {
      repositories {
	...
	maven { url 'https://jitpack.io' }
	}
}
```
##### OR 
in your `settings.gradle`
 
```gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```
### Add dependency :

Add dependency in your `build.gradle` (module-level) file :

```groovy
dependencies {

 implementation 'com.github.dangiashish:StyledCardview:1.0.5'

}
```

### Xml Attrs
```groovy
 <com.github.dangiashish.StyledCardView
        android:layout_width="match_parent"
        android:layout_height="400dp"
        app:background_Type="fill_stroke"
        app:cornerRadius="10dp"
        app:background_Color="@color/white"
        app:shadow0_Outer_Alpha="0.3"
        app:shadow0_Outer_Angle="-45"
        app:shadow0_Outer_Blur="10dp"
        app:shadow0_Outer_Color="@android:color/holo_green_light"
        app:shadow0_Outer_Distance="10dp"
        app:shadow1_Outer_Alpha="0.5"
        app:shadow1_Outer_Angle="135"
        app:shadow1_Outer_Blur="10dp"
        app:shadow1_Outer_Color="@android:color/holo_blue_light"
        app:shadow1_Outer_Distance="5dp"
        app:shadow_Outer_Area="40dp"
        app:stroke_ColorType="gradient_sweep"
        app:stroke_Gradient_Angle="-45"
        app:stroke_Gradient_Color0="@android:color/holo_blue_light"
        app:stroke_Gradient_Color1="@android:color/holo_green_light"
        app:stroke_Width="1dp" />
```

    
#### LICENSE
```
MIT License

Copyright (c) 2023 Ashish Dangi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

        
