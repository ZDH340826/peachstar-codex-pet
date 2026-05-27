# PeachStar Codex 宠物

[英文说明](README.md) · [制作过程摘要](docs/conversation-summary.md) · [如何制作自己的宠物](docs/make-your-own-pet.zh-CN.md) · [无脑版教程](docs/no-brainer-guide.zh-CN.md)

PeachStar 是一个自定义 Codex 数字宠物：主体是 Q 版人物女孩，带有玉桂狗风格帽兜、毕业帽星星和樱花细节。

本仓库包含可直接安装到 Codex 的宠物包，以及一个屏幕显示更大的实验版本。

## 版本

- `pets/peachstar`：标准版。
- `pets/peachstar-large`：放大版，在 Codex 固定宠物帧内放大显示。

## 安装方式

把其中一个宠物文件夹复制到 Codex 自定义宠物目录：

```text
C:\Users\<你的用户名>\.codex\pets\
```

例如：

```text
C:\Users\<你的用户名>\.codex\pets\peachstar
```

复制后重启 Codex，然后在宠物或外观设置里选择 `PeachStar` 或 `PeachStar Large`。

## 文件说明

每个宠物文件夹包含：

- `pet.json`：Codex 宠物配置文件。
- `spritesheet.webp`：8 x 9 精灵图图集，每格 192 x 208 像素。

## 目录结构

```text
pets/
  peachstar/
    pet.json
    spritesheet.webp
  peachstar-large/
    pet.json
    spritesheet.webp
docs/
  conversation-summary.md
  make-your-own-pet.zh-CN.md
  no-brainer-guide.zh-CN.md
  images/
```

## 质量检查

预览接触表在：

```text
docs/images/
```

生成的精灵图已通过校验：

- 格式：WebP
- 颜色模式：RGBA
- 尺寸：1536 x 1872
- 校验错误：无
- 校验警告：无

## 隐私说明

仓库没有上传原始参考照片，也没有上传中间生成目录。只保留最终可安装的宠物包、QA 预览图和脱敏制作过程摘要。
