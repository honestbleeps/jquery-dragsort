jquery-dragsort
===============

Since the jquery-dragsort plugin at codeplex is no longer maintained, and it's incompatible with jQuery 1.9.1, I'm providing an updated / compatible version here.

Specifically, jquery-dragsort used $.browser detection, which is no longer supported in jQuery 1.9+ and is also unnecessary at this point.

Worthy of note: The Firefox and Safari specific mousewheel behavior from the original plugin has been removed in the interest of cross-browser consistency (and because it was the main cause of incompatibility).