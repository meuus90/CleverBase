# CleverBase

[![](https://jitpack.io/v/meuus90/CleverBase.svg)](https://jitpack.io/#meuus90/CleverBase)


Get Started
---

1. Add these in your root build.gradle:
    
```
    buildscript {
        dependencies {
            classpath com.android.tools.build:gradle:3.3.1
        }
    }
```    
... 
```
    allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
```
2. Add the dependency on your app build.gradle. 
    
    (Please replace x.y.z with the latest version numbers: [![](https://jitpack.io/v/meuus90/CleverBase.svg)](https://jitpack.io/#meuus90/CleverBase) )
```
    dependencies {
        implementation 'com.github.meuus90:CleverBase:x.y.z'
    }
```
3. Add compileOptions inside **android{}** on your app build.gradle
```
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }	
```
Compatibility
---

 * **Kotlin** : 1.3.21
 * **Minimum Android SDK** : 23 or later
 * **Compile Android SDK** : 29 or later
 
 
	
