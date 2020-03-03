# LOCAL STORAGE FOR WEB APPLICATIONS

**Persistent  local storage is one of the factors why native client applications have held an advantage over web applications.**

**Cookies are used by web applications for persistent local storage of small amounts of data, but they have 3 main downsides**

## Downsides of Cookies: 

1. **Slowing**
    Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
2. **Sending unencrypted data**
    Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
3. **Limited storage**
    Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## HTML 5 Storage

**HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser.**