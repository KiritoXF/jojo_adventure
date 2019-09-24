## jojo's adventure

+ Vue.js+ElementUI
+ Vue单页面demo

这是一个学习过程中的练习demo。

目前有两个主要的部分。

1. `jojo's adventure`，主要功能是生成怪物然后战斗，并且可以提升等级和购买装备。 完成度30%

2. `coding's adventure`，扮演软件公司的老板，雇佣员工敲代码获得福报。完成度10%

做到这个程度，已经可以发现单页面文件的一些弊端。代码冗余，不易管理，所有组件全写在一起。

所以没有维护的必要了。

从目前的完成程度来看，可以进行简单的运行，但是存在一些bug。

## demo

GitHub Pages: [jojo_adventure](https://kiritoxf.github.io/jojo_adventure)

目前不可用，似乎是因为域名配置的问题。稍后会进行修复（也许吧）。

也可以把`index.html`下载到本地打开。

## 可供参考的内容

1.设计理念

比如UI、玩法上的设计。用tab页的形式管理不同的界面。

2.组件的复用

尽管是单页面文件，但是也写了一些局部的可复用的组件。比如一些面板、button。在正常的开发中，这些组件应该是抽到单独的文件中的。
