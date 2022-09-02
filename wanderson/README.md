# Packages
1. npm
2. browser preview

# Problem

> 2022-09-02

어떤 이슈를 찾아보든 해결된 이슈는 없고 여전히 현재 진행형이다.

일렉트론을 gitpod 서비스에서 돌리기에는 무리가 있는거 같고 
  docker 의 도움을 받아 어느 환경에서든 문제 없이 구동시킬려고 했으나, docker 쪽은 아에 모르기 때문에 포기.

빠른 시일내에 데스크탑 앱을 체험해보려 했으나 여러 버그, 이슈들 때문에 못할거 같음.

나중에 기회가 되면 외출 나가서 테스트해봐야지

```
[7131:0902/102113.237205:ERROR:ozone_platform_x11.cc(247)] Missing X server or $DISPLAY
[7131:0902/102113.237258:ERROR:env.cc(226)] The platform failed to initialize.  Exiting.
/workspace/electronjs/wanderson/node_modules/electron/dist/electron exited with signal SIGSEGV
```


# ISSUE

> gitpod에서 일렉트론을 활용하여 개발할 수 있는가에 대한 주제에 관해 토론
1. [Support Electron apps #261](https://github.com/gitpod-io/gitpod/issues/261)

2. [Missing shared libraries #486](https://forum.magicmirror.builders/topic/10280/npm-install-error/2)

3. [npm error Syntax error: word unexpected (expecting ")")](https://stackoverflow.com/questions/35609532/npm-error-syntax-error-word-unexpected-expecting)

4. [[Bug]: Missing X server or $DISPLAY #8148](https://github.com/puppeteer/puppeteer/issues/8148)
# ERROR

1. [node.js puppeteer 리눅스VM 실행 불가 해결 방법(CentOS, 우분투): Failed to launch the browser process](https://curryyou.tistory.com/222)
