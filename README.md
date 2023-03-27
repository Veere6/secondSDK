# secondSDK
Simple toast by veer

> Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
gradle
  allprojects {
		repositories {
			'''
			maven { url 'https://jitpack.io' }
		}
	}
  '''
  > Add the dependency
  
  dependencies {
  '''
	        implementation 'com.github.Veere6:secondSDK:Tag'
	}
