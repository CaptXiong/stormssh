<img src="https://raw.github.com/emre/storm/master/resources/logos/storm-logo.png" height="80">
---

[![Join the chat at https://gitter.im/emre/storm](https://badges.gitter.im/emre/storm.svg)](https://gitter.im/emre/storm?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/emre/storm.svg?branch=master)](https://travis-ci.org/emre/storm)

**Support Python after 3.11 now.** 

storm is a command line tool to manage your ssh connections.


**features**

- adding, editing, deleting, listing, searching across your SSHConfig.
- command alias support for your CLI preferences.
- support for custom SSH directives.
- scriptable as a python library.
- user interfaces besides cli. (web ui, wxpython, unity(ubuntu) indicator.)

#### dependencies
On Debian systems, install header files and a static library for Python (python3.4-dev or python2.7-dev)

On Ubuntu 16.04, you need install libssl-dev and libffi-dev (sudo apt-get install libssl-dev libffi-dev)

#### installation

```bash
$ [sudo] pip install git+https://github.com/CaptXiong/stormssh.git
```

#### troubleshooting installation

```
clang: error: unknown argument: '-mno-fused-madd'

error: command 'cc' failed with exit status 1
```

See [#73](https://github.com/emre/storm/issues/73). If the issue persists, see also [#76](https://github.com/emre/storm/issues/96) .

#### usage & documentation

<a href='http://stormssh.readthedocs.org/en/master/'>http://stormssh.readthedocs.org/en/master/</a>

#### screens

<a href="http://i.imgur.com/qIc1mDx.png"><img src="http://i.imgur.com/qIc1mDx.png"></a>


**web ui**

<a href="http://i.imgur.com/wVtnWxx.png"><img src="http://i.imgur.com/wVtnWxx.png"></a>

