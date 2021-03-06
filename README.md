# adapt-cordova

Adds the relevant cordova config to a module so that mobile applications can be built easily.

## Authoring tool installation

Download repository as a zip file and import the extension into the adapt authoring tool (v0.2.0+). In the authoring tool you can configure the extension from the configuration settings screen of a page on a course. 

## Command-line installation

Get the code directly from GitHub, either downloading the zip file or cloning the repository.

To play around with it, the easiest thing is to create a course:

```
 adapt create course myTestCourse
 cd myTestCourse
 grunt build
 cd src/extensions
 git clone https://github.com/theodi/adapt-odi-cordova
```

The configuration shown in the example.json file is strait forward and for futher information on the field definitions please refer to the documetion for the config.xml file in a cordova project at docs.

https://cordova.apache.org/docs/en/latest/config_ref/
