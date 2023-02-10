To get a Git project into your build:

[![](https://jitpack.io/v/metafylabs/Imagecropper-Library.svg)](https://jitpack.io/#metafylabs/Imagecropper-Library)


Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency 

	dependencies {
	        implementation 'com.github.metafylabs:Imagecropper-Library:Tag'
	}
