# Domain-name-resolution
域名解析相关

1.域名解析为从右向左解析<br>

      如https://www.google.com.
        //谷歌子域名
        http://translate.google.com/

最先解析的是最右边的  .  为公网  ，然后依次向左解析
然而大多数情况下不用向公网请求，而是向运营商本地的域名，所以一般不用加 " .  "


localhost=172.0.0.1     dns=ip地址

