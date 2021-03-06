#Delphi Frost Glass Control

A little pet project ;-) 

It's a frost glass (blur+background coloring) Delphi Firemonkey component for use with all Firemonkey platforms. This component is just like the IOS 8/10 popup sound control and IOS Control Centre (bottom slide up) but with a bonus: you can give it a nice background color tint. I tested it on Delphi Berlin 10.1 update 2.


### About the project
Performance is utterly important here, it was/is a challenge to get this component as smooth as possible.  If you think you can shave off some milli seconds? Let me know!

In some cases it is wise to use the build-in cache feature and somtimes it's not (like with changing backgrounds or with slide popins because you want continue updates). Anyway you can test for yourself via the included test project. Just resize the form at runtime to see the speed result in ms in the lisbox via the onTickEvent. I added a build-in TStopwatch to measure performance. If you click on the image a Frost Glass will popup.

Example:
![Frost-Glass Example](https://github.com/Spelt/Frost-Glass/blob/master/misc/screenshot.png)

The inspiration for this component are the IOS 8/10 popup sound controls and IOS Control Centre (bottom slide up). Code inspiration comes from this stack overflow post: http://stackoverflow.com/questions/23898849/ios7-blurred-overlay-in-delphi-xe6


###Changes
- v1 Date: 2017/03/05 
	- Initial upload to github


###Features
- Demo project

Properties available
- Blur (Gaussian) enabled 
- FrostColor
- FrostColor Enabled
- Caching


Important inherited properties of TRectangle which will make it look more great.
- Border functionality
- Corner functionality


###Licence
Frost Glass is released under the Apache 2.0 license.  A copy of the Apache 2.0 license can be found here: http://www.apache.org/licenses/LICENSE-2.0

