# Anroid Call Recorder

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Call%20Recorder-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/4544)

Android incomig and outgoing call recorder at any time.

# How to Use

```
callRecord = new CallRecord.Builder(this)
      .setRecordFileName("CallRecordFileName") //anything
      .setRecordDirName("CallRecordDirName")  //anything
      .build();
                
callRecord.startCallReceiver();
```

OR

```
callRecord = CallRecord.init(this);
```

**Stop CallRecord**

```
callRecord.stopCallReceiver();
```


---

If you wish run in Service;

```
callRecord = new CallRecord.Builder(this)
       .setRecordDirName("ServiceRecordDirName")
       .setRecordFileName("ServiceRecordFileName")
       .buildService();

callRecord.startCallRecordService();
```



# Installation

Gradle

Add it as a dependency in your app's build.gradle file

```
compile 'com.aykuttasil:callrecord:1.0.1'

```


# Sample

You can see sample project in app folder.


# License 

```
Copyright 2016 aykuttasil - Aykut Asil

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```




