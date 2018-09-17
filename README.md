# WEB startkit

Prerequisites:

* tmux
* python-3.6
* pip
* node
* yarn

If you don't have/use CBSD/Reggae, you should download backend and frontend:

```
# mkdir services
# git clone https://github.com/mekanix/backend-startkit services/backend
# git clone https://github.com/mekanix/frontend-startkit services/frontend
# echo 'HTTP_PROXY=localhost:5000' >services/frontend/project.conf
# bin/devel.sh
```

If you do use CBSD/Reggae, you should only run:
```
# echo 'DEVEL_MODE=YES' >vars.mk
# make devel
```

It will download backend and frontend repos for you and do the rest of the magic.
