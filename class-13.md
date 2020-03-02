# Class13

# Local Stroge
local storage is one of the areas where native client applications have held an advantage over web applications.

### three potentially dealbreaking:-
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

#### what users or programmers really want :-
1. a lot of storage space
2. on the client
3. that persists beyond a page refresh
4. and isn’t transmitted to the server

#### what is userData ?
allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.)

### HTML5 STORGE SUPPORT
TYPE|AMOUNT
----|------
IE|8.0+
FIREFOX|3.5+
SAFARI|4.0+
CHROME|4.0+
OPERA|10.5+
IPHONE|2.0+
ANDROID|2.0+

### USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string.

### TRACKING CHANGES TO THE HTML5 STORAGE AREA
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

### STORAGEEVENT OBJECT
PROPERTY|TYPE|DESCRIPTION
--------|----|-----------
key|string|the named key that was added, removed, or modified
oldValue|any|the previous value (now overwritten), or null if a new item was added
newValue|any|the new value, or null if an item was removed
url*|string|the page which called a method that triggered this change

### WEB SQL DATABASE SUPPORT

IE|FIREFOX|SAFARI|CHROME|OPERA|IPHONE|ANDROID
--|-------|------|------|-----|------|-------
.|.|4.0+|4.0+|10.5+|3.0+|2.0+


### Web SQL Database:
1. Web SQL Database specification
2. Introducing Web SQL Databases
3. Web Database demonstration
4. persistence.js, an “asynchronous JavaScript ORM” built on top of Web SQL Database and Gears





