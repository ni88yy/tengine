
Introduction
============

Tengine is a web server originated by [Taobao](http://en.wikipedia.org/wiki/Taobao), the largest e-commerce website in Asia. It is based on the popular [Nginx](http://nginx.org) HTTP server and has many advanced features. Tengine has been proven very stable and efficient on the top 100 websites, including [taobao.com](http://www.taobao.com) and [tmall.com](http://www.tmall.com).

Tengine has been an open source project since December 2011.

Features
========

* All features of Nginx-1.0.15 are inherited, i.e. it is 100% compatible with Nginx.
* Input body filter support. It's quite handy to write Web Application Firewalls by using this mechanism.
* Logging enhancement. Syslog (local and remote), pipe logging and log sampling are supported.
* Protecting server in case system load or memory use goes too high.
* Multiple CSS or JavaScript requests can be combined into one request to reduce downloading time.
* Proactive health checks of upstream servers can be performed.
* The number of worker processes and CPU affinities can be set automatically.
* The limit_req module is enhanced with white list support and more conditions are allowed in a single location.
* Diagnostic information to tell the server where the error happened.
* More user friendly command lines. e.g. showing all compiled-in modules and supported directives.
* Expiration times can be specified for certain MIME types.
* Error pages can be reset to 'default'.
* ...

Mail list
=========

* Chinese: [http://code.taobao.org/mailman/listinfo/tengine-cn](http://code.taobao.org/mailman/listinfo/tengine-cn)
* English: [http://code.taobao.org/mailman/listinfo/tengine](http://code.taobao.org/mailman/listinfo/tengine)
