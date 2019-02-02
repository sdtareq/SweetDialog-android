# SweetDialog-android
## Step 1: Add it in your root build.gradle at the end of repositories:
``` 
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
## Step 2: Add the dependency
```
	dependencies {
	        implementation 'com.github.sdtareq:SweetDialog-android:v0.1.1'
	}

```
## Uses
```java
  SweetAlertDialog pDialog = new SweetAlertDialog(getApplicationContext(), SweetAlertDialog.PROGRESS_TYPE);
                pDialog.getProgressHelper().setBarColor(Color.parseColor("#A5DC86"));
                pDialog.setTitleText("Loading");
                pDialog.setCancelable(false);
                pDialog.show();
```
