# 📄项目简介
分享最好用、最实用的ComfyUI工作流（``workflow``），最新、最前沿的研究成果和相应的自定义节点（`custom nodes`），实用的视频、文字教程和知识等。

# 📊工作流分享
我把最实用的工作流（workflow）都给毫无保留地免费分享给所有需要的人：[点击此处查看pysssss-workflows文件夹](./pysssss-workflows)

| 序号  | 工作流名称                                                                                     | 工作流功能                                                                                                                               | 视频教程                                                                                                                                       |
| --- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | [1.0Cascade_Standard](pysssss-workflows/1.0Cascade_Standard.json)                         | 基本的``stable cascade``工作流，什么是cascade：[introducing-stable-cascade](https://stability.ai/news/introducing-stable-cascade)              |                                                                                                                                            |
| 2   | [1.1cascade-inpainting](pysssss-workflows/1.1cascade-inpainting.json)                     | cascade的inpainting（局部重绘）功能                                                                                                          |                                                                                                                                            |
| 3   | [2.0放大supir](pysssss-workflows/2.0放大supir.json)                                           | 个人认为目前为止最好的放大模型                                                                                                                     | [ComfyUI当前最强！一键放大工作流！SUPIR](https://www.bilibili.com/video/BV1nr42187dq/?share_source=copy_web&vd_source=22e73f717510e88027a60aa9c288021d) |
| 4   | [3.0检测（简单）YoloWorld-EfficientSAM](pysssss-workflows/3.0检测（简单）YoloWorld-EfficientSAM.json) | 自动检测任何物体，真的很神奇！                                                                                                                     |                                                                                                                                            |
| 5   | [3.1检测+重绘YoloWorld-EfficientSAM](pysssss-workflows/3.1检测+重绘YoloWorld-EfficientSAM.json)   | 自动检测后重绘检测的部分，比如检测图片里面的猫，然后全部换成狗。                                                                                                    |                                                                                                                                            |
| 6   | [4.0修复手部](pysssss-workflows/4.0修复手部.json)                                                 | 修复手部很好用                                                                                                                             |                                                                                                                                            |
| 7   | [5.0扩图](pysssss-workflows/5.0扩图.json)                                                     | 用的[Fooocus](https://github.com/lllyasviel/Fooocus)的模型，所以效果很不错，功能也很像。                                                                |                                                                                                                                            |
| 8   | [6.0移除背景BRIA](pysssss-workflows/6.0移除背景BRIA.json)                                         | 高效移除背景，速度极快，当然太复杂的图片，还是不行的。不想安装可以直接用这个**huggingface demo**：[BRIA-RMBG-1.4 demo](https://huggingface.co/spaces/briaai/BRIA-RMBG-1.4) |                                                                                                                                            |

# 👍用了都说好的`custom nodes`（自定义节点）

## 📈custom nodes排行榜
[nodecafe](https://www.nodecafe.org/)这个网站，由[comfyui-workspace-manager](https://github.com/11cafe/comfyui-workspace-manager)构建，一个类似于Pypi（用于发布、共享和安装Python包的官方第三方库）的comfyui自定义节点库wiki，根据开源`custom nodes`获得的stars⭐排名！

| 序号（实时⭐）                                                                            | Custom Nodes                                                                          | 简介（最有用的功能）                                                                                                                     |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| 1<br>![](https://img.shields.io/github/stars/ltdrdata/ComfyUI-Manager)             | [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)                        | 安装、删除、禁用和启用 ComfyUI 各种自定义节点的管理功能。此外，该扩展还提供了一个中心功能和便利功能，以便访问 ComfyUI 内部的广泛信息。                                                   |
| 2<br>![](https://img.shields.io/github/stars/pythongosssss/ComfyUI-Custom-Scripts) | [ComfyUI-Custom-Scripts](https://github.com/pythongosssss/ComfyUI-Custom-Scripts)<br> | 图像源：[Image Feed](https://github.com/pythongosssss/ComfyUI-Custom-Scripts?tab=readme-ov-file#image-feed)<br>添加一个面板，显示当前会话中生成的图像 |
| 3<br>![](https://img.shields.io/github/stars/Nuked88/ComfyUI-N-Sidebar)            | [ComfyUI-N-Sidebar](https://github.com/Nuked88/ComfyUI-N-Sidebar)<br><br>             | 提供了一个简单的侧边栏，支持节点的拖放、收藏、搜索，以及类别的展开/收起等功能，极大增强了界面交互体验。                                                                           |


# 💡AIGC前沿技术
（图像、视频、音频、数字人、3D等生成）

| 序号  | 项目名称及网址                                                   | 介绍                                                                                                      | huggingface demo（在线生成）                                             | ComfyUI实现                                                                                                                                         |
| --- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [InstantID](https://github.com/InstantID/InstantID)       | 【风格、样貌迁移】可实现使用单张图片进行ID保持生成的最先进方法，支持各种下游任务。                                                              | [InstantID demo](https://huggingface.co/spaces/InstantX/InstantID) | [ComfyUI InstantID](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID):<br>[ComfyUI_InstantID-（原生支持版）](https://github.com/cubiq/ComfyUI_InstantID) |
| 2   | [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) | 【风格、样貌迁移】其实效果没InstantID好。                                                                               | [IP-Adapter demo](https://huggingface.co/h94/IP-Adapter)           |                                                                                                                                                   |
| 3   | [AnyText](https://github.com/tyxsspa/AnyText)             | 【生成文字】多语言（包括汉字！）视觉文本生成与编辑                                                                               | [AnyText demo](https://huggingface.co/spaces/modelscope/AnyText)   |                                                                                                                                                   |
| 4   | [SUPIR](https://github.com/Fanghua-Yu/SUPIR)              | 【图片放大】极致卓越的放大方案，模糊照片还原出照片级别质感                                                                           | 暂无                                                                 |                                                                                                                                                   |
| 5   | <br>[APISR](https://github.com/Kiteretsu77/APISR)         | 【图片放大】- 对 [APISR](https://github.com/Kiteretsu77/APISR) 的非官方实现。专门用于**动漫**的超分模型，包含 2x 和 4x 双模型，速度飞快，效果很好 | [APISR demo](https://huggingface.co/spaces/HikariDawn/APISR)       | [ComfyUI-APISR](https://github.com/ZHO-ZHO-ZHO/ComfyUI-APISR)                                                                                     |

# 🏆顶级开发者（他们贡献了最棒的custom nodes）

| 序号  | 开发者                                           | 简介（主要贡献）                                                                                                                                                                                                                                                                                                                                                                                                 |
| --- | --------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [ZHO-ZHO-ZHO](https://github.com/ZHO-ZHO-ZHO) | [BRIA_RMBG 1.4 in ComfyUI](https://github.com/ZHO-ZHO-ZHO/ComfyUI-BRIA_AI-RMBG)：BRIA 开发的目前最好的背景去除模型，已支持批量处理（可去除视频背景）<br>[ComfyUI InstantID](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID): 仅需一张图就可实现高质量的角色保持！多种风格随心变！                                                                                                                                                                                |
| 2   | [ltdrdata](https://github.com/ltdrdata)<br>   | [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager)<br> [ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)                                                                                                                                                                                                                                                                |
| 3   | [lllyasviel](https://github.com/lllyasviel)   | [Fooocus](https://github.com/lllyasviel/Fooocus)<br>[stable-diffusion-webui-forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)<br>[ControlNet](https://github.com/lllyasviel/ControlNet)<br>                                                                                                                                                                                             |
| 4   | [HumanAIGC](https://github.com/HumanAIGC)<br> | 阿里的开源项目，画了很多饼，没一个正儿八经开源了！但是我们还是相信他会开源？<br>[EMO](https://github.com/HumanAIGC/EMO)：情感肖像活灵活现：在弱条件下利用音频到视频扩散模型生成富有表情的肖像视频<br>[AnimateAnyone](https://github.com/HumanAIGC/AnimateAnyone)：是的，有了这个谁都可以跳科目三，但就是不放代码出来啊！<br>[OutfitAnyone](https://github.com/HumanAIGC/OutfitAnyone)：想换装？以后淘宝买衣服，让它给你换来看看再买吧。这个有huggingface demo，[OutfitAnyone demo](https://huggingface.co/spaces/HumanAIGC/OutfitAnyone)<br> |

# ⬇️工作流、模型下载，社区交流

| 类别           | 网址                                      | 说明                                |     |
| ------------ | --------------------------------------- | --------------------------------- | --- |
| 工作流分享        | [OpenArt](https://openart.ai/workflows) | 很多大佬分享了海量的高质量工作流。                 |     |
| 模型分享（也有工作流等） | [civitai](https://civitai.com/)         | 搜索、下载和分享各种 AI 绘画模型，最齐全的网站，好像没有之一？ |     |

# 🌐图片、视频、音乐、3D模型、数字人…生成网站

| 图片生成 | [ideogram](https://ideogram.ai/)            | 这个网站生成的图片质量不错，可以生成文字。他们的模型也在不断迭代中。                                                       |
| ---- | ------------------------------------------- | ---------------------------------------------------------------------------------------- |
| 视频生成 | [haiper](https://app.haiper.ai/explore)     | 【生成视频】个人觉得生成的效果比什么[runway](https://runwayml.com/)、[pika](https://pika.art/)要好啊！就是2秒时间太短。 |
| 音乐生成 | [suno](https://app.suno.ai)                 | 音乐生成界的chatgpt？                                                                           |
| 数字人  | [heygen主页](https://app.heygen.com/home)<br> | 一个云端视频创作平台，提供了视频编辑（**视频翻译**）、AI生成内容（**数字人**）、个性化定制、模板场景库等功能，适合各种背景和技能水平的用户使用。            |