# drawMinDmg
A lua script for Aimware to draw minimum damage. 
Draws minimum damage per gun/shared configuration. The problem is that I think that the rbot_shared_mode variable is broken wherefore I had to make a detour around that:
for this to work properly you have to set your arm scale to above 1%(2% should be enough) in your Shared config. (It will not work if you just switch between shared/per gun in the same config, you need 2 different configs).

Maybe I am doing something wrong, but oh well.
Please let me know if there is a better way to determine whether the configuration is shared or not. 

Video:
https://www.youtube.com/watch?v=KTy0Cpp4XYg
(It draws it on the left side, sorry about the 2500kbps video)
