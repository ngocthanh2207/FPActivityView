FPActivityView
==============



## How to use
============

``` objective-c
UIImage* activityImage = [[UIImage imageNamed:@"download-bar"] resizableImageWithCapInsets:UIEdgeInsetsMake(0, 1, 0, 1)];
FPActivityView* activityView = [[FPActivityView alloc] initWithFrame:CGRectMake(0, 0, self.view.frame.size.width, 4) andActivityBar:activityImage];
[activityView start];
[self.view addSubview:activityView];
```


## Requires
============
ARC  
QuartzCore






## License

FPActivityView is available under the MIT license. See the LICENSE file for more info.
