# Pluzzdl

**Remark**: This version fixes an installation issue. Indeed, with previous versin the installed version was not working unless you were in the git repository itself.

Pluzzdl is a Python script used to fetch free VOD videos from http://pluzz.francetv.fr/
Note that the video content is only available to users connecting from a
French IP, if you live outside of France, a proxy should be used. See
`proxy_fetch.sh` for an example of how to use a proxy (set to
127.0.0.1:8080 in the proxy example).

## Installation procedure (tested on Ubuntu 12.04)

```
sudo apt-get install python-beautifulsoup git-core
git clone https://github.com/doc75/pluzzdl.git
cd pluzzdl
make build
sudo make install
```
