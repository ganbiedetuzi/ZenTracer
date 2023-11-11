<p align="center">
  <img src="https://raw.githubusercontent.com/hluwa/ZenTracer/master/icon.png" alt="Logo"/>
</p>

### 2023.11.11更新
更新：适配了新版的frida使用的是app的进程名不再是app的包名了,只需要在config.py文件中设置你是否为新版本的frida
### screenshot
![](./screenshot.png)



### problem
	1. the commandline trace script is not intuitive, so i use the PyQt draw UI.
	2. * maybe has some bug, please fix when using..

### usage
	1. require `PyQt5` & `frida`.
	2. manage Match/Black Pattern of target in `Action`.
	3. support double match mode: 'M'(match),'E'(equal); such as: 'M:android.content.', 'E:android.content.ContextImpl'.
	4. `Import jadx-jobf` can modify classname to sync jadx deobfuscate.
	5. `Export\Import JSON` can save\restore call tree.

### changelog
#### 20190926
	1. [untested\imperfect] support multiprocess.
	2. merge ui code.
	3. fix bugs.
	4. add README :)

#### ....
