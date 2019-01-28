



####Global dependencies you may need:

* `npm install -g ionic cordova`
* DevApp
* Appflow


- We have to manually run the app on an emulator

####Some things to know:


* ionic doesn't yet have support for Xcode 10.1+, so you need to build using the `legacyBuildSystem`. There are two options for this that are explained on [this thread](https://github.com/apache/cordova-ios/issues/407)

` ionic cordova build ios -- --buildFlag="-UseModernBuildSystem=0"`



#### Other global dependencies:


`npm install -g ios-sim`

`npm install -g ios-deploy`


Le links on this post can be useful to know more about specific tricks for ionic: https://www.joshmorony.com/what-to-expect-when-ionic-4-is-released/