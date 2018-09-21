# ngx_pagespeed
Dynamic pagespeed module binary compatible with Debian Stretch for Nginx 1.10.3
pagespeed_ngx_1.13.35.2 + Debian 9 standard distro of nginx-1.10.3

Simply copy the module to the server and include it via:
load_module path_to_modules/ngx_pagespeed.so;

Make sure you test compatibility by typing nginx -t prior to restarting the server.
