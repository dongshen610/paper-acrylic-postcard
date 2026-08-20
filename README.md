# Paper Acrylic Postcard Skill

把一张生活照片制作成“真实原图 + 极简纸感丙烯插画”的横向收藏型明信片。

## 特点

- 自动判断照片横版或竖版并选择版式
- 保留原始照片的真实人物、动作和关键物体
- 自动提炼最值得记住的动作、关系与情绪
- 生成不规则干刷边缘的纸感丙烯插画
- 使用不超过四种主要颜色和大量留白
- 自动生成连续编号、中文短文案和三个取色色块
- 锁定精修比例：插画比照片小一档，不喧宾夺主

## 安装

把下面这句话交给 Codex：

```text
请从这个 GitHub 仓库安装 paper-acrylic-postcard Skill。
仓库路径：https://github.com/dongshen610/paper-acrylic-postcard/tree/main/paper-acrylic-postcard
```

也可以使用 Skill Installer：

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo dongshen610/paper-acrylic-postcard \
  --path paper-acrylic-postcard
```

安装后，在下一轮对话中上传照片并说：

```text
用 $paper-acrylic-postcard 把这张照片做成纸感丙烯明信片。
```

## 使用说明

生成效果依赖所使用的图像生成模型。请仅上传自己拥有或获得授权的照片。Skill 不包含任何用户照片、API Key、Token 或私人数据。

## License

MIT
