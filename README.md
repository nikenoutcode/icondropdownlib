# icondropdownlib

## add this library on your app level build.gradle

    ```
        implementation 'com.github.nikenoutcode:icondropdownlib:1.0.0'

    ```

## add this line on settings.gradle
     ```
             maven { url 'https://jitpack.io' }

     ```

 for Example:

        ```
        dependencyResolutionManagement {
            repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
            repositories {
                google()
                mavenCentral()
                maven { url 'https://jitpack.io' }
            }
        }

        ```

## steps to use this component

```
IconDropDown(
              dropDownList = countryList,
              hint = "Select Country",
              shouldShowIcon = false,
              shouldShowDropDownIcon = false,
              onValueSelected = {

              }
)
```
