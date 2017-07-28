Chrome extension for [TAPD](http://www.tapd.cn/)
---

### Extension ID

* Local `pidmbabdfgglodgkakjoegeeeemfkdeg`
* Store [`ifnplghlomamhddgdknfcennkpcjcoke`](https://chrome.google.com/webstore/detail/tapd助手/ifnplghlomamhddgdknfcennkpcjcoke)

### Features

* Custom URL schema support

* Shortcuts
  * [Alt+Esc] toggle project list
  * [Alt+Num] Num=1,2,3,4..., switch to project *Num*
  * [Alt+M] project members
  * [Alt+R] newest requirements report or do nothing
  * [Alt+B] newest customized bug report or bug/dealer report

  * [Alt+W] open worktable
  * [Alt+N] open notification messages
  * [Alt+H/Alt+Left] left page
  * [Alt+L/Alt+Right] left page
  * [Alt+S] search
  * [Alt+F] fullscreen
  * [Shift+?] show help
  * [Ctrl+C/Cmd+C] copy feature/bug title and url
  * [Alt+C] copy feature/bug id and title

### TODO

* after click `#btn_update_exit`, clean empty `<a>` in editor
* configurable shortcuts


### 路线图Roadmap:

* 配置页面，可以配置触发键为Alt或者Ctrl或者Cmd等。
  * [官方文档](https://developer.chrome.com/extensions/options) `chrome.storage.sync.set|get`
  * 产品稿 <http://dev01.xiaoman.cc:8000/katyusha/#g=1&p=config>

* fullscreen模式支持自定义zoom
  * 在fullscreen下，点击+/-号设置element的zoom，同时存储起来
  * 退出fullscreen，清除zoom
  * 再次启用fullscreen的时候，会再次设置zoom


