# lua-docker

Minimal, automated, and up-to-date Docker images for different Lua and LuaJIT versions.

Provides variants for:

- Debian, Alpine, Ubuntu, and CentOS base images
- With LuaRocks
- LuaJIT
- LuaJIT built with Lua 5.2 compatibility mode

This repo provides the source for both Lua and LuaJIT images. The different images can be found at:

- [`nickblah/lua`](https://hub.docker.com/r/nickblah/lua/): Lua images.
- [`nickblah/luajit`](https://hub.docker.com/r/nickblah/luajit/): LuaJIT images.

## Supported Tags and Respective Dockerfile Links

### [`nickblah/lua`](https://hub.docker.com/r/nickblah/lua/)
- `5.4-alpha-rc`, `5.4-alpha-rc-stretch`, `5.4.0-alpha-rc2`, `5.4.0-alpha-rc2-stretch`: [lua-5.4-alpha-rc/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/stretch/Dockerfile)
- `5.4-alpha-rc-jessie`, `5.4.0-alpha-rc2-jessie`: [lua-5.4-alpha-rc/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/jessie/Dockerfile)
- `5.4-alpha-rc-luarocks`, `5.4-alpha-rc-luarocks-stretch`, `5.4.0-alpha-rc2-luarocks`, `5.4.0-alpha-rc2-luarocks-stretch`: [lua-5.4-alpha-rc/luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-stretch/Dockerfile)
- `5.4-alpha-rc-luarocks-jessie`, `5.4.0-alpha-rc2-luarocks-jessie`: [lua-5.4-alpha-rc/luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-jessie/Dockerfile)
- `5.4-alpha-rc-alpine`, `5.4-alpha-rc-alpine3.9`, `5.4.0-alpha-rc2-alpine`, `5.4.0-alpha-rc2-alpine3.9`: [lua-5.4-alpha-rc/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/alpine3.9/Dockerfile)
- `5.4-alpha-rc-luarocks-alpine`, `5.4-alpha-rc-luarocks-alpine3.9`, `5.4.0-alpha-rc2-luarocks-alpine`, `5.4.0-alpha-rc2-luarocks-alpine3.9`: [lua-5.4-alpha-rc/luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-alpine3.9/Dockerfile)
- `5.4-alpha-rc-bionic`, `5.4-alpha-rc-ubuntu`, `5.4.0-alpha-rc2-bionic`, `5.4.0-alpha-rc2-ubuntu`: [lua-5.4-alpha-rc/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/bionic/Dockerfile)
- `5.4-alpha-rc-xenial`, `5.4.0-alpha-rc2-xenial`: [lua-5.4-alpha-rc/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/xenial/Dockerfile)
- `5.4-alpha-rc-luarocks-bionic`, `5.4-alpha-rc-luarocks-ubuntu`, `5.4.0-alpha-rc2-luarocks-bionic`, `5.4.0-alpha-rc2-luarocks-ubuntu`: [lua-5.4-alpha-rc/luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-bionic/Dockerfile)
- `5.4-alpha-rc-luarocks-xenial`, `5.4.0-alpha-rc2-luarocks-xenial`: [lua-5.4-alpha-rc/luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-xenial/Dockerfile)
- `5.4-alpha-rc-centos`, `5.4-alpha-rc-centos7`, `5.4.0-alpha-rc2-centos`, `5.4.0-alpha-rc2-centos7`: [lua-5.4-alpha-rc/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/centos7/Dockerfile)
- `5.4-alpha-rc-centos6`, `5.4.0-alpha-rc2-centos6`: [lua-5.4-alpha-rc/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/centos6/Dockerfile)
- `5.4-alpha-rc-luarocks-centos`, `5.4-alpha-rc-luarocks-centos7`, `5.4.0-alpha-rc2-luarocks-centos`, `5.4.0-alpha-rc2-luarocks-centos7`: [lua-5.4-alpha-rc/luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-centos7/Dockerfile)
- `5.4-alpha-rc-luarocks-centos6`, `5.4.0-alpha-rc2-luarocks-centos6`: [lua-5.4-alpha-rc/luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.4-alpha-rc/luarocks-centos6/Dockerfile)
- `5`, `5-stretch`, `5.3`, `5.3-stretch`, `5.3.5`, `5.3.5-stretch`, `latest`: [lua-5.3/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/stretch/Dockerfile)
- `5-jessie`, `5.3-jessie`, `5.3.5-jessie`: [lua-5.3/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/jessie/Dockerfile)
- `5-luarocks`, `5-luarocks-stretch`, `5.3-luarocks`, `5.3-luarocks-stretch`, `5.3.5-luarocks`, `5.3.5-luarocks-stretch`, `luarocks`: [lua-5.3/luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-stretch/Dockerfile)
- `5-luarocks-jessie`, `5.3-luarocks-jessie`, `5.3.5-luarocks-jessie`: [lua-5.3/luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-jessie/Dockerfile)
- `5-alpine`, `5-alpine3.9`, `5.3-alpine`, `5.3-alpine3.9`, `5.3.5-alpine`, `5.3.5-alpine3.9`, `alpine`: [lua-5.3/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/alpine3.9/Dockerfile)
- `5-luarocks-alpine`, `5-luarocks-alpine3.9`, `5.3-luarocks-alpine`, `5.3-luarocks-alpine3.9`, `5.3.5-luarocks-alpine`, `5.3.5-luarocks-alpine3.9`, `luarocks-alpine`: [lua-5.3/luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-alpine3.9/Dockerfile)
- `5-bionic`, `5-ubuntu`, `5.3-bionic`, `5.3-ubuntu`, `5.3.5-bionic`, `5.3.5-ubuntu`, `ubuntu`: [lua-5.3/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/bionic/Dockerfile)
- `5-xenial`, `5.3-xenial`, `5.3.5-xenial`: [lua-5.3/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/xenial/Dockerfile)
- `5-luarocks-bionic`, `5-luarocks-ubuntu`, `5.3-luarocks-bionic`, `5.3-luarocks-ubuntu`, `5.3.5-luarocks-bionic`, `5.3.5-luarocks-ubuntu`, `luarocks-ubuntu`: [lua-5.3/luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-bionic/Dockerfile)
- `5-luarocks-xenial`, `5.3-luarocks-xenial`, `5.3.5-luarocks-xenial`: [lua-5.3/luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-xenial/Dockerfile)
- `5-centos`, `5-centos7`, `5.3-centos`, `5.3-centos7`, `5.3.5-centos`, `5.3.5-centos7`, `centos`: [lua-5.3/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/centos7/Dockerfile)
- `5-centos6`, `5.3-centos6`, `5.3.5-centos6`: [lua-5.3/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/centos6/Dockerfile)
- `5-luarocks-centos`, `5-luarocks-centos7`, `5.3-luarocks-centos`, `5.3-luarocks-centos7`, `5.3.5-luarocks-centos`, `5.3.5-luarocks-centos7`, `luarocks-centos`: [lua-5.3/luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-centos7/Dockerfile)
- `5-luarocks-centos6`, `5.3-luarocks-centos6`, `5.3.5-luarocks-centos6`: [lua-5.3/luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.3/luarocks-centos6/Dockerfile)
- `5.2`, `5.2-stretch`, `5.2.4`, `5.2.4-stretch`: [lua-5.2/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/stretch/Dockerfile)
- `5.2-jessie`, `5.2.4-jessie`: [lua-5.2/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/jessie/Dockerfile)
- `5.2-luarocks`, `5.2-luarocks-stretch`, `5.2.4-luarocks`, `5.2.4-luarocks-stretch`: [lua-5.2/luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-stretch/Dockerfile)
- `5.2-luarocks-jessie`, `5.2.4-luarocks-jessie`: [lua-5.2/luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-jessie/Dockerfile)
- `5.2-alpine`, `5.2-alpine3.9`, `5.2.4-alpine`, `5.2.4-alpine3.9`: [lua-5.2/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/alpine3.9/Dockerfile)
- `5.2-luarocks-alpine`, `5.2-luarocks-alpine3.9`, `5.2.4-luarocks-alpine`, `5.2.4-luarocks-alpine3.9`: [lua-5.2/luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-alpine3.9/Dockerfile)
- `5.2-bionic`, `5.2-ubuntu`, `5.2.4-bionic`, `5.2.4-ubuntu`: [lua-5.2/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/bionic/Dockerfile)
- `5.2-xenial`, `5.2.4-xenial`: [lua-5.2/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/xenial/Dockerfile)
- `5.2-luarocks-bionic`, `5.2-luarocks-ubuntu`, `5.2.4-luarocks-bionic`, `5.2.4-luarocks-ubuntu`: [lua-5.2/luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-bionic/Dockerfile)
- `5.2-luarocks-xenial`, `5.2.4-luarocks-xenial`: [lua-5.2/luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-xenial/Dockerfile)
- `5.2-centos`, `5.2-centos7`, `5.2.4-centos`, `5.2.4-centos7`: [lua-5.2/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/centos7/Dockerfile)
- `5.2-centos6`, `5.2.4-centos6`: [lua-5.2/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/centos6/Dockerfile)
- `5.2-luarocks-centos`, `5.2-luarocks-centos7`, `5.2.4-luarocks-centos`, `5.2.4-luarocks-centos7`: [lua-5.2/luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-centos7/Dockerfile)
- `5.2-luarocks-centos6`, `5.2.4-luarocks-centos6`: [lua-5.2/luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.2/luarocks-centos6/Dockerfile)
- `5.1`, `5.1-stretch`, `5.1.5`, `5.1.5-stretch`: [lua-5.1/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/stretch/Dockerfile)
- `5.1-jessie`, `5.1.5-jessie`: [lua-5.1/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/jessie/Dockerfile)
- `5.1-luarocks`, `5.1-luarocks-stretch`, `5.1.5-luarocks`, `5.1.5-luarocks-stretch`: [lua-5.1/luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-stretch/Dockerfile)
- `5.1-luarocks-jessie`, `5.1.5-luarocks-jessie`: [lua-5.1/luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-jessie/Dockerfile)
- `5.1-alpine`, `5.1-alpine3.9`, `5.1.5-alpine`, `5.1.5-alpine3.9`: [lua-5.1/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/alpine3.9/Dockerfile)
- `5.1-luarocks-alpine`, `5.1-luarocks-alpine3.9`, `5.1.5-luarocks-alpine`, `5.1.5-luarocks-alpine3.9`: [lua-5.1/luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-alpine3.9/Dockerfile)
- `5.1-bionic`, `5.1-ubuntu`, `5.1.5-bionic`, `5.1.5-ubuntu`: [lua-5.1/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/bionic/Dockerfile)
- `5.1-xenial`, `5.1.5-xenial`: [lua-5.1/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/xenial/Dockerfile)
- `5.1-luarocks-bionic`, `5.1-luarocks-ubuntu`, `5.1.5-luarocks-bionic`, `5.1.5-luarocks-ubuntu`: [lua-5.1/luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-bionic/Dockerfile)
- `5.1-luarocks-xenial`, `5.1.5-luarocks-xenial`: [lua-5.1/luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-xenial/Dockerfile)
- `5.1-centos`, `5.1-centos7`, `5.1.5-centos`, `5.1.5-centos7`: [lua-5.1/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/centos7/Dockerfile)
- `5.1-centos6`, `5.1.5-centos6`: [lua-5.1/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/centos6/Dockerfile)
- `5.1-luarocks-centos`, `5.1-luarocks-centos7`, `5.1.5-luarocks-centos`, `5.1.5-luarocks-centos7`: [lua-5.1/luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-centos7/Dockerfile)
- `5.1-luarocks-centos6`, `5.1.5-luarocks-centos6`: [lua-5.1/luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.1/luarocks-centos6/Dockerfile)
- `5.0`, `5.0-stretch`, `5.0.3`, `5.0.3-stretch`: [lua-5.0/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/stretch/Dockerfile)
- `5.0-jessie`, `5.0.3-jessie`: [lua-5.0/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/jessie/Dockerfile)
- `5.0-alpine`, `5.0-alpine3.9`, `5.0.3-alpine`, `5.0.3-alpine3.9`: [lua-5.0/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/alpine3.9/Dockerfile)
- `5.0-bionic`, `5.0-ubuntu`, `5.0.3-bionic`, `5.0.3-ubuntu`: [lua-5.0/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/bionic/Dockerfile)
- `5.0-xenial`, `5.0.3-xenial`: [lua-5.0/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/xenial/Dockerfile)
- `5.0-centos`, `5.0-centos7`, `5.0.3-centos`, `5.0.3-centos7`: [lua-5.0/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/centos7/Dockerfile)
- `5.0-centos6`, `5.0.3-centos6`: [lua-5.0/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/lua-5.0/centos6/Dockerfile)
### [`nickblah/luajit`](https://hub.docker.com/r/nickblah/luajit/)
- `2.1-beta`, `2.1-beta-stretch`, `2.1.0-beta3`, `2.1.0-beta3-stretch`: [luajit-2.1-beta/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/stretch/Dockerfile)
- `2.1-beta-jessie`, `2.1.0-beta3-jessie`: [luajit-2.1-beta/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/jessie/Dockerfile)
- `2.1-beta-luarocks`, `2.1-beta-luarocks-stretch`, `2.1.0-beta3-luarocks`, `2.1.0-beta3-luarocks-stretch`: [luajit-2.1-beta/luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-stretch/Dockerfile)
- `2.1-beta-luarocks-jessie`, `2.1.0-beta3-luarocks-jessie`: [luajit-2.1-beta/luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-jessie/Dockerfile)
- `2.1-beta-lua52compat`, `2.1-beta-lua52compat-stretch`, `2.1.0-beta3-lua52compat`, `2.1.0-beta3-lua52compat-stretch`: [luajit-2.1-beta/lua52compat-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-stretch/Dockerfile)
- `2.1-beta-lua52compat-jessie`, `2.1.0-beta3-lua52compat-jessie`: [luajit-2.1-beta/lua52compat-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-jessie/Dockerfile)
- `2.1-beta-lua52compat-luarocks`, `2.1-beta-lua52compat-luarocks-stretch`, `2.1.0-beta3-lua52compat-luarocks`, `2.1.0-beta3-lua52compat-luarocks-stretch`: [luajit-2.1-beta/lua52compat-luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-stretch/Dockerfile)
- `2.1-beta-lua52compat-luarocks-jessie`, `2.1.0-beta3-lua52compat-luarocks-jessie`: [luajit-2.1-beta/lua52compat-luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-jessie/Dockerfile)
- `2.1-beta-alpine`, `2.1-beta-alpine3.9`, `2.1.0-beta3-alpine`, `2.1.0-beta3-alpine3.9`: [luajit-2.1-beta/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/alpine3.9/Dockerfile)
- `2.1-beta-luarocks-alpine`, `2.1-beta-luarocks-alpine3.9`, `2.1.0-beta3-luarocks-alpine`, `2.1.0-beta3-luarocks-alpine3.9`: [luajit-2.1-beta/luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-alpine3.9/Dockerfile)
- `2.1-beta-lua52compat-alpine`, `2.1-beta-lua52compat-alpine3.9`, `2.1.0-beta3-lua52compat-alpine`, `2.1.0-beta3-lua52compat-alpine3.9`: [luajit-2.1-beta/lua52compat-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-alpine3.9/Dockerfile)
- `2.1-beta-lua52compat-luarocks-alpine`, `2.1-beta-lua52compat-luarocks-alpine3.9`, `2.1.0-beta3-lua52compat-luarocks-alpine`, `2.1.0-beta3-lua52compat-luarocks-alpine3.9`: [luajit-2.1-beta/lua52compat-luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-alpine3.9/Dockerfile)
- `2.1-beta-bionic`, `2.1-beta-ubuntu`, `2.1.0-beta3-bionic`, `2.1.0-beta3-ubuntu`: [luajit-2.1-beta/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/bionic/Dockerfile)
- `2.1-beta-xenial`, `2.1.0-beta3-xenial`: [luajit-2.1-beta/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/xenial/Dockerfile)
- `2.1-beta-luarocks-bionic`, `2.1-beta-luarocks-ubuntu`, `2.1.0-beta3-luarocks-bionic`, `2.1.0-beta3-luarocks-ubuntu`: [luajit-2.1-beta/luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-bionic/Dockerfile)
- `2.1-beta-luarocks-xenial`, `2.1.0-beta3-luarocks-xenial`: [luajit-2.1-beta/luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-xenial/Dockerfile)
- `2.1-beta-lua52compat-bionic`, `2.1-beta-lua52compat-ubuntu`, `2.1.0-beta3-lua52compat-bionic`, `2.1.0-beta3-lua52compat-ubuntu`: [luajit-2.1-beta/lua52compat-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-bionic/Dockerfile)
- `2.1-beta-lua52compat-xenial`, `2.1.0-beta3-lua52compat-xenial`: [luajit-2.1-beta/lua52compat-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-xenial/Dockerfile)
- `2.1-beta-lua52compat-luarocks-bionic`, `2.1-beta-lua52compat-luarocks-ubuntu`, `2.1.0-beta3-lua52compat-luarocks-bionic`, `2.1.0-beta3-lua52compat-luarocks-ubuntu`: [luajit-2.1-beta/lua52compat-luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-bionic/Dockerfile)
- `2.1-beta-lua52compat-luarocks-xenial`, `2.1.0-beta3-lua52compat-luarocks-xenial`: [luajit-2.1-beta/lua52compat-luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-xenial/Dockerfile)
- `2.1-beta-centos`, `2.1-beta-centos7`, `2.1.0-beta3-centos`, `2.1.0-beta3-centos7`: [luajit-2.1-beta/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/centos7/Dockerfile)
- `2.1-beta-centos6`, `2.1.0-beta3-centos6`: [luajit-2.1-beta/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/centos6/Dockerfile)
- `2.1-beta-luarocks-centos`, `2.1-beta-luarocks-centos7`, `2.1.0-beta3-luarocks-centos`, `2.1.0-beta3-luarocks-centos7`: [luajit-2.1-beta/luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-centos7/Dockerfile)
- `2.1-beta-luarocks-centos6`, `2.1.0-beta3-luarocks-centos6`: [luajit-2.1-beta/luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/luarocks-centos6/Dockerfile)
- `2.1-beta-lua52compat-centos`, `2.1-beta-lua52compat-centos7`, `2.1.0-beta3-lua52compat-centos`, `2.1.0-beta3-lua52compat-centos7`: [luajit-2.1-beta/lua52compat-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-centos7/Dockerfile)
- `2.1-beta-lua52compat-centos6`, `2.1.0-beta3-lua52compat-centos6`: [luajit-2.1-beta/lua52compat-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-centos6/Dockerfile)
- `2.1-beta-lua52compat-luarocks-centos`, `2.1-beta-lua52compat-luarocks-centos7`, `2.1.0-beta3-lua52compat-luarocks-centos`, `2.1.0-beta3-lua52compat-luarocks-centos7`: [luajit-2.1-beta/lua52compat-luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-centos7/Dockerfile)
- `2.1-beta-lua52compat-luarocks-centos6`, `2.1.0-beta3-lua52compat-luarocks-centos6`: [luajit-2.1-beta/lua52compat-luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.1-beta/lua52compat-luarocks-centos6/Dockerfile)
- `2`, `2-stretch`, `2.0`, `2.0-stretch`, `2.0.5`, `2.0.5-stretch`, `latest`: [luajit-2.0/stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/stretch/Dockerfile)
- `2-jessie`, `2.0-jessie`, `2.0.5-jessie`: [luajit-2.0/jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/jessie/Dockerfile)
- `2-luarocks`, `2-luarocks-stretch`, `2.0-luarocks`, `2.0-luarocks-stretch`, `2.0.5-luarocks`, `2.0.5-luarocks-stretch`, `luarocks`: [luajit-2.0/luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-stretch/Dockerfile)
- `2-luarocks-jessie`, `2.0-luarocks-jessie`, `2.0.5-luarocks-jessie`: [luajit-2.0/luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-jessie/Dockerfile)
- `2-lua52compat`, `2-lua52compat-stretch`, `2.0-lua52compat`, `2.0-lua52compat-stretch`, `2.0.5-lua52compat`, `2.0.5-lua52compat-stretch`, `lua52compat`: [luajit-2.0/lua52compat-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-stretch/Dockerfile)
- `2-lua52compat-jessie`, `2.0-lua52compat-jessie`, `2.0.5-lua52compat-jessie`: [luajit-2.0/lua52compat-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-jessie/Dockerfile)
- `2-lua52compat-luarocks`, `2-lua52compat-luarocks-stretch`, `2.0-lua52compat-luarocks`, `2.0-lua52compat-luarocks-stretch`, `2.0.5-lua52compat-luarocks`, `2.0.5-lua52compat-luarocks-stretch`, `lua52compat-luarocks`: [luajit-2.0/lua52compat-luarocks-stretch/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-stretch/Dockerfile)
- `2-lua52compat-luarocks-jessie`, `2.0-lua52compat-luarocks-jessie`, `2.0.5-lua52compat-luarocks-jessie`: [luajit-2.0/lua52compat-luarocks-jessie/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-jessie/Dockerfile)
- `2-alpine`, `2-alpine3.9`, `2.0-alpine`, `2.0-alpine3.9`, `2.0.5-alpine`, `2.0.5-alpine3.9`, `alpine`: [luajit-2.0/alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/alpine3.9/Dockerfile)
- `2-luarocks-alpine`, `2-luarocks-alpine3.9`, `2.0-luarocks-alpine`, `2.0-luarocks-alpine3.9`, `2.0.5-luarocks-alpine`, `2.0.5-luarocks-alpine3.9`, `luarocks-alpine`: [luajit-2.0/luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-alpine3.9/Dockerfile)
- `2-lua52compat-alpine`, `2-lua52compat-alpine3.9`, `2.0-lua52compat-alpine`, `2.0-lua52compat-alpine3.9`, `2.0.5-lua52compat-alpine`, `2.0.5-lua52compat-alpine3.9`, `lua52compat-alpine`: [luajit-2.0/lua52compat-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-alpine3.9/Dockerfile)
- `2-lua52compat-luarocks-alpine`, `2-lua52compat-luarocks-alpine3.9`, `2.0-lua52compat-luarocks-alpine`, `2.0-lua52compat-luarocks-alpine3.9`, `2.0.5-lua52compat-luarocks-alpine`, `2.0.5-lua52compat-luarocks-alpine3.9`, `lua52compat-luarocks-alpine`: [luajit-2.0/lua52compat-luarocks-alpine3.9/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-alpine3.9/Dockerfile)
- `2-bionic`, `2-ubuntu`, `2.0-bionic`, `2.0-ubuntu`, `2.0.5-bionic`, `2.0.5-ubuntu`, `ubuntu`: [luajit-2.0/bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/bionic/Dockerfile)
- `2-xenial`, `2.0-xenial`, `2.0.5-xenial`: [luajit-2.0/xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/xenial/Dockerfile)
- `2-luarocks-bionic`, `2-luarocks-ubuntu`, `2.0-luarocks-bionic`, `2.0-luarocks-ubuntu`, `2.0.5-luarocks-bionic`, `2.0.5-luarocks-ubuntu`, `luarocks-ubuntu`: [luajit-2.0/luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-bionic/Dockerfile)
- `2-luarocks-xenial`, `2.0-luarocks-xenial`, `2.0.5-luarocks-xenial`: [luajit-2.0/luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-xenial/Dockerfile)
- `2-lua52compat-bionic`, `2-lua52compat-ubuntu`, `2.0-lua52compat-bionic`, `2.0-lua52compat-ubuntu`, `2.0.5-lua52compat-bionic`, `2.0.5-lua52compat-ubuntu`, `lua52compat-ubuntu`: [luajit-2.0/lua52compat-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-bionic/Dockerfile)
- `2-lua52compat-xenial`, `2.0-lua52compat-xenial`, `2.0.5-lua52compat-xenial`: [luajit-2.0/lua52compat-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-xenial/Dockerfile)
- `2-lua52compat-luarocks-bionic`, `2-lua52compat-luarocks-ubuntu`, `2.0-lua52compat-luarocks-bionic`, `2.0-lua52compat-luarocks-ubuntu`, `2.0.5-lua52compat-luarocks-bionic`, `2.0.5-lua52compat-luarocks-ubuntu`, `lua52compat-luarocks-ubuntu`: [luajit-2.0/lua52compat-luarocks-bionic/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-bionic/Dockerfile)
- `2-lua52compat-luarocks-xenial`, `2.0-lua52compat-luarocks-xenial`, `2.0.5-lua52compat-luarocks-xenial`: [luajit-2.0/lua52compat-luarocks-xenial/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-xenial/Dockerfile)
- `2-centos`, `2-centos7`, `2.0-centos`, `2.0-centos7`, `2.0.5-centos`, `2.0.5-centos7`, `centos`: [luajit-2.0/centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/centos7/Dockerfile)
- `2-centos6`, `2.0-centos6`, `2.0.5-centos6`: [luajit-2.0/centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/centos6/Dockerfile)
- `2-luarocks-centos`, `2-luarocks-centos7`, `2.0-luarocks-centos`, `2.0-luarocks-centos7`, `2.0.5-luarocks-centos`, `2.0.5-luarocks-centos7`, `luarocks-centos`: [luajit-2.0/luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-centos7/Dockerfile)
- `2-luarocks-centos6`, `2.0-luarocks-centos6`, `2.0.5-luarocks-centos6`: [luajit-2.0/luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/luarocks-centos6/Dockerfile)
- `2-lua52compat-centos`, `2-lua52compat-centos7`, `2.0-lua52compat-centos`, `2.0-lua52compat-centos7`, `2.0.5-lua52compat-centos`, `2.0.5-lua52compat-centos7`, `lua52compat-centos`: [luajit-2.0/lua52compat-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-centos7/Dockerfile)
- `2-lua52compat-centos6`, `2.0-lua52compat-centos6`, `2.0.5-lua52compat-centos6`: [luajit-2.0/lua52compat-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-centos6/Dockerfile)
- `2-lua52compat-luarocks-centos`, `2-lua52compat-luarocks-centos7`, `2.0-lua52compat-luarocks-centos`, `2.0-lua52compat-luarocks-centos7`, `2.0.5-lua52compat-luarocks-centos`, `2.0.5-lua52compat-luarocks-centos7`, `lua52compat-luarocks-centos`: [luajit-2.0/lua52compat-luarocks-centos7/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-centos7/Dockerfile)
- `2-lua52compat-luarocks-centos6`, `2.0-lua52compat-luarocks-centos6`, `2.0.5-lua52compat-luarocks-centos6`: [luajit-2.0/lua52compat-luarocks-centos6/Dockerfile](https://github.com/GUI/lua-docker/blob/master/luajit-2.0/lua52compat-luarocks-centos6/Dockerfile)

## Image Variants

### `nickblah/lua:<version>`
The default Lua image. Provides Lua. Uses Debian Linux for base image.

### `nickblah/lua:<version>-alpine`
Provides Lua. Uses Alpine Linux for base image.

### `nickblah/lua:<version>-luarocks`
Provides Lua and LuaRocks. Uses Debian Linux for base image.

### `nickblah/lua:<version>-luarocks-alpine`
Provides Lua and LuaRocks. Uses Alpine Linux for base image.

### `nickblah/luajit:<version>`
The default LuaJIT image. Provides LuaJIT. Uses Debian Linux for base image.

### `nickblah/luajit:<version>-alpine`
Provides LuaJIT. Uses Alpine Linux for base image.

### `nickblah/luajit:<version>-luarocks`
Provides LuaJIT and LuaRocks. Uses Debian Linux for base image.

### `nickblah/luajit:<version>-luarocks-alpine`
Provides LuaJIT and LuaRocks. Uses Alpine Linux for base image.

### `nickblah/luajit:<version>-lua52compat`
Provides LuaJIT. LuaJIT compiled with `LUAJIT_ENABLE_LUA52COMPAT`. Uses Debian Linux for base image.

### `nickblah/luajit:<version>-lua52compat-alpine`
Provides LuaJIT. LuaJIT compiled with `LUAJIT_ENABLE_LUA52COMPAT`. Uses Alpine Linux for base image.

### `nickblah/luajit:<version>-lua52compat-luarocks`
Provides LuaJIT and LuaRocks. LuaJIT compiled with `LUAJIT_ENABLE_LUA52COMPAT`. Uses Debian Linux for base image.

### `nickblah/luajit:<version>-lua52compat-luarocks-alpine`
Provides LuaJIT and LuaRocks. LuaJIT compiled with `LUAJIT_ENABLE_LUA52COMPAT`. Uses Alpine Linux for base image.

## Installing C Libraries

These base images are minimal, so they only contain the necessary dependencies for running Lua and installing pure-Lua LuaRocks modules. If you need to install LuaRocks modules that include C extensions or need compiling/building, then you'll first need to install the necessary dependencies (for example, make, gcc, etc). The exact dependencies may vary depending on the module's requirements, but to install basic build dependencies, the following installation commands can be used:

- For Debian based images:
    ```sh
    apt-get update && apt-get install -y build-essential
    ```
- For Alpine based images:
    ```sh
    apk add --no-cache build-base
    ```

## Update Process

This could possibly be automated more, but the current process for handling updates: When new versions of Lua, LuaJIT, or LuaRocks are released, the CI builds should fail (which serves as a notification mechanism). Run `./update` and commit the results to generate the new Dockerfiles. If there are any new major or minor releases, ensure the automated build configuration is updated (patch releases should not require updating):

- [`nickblah/lua`](https://cloud.docker.com/repository/docker/nickblah/lua/builds/edit)
  - Docker Tag: `5.0-alpine3.9`  
    Build Context: `/lua-5.0/alpine3.9/`
  - Docker Tag: `5.0-bionic`  
    Build Context: `/lua-5.0/bionic/`
  - Docker Tag: `5.0-centos6`  
    Build Context: `/lua-5.0/centos6/`
  - Docker Tag: `5.0-centos7`  
    Build Context: `/lua-5.0/centos7/`
  - Docker Tag: `5.0-jessie`  
    Build Context: `/lua-5.0/jessie/`
  - Docker Tag: `5.0-stretch`  
    Build Context: `/lua-5.0/stretch/`
  - Docker Tag: `5.0-xenial`  
    Build Context: `/lua-5.0/xenial/`
  - Docker Tag: `5.1-alpine3.9`  
    Build Context: `/lua-5.1/alpine3.9/`
  - Docker Tag: `5.1-bionic`  
    Build Context: `/lua-5.1/bionic/`
  - Docker Tag: `5.1-centos6`  
    Build Context: `/lua-5.1/centos6/`
  - Docker Tag: `5.1-centos7`  
    Build Context: `/lua-5.1/centos7/`
  - Docker Tag: `5.1-jessie`  
    Build Context: `/lua-5.1/jessie/`
  - Docker Tag: `5.1-luarocks-alpine3.9`  
    Build Context: `/lua-5.1/luarocks-alpine3.9/`
  - Docker Tag: `5.1-luarocks-bionic`  
    Build Context: `/lua-5.1/luarocks-bionic/`
  - Docker Tag: `5.1-luarocks-centos6`  
    Build Context: `/lua-5.1/luarocks-centos6/`
  - Docker Tag: `5.1-luarocks-centos7`  
    Build Context: `/lua-5.1/luarocks-centos7/`
  - Docker Tag: `5.1-luarocks-jessie`  
    Build Context: `/lua-5.1/luarocks-jessie/`
  - Docker Tag: `5.1-luarocks-stretch`  
    Build Context: `/lua-5.1/luarocks-stretch/`
  - Docker Tag: `5.1-luarocks-xenial`  
    Build Context: `/lua-5.1/luarocks-xenial/`
  - Docker Tag: `5.1-stretch`  
    Build Context: `/lua-5.1/stretch/`
  - Docker Tag: `5.1-xenial`  
    Build Context: `/lua-5.1/xenial/`
  - Docker Tag: `5.2-alpine3.9`  
    Build Context: `/lua-5.2/alpine3.9/`
  - Docker Tag: `5.2-bionic`  
    Build Context: `/lua-5.2/bionic/`
  - Docker Tag: `5.2-centos6`  
    Build Context: `/lua-5.2/centos6/`
  - Docker Tag: `5.2-centos7`  
    Build Context: `/lua-5.2/centos7/`
  - Docker Tag: `5.2-jessie`  
    Build Context: `/lua-5.2/jessie/`
  - Docker Tag: `5.2-luarocks-alpine3.9`  
    Build Context: `/lua-5.2/luarocks-alpine3.9/`
  - Docker Tag: `5.2-luarocks-bionic`  
    Build Context: `/lua-5.2/luarocks-bionic/`
  - Docker Tag: `5.2-luarocks-centos6`  
    Build Context: `/lua-5.2/luarocks-centos6/`
  - Docker Tag: `5.2-luarocks-centos7`  
    Build Context: `/lua-5.2/luarocks-centos7/`
  - Docker Tag: `5.2-luarocks-jessie`  
    Build Context: `/lua-5.2/luarocks-jessie/`
  - Docker Tag: `5.2-luarocks-stretch`  
    Build Context: `/lua-5.2/luarocks-stretch/`
  - Docker Tag: `5.2-luarocks-xenial`  
    Build Context: `/lua-5.2/luarocks-xenial/`
  - Docker Tag: `5.2-stretch`  
    Build Context: `/lua-5.2/stretch/`
  - Docker Tag: `5.2-xenial`  
    Build Context: `/lua-5.2/xenial/`
  - Docker Tag: `5.3-alpine3.9`  
    Build Context: `/lua-5.3/alpine3.9/`
  - Docker Tag: `5.3-bionic`  
    Build Context: `/lua-5.3/bionic/`
  - Docker Tag: `5.3-centos6`  
    Build Context: `/lua-5.3/centos6/`
  - Docker Tag: `5.3-centos7`  
    Build Context: `/lua-5.3/centos7/`
  - Docker Tag: `5.3-jessie`  
    Build Context: `/lua-5.3/jessie/`
  - Docker Tag: `5.3-luarocks-alpine3.9`  
    Build Context: `/lua-5.3/luarocks-alpine3.9/`
  - Docker Tag: `5.3-luarocks-bionic`  
    Build Context: `/lua-5.3/luarocks-bionic/`
  - Docker Tag: `5.3-luarocks-centos6`  
    Build Context: `/lua-5.3/luarocks-centos6/`
  - Docker Tag: `5.3-luarocks-centos7`  
    Build Context: `/lua-5.3/luarocks-centos7/`
  - Docker Tag: `5.3-luarocks-jessie`  
    Build Context: `/lua-5.3/luarocks-jessie/`
  - Docker Tag: `5.3-luarocks-stretch`  
    Build Context: `/lua-5.3/luarocks-stretch/`
  - Docker Tag: `5.3-luarocks-xenial`  
    Build Context: `/lua-5.3/luarocks-xenial/`
  - Docker Tag: `5.3-stretch`  
    Build Context: `/lua-5.3/stretch/`
  - Docker Tag: `5.3-xenial`  
    Build Context: `/lua-5.3/xenial/`
  - Docker Tag: `5.4-alpha-rc-alpine3.9`  
    Build Context: `/lua-5.4-alpha-rc/alpine3.9/`
  - Docker Tag: `5.4-alpha-rc-bionic`  
    Build Context: `/lua-5.4-alpha-rc/bionic/`
  - Docker Tag: `5.4-alpha-rc-centos6`  
    Build Context: `/lua-5.4-alpha-rc/centos6/`
  - Docker Tag: `5.4-alpha-rc-centos7`  
    Build Context: `/lua-5.4-alpha-rc/centos7/`
  - Docker Tag: `5.4-alpha-rc-jessie`  
    Build Context: `/lua-5.4-alpha-rc/jessie/`
  - Docker Tag: `5.4-alpha-rc-luarocks-alpine3.9`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-alpine3.9/`
  - Docker Tag: `5.4-alpha-rc-luarocks-bionic`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-bionic/`
  - Docker Tag: `5.4-alpha-rc-luarocks-centos6`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-centos6/`
  - Docker Tag: `5.4-alpha-rc-luarocks-centos7`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-centos7/`
  - Docker Tag: `5.4-alpha-rc-luarocks-jessie`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-jessie/`
  - Docker Tag: `5.4-alpha-rc-luarocks-stretch`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-stretch/`
  - Docker Tag: `5.4-alpha-rc-luarocks-xenial`  
    Build Context: `/lua-5.4-alpha-rc/luarocks-xenial/`
  - Docker Tag: `5.4-alpha-rc-stretch`  
    Build Context: `/lua-5.4-alpha-rc/stretch/`
  - Docker Tag: `5.4-alpha-rc-xenial`  
    Build Context: `/lua-5.4-alpha-rc/xenial/`
- [`nickblah/luajit`](https://cloud.docker.com/repository/docker/nickblah/luajit/builds/edit)
  - Docker Tag: `2.0-alpine3.9`  
    Build Context: `/luajit-2.0/alpine3.9/`
  - Docker Tag: `2.0-bionic`  
    Build Context: `/luajit-2.0/bionic/`
  - Docker Tag: `2.0-centos6`  
    Build Context: `/luajit-2.0/centos6/`
  - Docker Tag: `2.0-centos7`  
    Build Context: `/luajit-2.0/centos7/`
  - Docker Tag: `2.0-jessie`  
    Build Context: `/luajit-2.0/jessie/`
  - Docker Tag: `2.0-lua52compat-alpine3.9`  
    Build Context: `/luajit-2.0/lua52compat-alpine3.9/`
  - Docker Tag: `2.0-lua52compat-bionic`  
    Build Context: `/luajit-2.0/lua52compat-bionic/`
  - Docker Tag: `2.0-lua52compat-centos6`  
    Build Context: `/luajit-2.0/lua52compat-centos6/`
  - Docker Tag: `2.0-lua52compat-centos7`  
    Build Context: `/luajit-2.0/lua52compat-centos7/`
  - Docker Tag: `2.0-lua52compat-jessie`  
    Build Context: `/luajit-2.0/lua52compat-jessie/`
  - Docker Tag: `2.0-lua52compat-luarocks-alpine3.9`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-alpine3.9/`
  - Docker Tag: `2.0-lua52compat-luarocks-bionic`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-bionic/`
  - Docker Tag: `2.0-lua52compat-luarocks-centos6`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-centos6/`
  - Docker Tag: `2.0-lua52compat-luarocks-centos7`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-centos7/`
  - Docker Tag: `2.0-lua52compat-luarocks-jessie`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-jessie/`
  - Docker Tag: `2.0-lua52compat-luarocks-stretch`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-stretch/`
  - Docker Tag: `2.0-lua52compat-luarocks-xenial`  
    Build Context: `/luajit-2.0/lua52compat-luarocks-xenial/`
  - Docker Tag: `2.0-lua52compat-stretch`  
    Build Context: `/luajit-2.0/lua52compat-stretch/`
  - Docker Tag: `2.0-lua52compat-xenial`  
    Build Context: `/luajit-2.0/lua52compat-xenial/`
  - Docker Tag: `2.0-luarocks-alpine3.9`  
    Build Context: `/luajit-2.0/luarocks-alpine3.9/`
  - Docker Tag: `2.0-luarocks-bionic`  
    Build Context: `/luajit-2.0/luarocks-bionic/`
  - Docker Tag: `2.0-luarocks-centos6`  
    Build Context: `/luajit-2.0/luarocks-centos6/`
  - Docker Tag: `2.0-luarocks-centos7`  
    Build Context: `/luajit-2.0/luarocks-centos7/`
  - Docker Tag: `2.0-luarocks-jessie`  
    Build Context: `/luajit-2.0/luarocks-jessie/`
  - Docker Tag: `2.0-luarocks-stretch`  
    Build Context: `/luajit-2.0/luarocks-stretch/`
  - Docker Tag: `2.0-luarocks-xenial`  
    Build Context: `/luajit-2.0/luarocks-xenial/`
  - Docker Tag: `2.0-stretch`  
    Build Context: `/luajit-2.0/stretch/`
  - Docker Tag: `2.0-xenial`  
    Build Context: `/luajit-2.0/xenial/`
  - Docker Tag: `2.1-beta-alpine3.9`  
    Build Context: `/luajit-2.1-beta/alpine3.9/`
  - Docker Tag: `2.1-beta-bionic`  
    Build Context: `/luajit-2.1-beta/bionic/`
  - Docker Tag: `2.1-beta-centos6`  
    Build Context: `/luajit-2.1-beta/centos6/`
  - Docker Tag: `2.1-beta-centos7`  
    Build Context: `/luajit-2.1-beta/centos7/`
  - Docker Tag: `2.1-beta-jessie`  
    Build Context: `/luajit-2.1-beta/jessie/`
  - Docker Tag: `2.1-beta-lua52compat-alpine3.9`  
    Build Context: `/luajit-2.1-beta/lua52compat-alpine3.9/`
  - Docker Tag: `2.1-beta-lua52compat-bionic`  
    Build Context: `/luajit-2.1-beta/lua52compat-bionic/`
  - Docker Tag: `2.1-beta-lua52compat-centos6`  
    Build Context: `/luajit-2.1-beta/lua52compat-centos6/`
  - Docker Tag: `2.1-beta-lua52compat-centos7`  
    Build Context: `/luajit-2.1-beta/lua52compat-centos7/`
  - Docker Tag: `2.1-beta-lua52compat-jessie`  
    Build Context: `/luajit-2.1-beta/lua52compat-jessie/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-alpine3.9`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-alpine3.9/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-bionic`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-bionic/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-centos6`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-centos6/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-centos7`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-centos7/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-jessie`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-jessie/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-stretch`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-stretch/`
  - Docker Tag: `2.1-beta-lua52compat-luarocks-xenial`  
    Build Context: `/luajit-2.1-beta/lua52compat-luarocks-xenial/`
  - Docker Tag: `2.1-beta-lua52compat-stretch`  
    Build Context: `/luajit-2.1-beta/lua52compat-stretch/`
  - Docker Tag: `2.1-beta-lua52compat-xenial`  
    Build Context: `/luajit-2.1-beta/lua52compat-xenial/`
  - Docker Tag: `2.1-beta-luarocks-alpine3.9`  
    Build Context: `/luajit-2.1-beta/luarocks-alpine3.9/`
  - Docker Tag: `2.1-beta-luarocks-bionic`  
    Build Context: `/luajit-2.1-beta/luarocks-bionic/`
  - Docker Tag: `2.1-beta-luarocks-centos6`  
    Build Context: `/luajit-2.1-beta/luarocks-centos6/`
  - Docker Tag: `2.1-beta-luarocks-centos7`  
    Build Context: `/luajit-2.1-beta/luarocks-centos7/`
  - Docker Tag: `2.1-beta-luarocks-jessie`  
    Build Context: `/luajit-2.1-beta/luarocks-jessie/`
  - Docker Tag: `2.1-beta-luarocks-stretch`  
    Build Context: `/luajit-2.1-beta/luarocks-stretch/`
  - Docker Tag: `2.1-beta-luarocks-xenial`  
    Build Context: `/luajit-2.1-beta/luarocks-xenial/`
  - Docker Tag: `2.1-beta-stretch`  
    Build Context: `/luajit-2.1-beta/stretch/`
  - Docker Tag: `2.1-beta-xenial`  
    Build Context: `/luajit-2.1-beta/xenial/`
