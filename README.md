
> This is 'iw', a tool to use nl80211.


> To build iw, just enter 'make'. If that fails, set the
PKG_CONFIG_PATH environment variable to allow the Makefile
to find libnl.


> 'iw' is currently maintained at http://git.sipsolutions.net/iw.git/,
some more documentation is available at
http://wireless.kernel.org/en/users/Documentation/iw.

> Please send all patches to Johannes Berg <johannes@sipsolutions.net>
and CC linux-wireless@vger.kernel.org for community review.

---------------------------


这是我在树莓派3，操作系统为centos7.1上编译的iw模块

```bash
[root@node iw-3.15]#./iw list
[root@node iw-3.15]#./iw
```

可以将iw添加至`/sbin`目录下
```bash
[root@node iw-3.15]# cp iw /sbin/
[root@node iw-3.15]# iw list
```
