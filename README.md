jquery-scrollstop
=================

James Padolsey's jQuery scrollstop plugin that fires an event when scrolling stops for minimum amount of time.

Originally code copied from http://james.padolsey.com/javascript/special-scroll-events-for-jquery/


****

jQuery.event.handle.apply is not available in jQuery 1.7+ so I repleced it with a call to jQuery.event.simulate
seems to work for me in conjunction with [tuupola's](https://github.com/tuupola/jquery_lazyload "jquery lazyload") lazyload.