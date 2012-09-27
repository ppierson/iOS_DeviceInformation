Description
=======
<p>DeviceInformation is an iOS class created to make it easier to get the device platform, iOS version, and app bundle version. It is also used to check the iOS version at runtime to perform version specific functionality.
</p>

Sample
=======
```
	[DeviceInformation platform]; //returns the platform code for current device (Ex: "iPhone4,1")
	
	[DeviceInformation getPlatformVersion]; //returns a string representing the current device (Ex: "iPhone 4S")
	
	[DeviceInformation getIOSVersion]; //returns a string representing iOS version (Ex: "5.1") 
	
	[DeviceInformation getBundleVersion]; //returns a string representing the bundle version of the application (Ex: "2.0(201)" - 2.0 is bundle version, (201) is build version)
	
	if(SYSTEM_VESRION_EQUAL_TO(@"5.1")) NSLog(@"Current device has iOS version 5.1");
	if(SYSTEM_VESRION_GREATER_THAN(@"5.1")) NSLog(@"Current device iOS version is greater than 5.1");
	if(SYSTEM_VERSION_GREATER_THAN_OR_EQUAL_TO(@"5.1")) NSLog(@"Current is or may be higher than 5.1");
	if(SYSTEM_VERSION_LESS_THAN(@"5.0")) NSLog(@"Cannot use iOS 5 functionality");
	if(SYSTEM_VERSION_LESS_THAN_OR_EQUAL_TO(@"6.0")) NSLog(@"App may use functionality up to iOS version 6.0");
```

License
=======
```
//
//  Copyright (c) 2012 Patrick Pierson
//  
//  Permission is hereby granted, free of charge, to any person obtaining a copy
//  of this software and associated documentation files (the "Software"),
//  to deal in the Software without restriction, including without limitation the
//  rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
//  sell copies of the Software, and to permit persons to whom the Software is
//  furnished to do so, subject to the following conditions:
//  
//  The above copyright notice and this permission notice shall be included in all
//  copies or substantial portions of the Software.
//  
//  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
//  INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
//  PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
//  HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
//  OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
//  SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
//

```


	