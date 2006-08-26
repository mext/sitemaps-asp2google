ASP.NET to Google sitemap converter.
------------------------------------

The utility allows to convert ASP.NET sitemaps to Google sitemaps.

**** GUI mode *****
1. Launch the utility.
2. Specify path to input and output sitemaps, and domain name.
3. Start conversion process.

Utility saves entered values between sessions.

**** "Command-line" mode ****
If the utility launched with three (or more) command line arguments then GUI is not shown and conversion performed silently. 

First argument must be pathname to ASP.NET sitemap.
Second argument is a domain name.
Third argument is pathname of output Google sitemap.

Fourth (optional) argument is boolean value, and means if the utility should be silent if error happened. If the argument is specified it should be boolean value ("true" or "false" - CASE-SENSITIVE!!!). Default is "false".

Example:
 > SitemapConverter.exe c:\sandbox\mysite\web.sitemap http://www.mysite.com c:\output\sitemap.xml true