# Audio Player
一个基于Web Audio API的本地音乐播放器



## 开发
```sh
    git clone https://github.com/changelime/player.git
    cd player
    npm install --only=dev && npm install -g jspm && jspm install

    //打开chrome扩展管理烈面，加载NodeTab目录
```

## 构建
```sh
    jspm bundle-sfx src/js/app.js dest/js/app.bundle.js
    npm run built
    //打开chrome扩展管理烈面，加载NodeTab/dest目录
```

## 功能

* 播放列表（左上角按钮展开）
* 播放控制（播放、暂停、上一曲、下一曲）
* 播放列表搜索

## 演示
[Demo](changelime.github.io/player/dest/ "Demo")

![Demo](http://i.imgur.com/h0vI5f2.png)

![Demo](http://i.imgur.com/hcf1QN0.png)

![Demo](http://i.imgur.com/RKu2OEE.png)



## 许可
MIT
