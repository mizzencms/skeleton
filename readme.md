#MizzenCMS Lite

This is a "work in progress" repo of MizzenCMS Lite aka MizzenLite.

> Please note that the CMS is not even beta and code here may,
and will be changed in a way that is likely to break bc.
> Content of the modules directory will be removed from this repo in the near
future.
> You should have no need to use it at the moment, however if you are curious
read on.

###Installation
----

If you insist on installing this locally, clone the repo and do:

```bash
$ cd <folder_name>
$ composer install
\# following line is optional as submodules come and go
$ git submodule init && git submodule update
$ cp config/config.json.sample config/config.json
$ sudo chmod 0777 var
```

This should provide you with a working copy of a mizzencms