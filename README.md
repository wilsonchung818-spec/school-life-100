# 学校生活 100 词 · 口语学习 PWA

面向小学生的可安装英语口语样课。当前示范词是 **book**，围绕“会认、会听、会搭配、会对话、会复习”设计。

## 在线体验

https://wilsonchung818-spec.github.io/school-life-100/

## 核心功能

- 单词、音标、词义、自然拼读与跟读音频
- 3 个高频搭配及逐项学习记录
- 3 个图片沟通场景，每个场景都有完整问答、中文释义和替换练习
- 隐藏答案、交换角色、只听问题等渐进式口语训练
- 本机录音与回听，录音不会上传
- 第 1、2、7、14 天复习打卡，进度保存在当前设备
- Android、iPhone、iPad 添加到主屏幕及离线使用

## 本地运行

请通过本地静态服务器打开项目根目录，不要直接双击 HTML 文件。例如：

```powershell
python -m http.server 4173
```

然后访问 `http://127.0.0.1:4173/`。

## 自动检查

```powershell
npm test
```

应用图标源文件为 `assets/icons/icon.svg`。需要重新生成 PNG 时，运行 `scripts/generate_icons.py`。
