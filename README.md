__备份__`c:\windows\fonts`

- input dir: fonts
- output dir: output/fonts
- 替换字体

「设置 - 更新和安全 - 恢复 - 高级启动 - 立即重新启动」-「疑难解答 - 命令提示符」

``` shell
xcopy C:\fonts C:\Windows\Fonts
命令提示符下，c盘不一定是系统的c盘，用dir确认一下
```
