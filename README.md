# InkPageIndicator

InkPageIndicator created by @nickbutcher for Plaid https://github.com/nickbutcher/plaid and backported by me for API 16+ (4.1+)

[![GitHub license](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/DavidPacioianu/InkPageIndicator/master/LICENSE)  [ ![Download](https://api.bintray.com/packages/davidpacioianu/maven/ink-page-indicator/images/download.svg) ](https://bintray.com/davidpacioianu/maven/ink-page-indicator/_latestVersion)

<h3>InkPageIndicator Preview</h3>
 <img height="500px" width="300px" src="http://giant.gfycat.com/AbleEmbellishedKillerwhale.gif"/>

# Usage

```gradle
dependencies {
    compile 'com.pacioianu.david:ink-page-indicator:1.0.1'
}
```

```xml
<com.davidpacioianu.inkpageindicator.InkPageIndicator
  android:id="@+id/indicator"
  android:layout_width="match_parent"
  android:layout_height="wrap_content"/>
```

or with custom attributes:
```xml
<com.davidpacioianu.inkpageindicator.InkPageIndicator
  android:id="@+id/indicator"
  android:layout_width="match_parent"
  android:layout_height="wrap_content"
  app:dotDiameter="8dp"
  app:dotGap="8dp"
  app:animationDuration="320"
  app:pageIndicatorColor="@color/gray"
  app:currentPageIndicatorColor="@color/black"/>
```
 and 
 
```java
InkPageIndicator inkPageIndicator = (InkPageIndicator) findViewById(R.id.indicator);
inkPageIndicator.setViewPager(viewPager);
```

License
--------

    Copyright 2015 Google Inc., David Pacioianu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
