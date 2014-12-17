VMNumberScrollAnimatedView
==========================

Swift port of JTNumberScrollAnimatedView
Objective-C implementation [by @jonathantribouharet](https://github.com/jonathantribouharet/JTNumberScrollAnimatedView)

**Updated for XCode 6.1 and iOS 8.1.1**


----------


Screenshot 
==========

(Taken from Jonathan's github page)

![Example](https://dl.dropboxusercontent.com/s/0oftp8vpkl9fx9l/VMNumberScrollAnimatedView.gif)

Sample code
-----------

		@IBOutlet var animatedView:VMNumberScrollAnimatedView? = VMNumberScrollAnimatedView?()

		override func viewDidLoad() {
        	super.viewDidLoad()
        
	        self.animatedView?.textColor = UIColor.whiteColor()
        
    	    self.animatedView?.font = UIFont(name: "HelveticaNeue-Bold", size: 42)!
        	self.animatedView?.minLenght = 3
        
    		}

    	 @IBAction func start(){
    
        	self.animatedView?.setValue(NSNumber(int: rand()%5000))
	        self.animatedView?.startAnimation()
    
    		}


----------

Contributors 
---------------
***All contributors will receive virtual high fives from me and for the heck of it lets forget you are a south paw***

![enter image description here](https://dl.dropbox.com/s/n32dq4fle8fh7l4/internet-high-five.jpg)


----------
Other Repos you might like
--------------------------
1) https://github.com/varshylmobile/LocationManager

> CLLocationManager wrapper in Swift, performs location update,
> geocoding and reverse geocoding using Apple and Google service
> 

2) https://github.com/varshylmobile/MapManager

> Map manager is a MapKit wrapper in Swift to provide route direction
> drawing

3) https://github.com/varshylmobile/VMXMLParser

> NSXMLParser wrapper in Swift

4) https://github.com/varshylmobile/RateMyApp

> RateMyApp is a Swift class to provide gentle reminders to app user to
> rate your app

5) https://github.com/varshylmobile/VMFloatLabel

> Swift based UITextField subclass with floating labels


6) https://github.com/varshylmobile/TableViewCellFlip

> Vertical and Horizontal flip animation for table view cell

Contact Us
---------------

Have any questions or suggestions feel free to write at jimmy@varshyl.com (Jimmy Jose)
http://www.varshylmobile.com/

----------
## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.