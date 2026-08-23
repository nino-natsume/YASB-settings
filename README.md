# YASB 设置

个人使用的 YASB 设置，个人备份，兼共享

## 示例图

<img width="1916" height="47" alt="example" src="https://github.com/user-attachments/assets/8bdb5251-e86f-4d83-a80b-2be2c3aa8c92" />

### 说明

| 左 | 中 | 右 |
| :---: | :---: | :---: |
| 1、固定文件夹<br>2、当前打开的软件<br>3、播放器窗口 | 1、日期<br>2、时间 | 1、cava组件<br>2、系统托盘<br>3、内存占用情况<br>4、搜索<br>5、用户管理 |

其中，左1可自定义文件夹，在 `config.yaml` 的第 395 行修改你自己的文件夹路径

```
        callbacks:
          on_left: "exec explorer.exe C:\\example\\example\\1"
          on_right: "do_nothing"
```

左2软件可通过鼠标右键关闭，左3在播放音视频时会触发显示

以上所有内容均可自行在配置文件中自定义

## 使用方法

将本仓库内的 `config.toml`、`styles.css`下载拖拽覆盖原配置文件，或选择性复制粘贴至配置文件内，保存，若未自动重载则右键YASB，手动 `Reload YASB`重载配置

## 另

default压缩包是我最初开始用的版本，若担心这个不稳定建议用 default 这个，把压缩包内容拖至yasb主目录，让它 Reload 一下就能看到效果了
