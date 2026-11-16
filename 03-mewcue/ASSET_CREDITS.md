# 素材与截图来源

## 四张真实产品截图

welcome.png、ai-check.png、ai-insight.png、fgs-details.png均于2026-11-17通过现有在线产品实际操作截取，等待字体与图像解码后保存，无AI生成、重绘、拼接或界面替换。截图来自全新无登录浏览器，使用示例猫名Puffy，不包含个人账号、密钥或私人猫咪照片。详情图只打开修正控件，未人为制造另一个模型结果。

产品Figma UI由作者独立完成，猫咪插画使用Lovart生成。

## 示例A照片

Tuxedo cat, front view.png，Ryan Schwark，2021，CC0 1.0。

- [Wikimedia原始来源](https://commons.wikimedia.org/wiki/File:Tuxedo_cat,_front_view.png)
- [CC0说明](https://creativecommons.org/publicdomain/zero/1.0/)

截图按产品原有布局显示裁切，照片为公开许可案例，不是Puffy，也不是专家标注的健康或疼痛真值。

## 关键点与FGS

关键点为Hugo Cornellier预训练模型在本地LiteRT中实际预测的48组坐标，基于CatFLW数据集。原模型权重为CC BY-NC 4.0，代码为Apache-2.0。本包不分发权重，也不提供实时推理；点位颜色仅按原模型分组，不代表置信度、可见性或疼痛程度。此说明不构成商业模型许可。

- [模型来源](https://huggingface.co/hugocornellier/cat-face-landmarks)
- [模型代码](https://github.com/hugocornellier/cat-face-landmarks-training)
- [CatFLW论文：Martvel等，2023](https://arxiv.org/abs/2305.04232)
- Martvel、Shimshoni、Zamansky，Automated Detection of Cat Facial Landmarks，IJCV，2024。

FGS结果为原照片已保存的真实API观察，五项原始分数为0/0/0/0/null，有效总和0/8。它是实验性AI辅助观察，不是疾病诊断或临床验证结果，低分不能排除疼痛。
