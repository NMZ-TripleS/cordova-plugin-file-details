#  Change Logs

## Template

### {Tag - 1.0.0} ({Date - Month Day, Year})

* Details...

## Entries

### 1.0.0 (March 10, 2023)

**Feature:**

* Created the initial plugin along with the necessary documentation and folders.
* Currently only implemented for image files using exif.
* Receives the file path then retreiving the necessary details.

### 1.0.1 (March 13, 2023)

**Feature:**

Removed the altitude from the information.
Applied a conversion from DMS to a normal GPS location for android.
Replaced the package of exifinterface to the latest one and change the constructor to use input stream.
Parse the file path to input stream to support both file or content.
Fixed the wrong success callback for iOS.