# CacheUtilsLibrary

A simple util library to write and read cache files in Android. This whole library is just a simple [Java class](https://github.com/westlinkin/CacheUtilsLibrary/blob/master/library/src/main/java/com/lifeofcoding/cacheutlislibrary/CacheUtils.java), I used it in many other projects. I found it very useful, so here it is.

##Gradle


##Configuration
You need to configurate `CacheUtilsLibrary` in your `Application` class.

```
public class MyApplication extends Application {

    @Override
    public void onCreate() {
        super.onCreate();
        // configure CacheUtilsLibrary
        CacheUtils.configureCache(this);
    }
}
```

Don't forget to declare the `MyApplication` class in your `AndroidManifest.xml` file.


##Usage


##License

	Copyright 2015 Wesley Lin

	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at

    	http://www.apache.org/licenses/LICENSE-2.0

	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.
