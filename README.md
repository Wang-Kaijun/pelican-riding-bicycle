# 🚲 鹈鹕骑自行车 · 多模型对比

同一个命题 —— **"用纯 SVG + JavaScript 画一只骑自行车的鹈鹕"** —— 交给不同的模型各自完成一个可交互的动画页面，本仓库收录它们的成果。

## 🎬 在线实时预览

GitHub 仓库页里打开 HTML 只能看到源代码，**实时渲染请访问 GitHub Pages 站点**：

👉 **https://wang-kaijun.github.io/pelican-riding-bicycle/**

| 模型 | 页面 |
|------|------|
| GLM-5.3-Flash | [glm-5-3-flash.html](https://wang-kaijun.github.io/pelican-riding-bicycle/glm-5-3-flash.html) |
| GPT-6 Astra（xhigh） | [gpt-6-astra-xhigh.html](https://wang-kaijun.github.io/pelican-riding-bicycle/gpt-6-astra-xhigh.html) |
| DeepSeek-V4.1-Flash | [deepseek-v4-1-flash.html](https://wang-kaijun.github.io/pelican-riding-bicycle/deepseek-v4-1-flash.html) |
| Claude Opus 5（high） | [claude-opus-5-high.html](https://wang-kaijun.github.io/pelican-riding-bicycle/claude-opus-5-high.html) |

首页为四联实时预览，可直接在预览里拖动速度滑块。

## 🖥️ 本地运行

```bash
git clone https://github.com/Wang-Kaijun/pelican-riding-bicycle.git
cd pelican-riding-bicycle
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```
