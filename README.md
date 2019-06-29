# constraint-layout-2.0.0-beta2-bug

In Constraintlayout 2.0.0-beta1 the layout was showing correctly. When I update to 2.0.0-beta2 the list items are not shown anymore in the device. 

Ps. In my "real" project I have some ads loading in the bottom of the screen. 
After a while they update, causing a new layout pass to happen. 
Then the list items in the Scrollview are shown again...?

# How to reproduce
Change the version in app to see the problem

# 2.0.0-beta1 layout
![2.0.0-beta1 layout](https://github.com/ptornhult/constraint-layout-2.0.0-beta2-bug/blob/master/images/Screenshot_1561824526.png)

# 2.0.0-beta2 layout
![2.0.0-beta2 layout](https://github.com/ptornhult/constraint-layout-2.0.0-beta2-bug/blob/master/images/Screenshot_1561824434.png)