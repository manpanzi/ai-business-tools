# 🎨 Midjourney 绘画提示词库

> 针对中文用户优化的提示词，涵盖常用风格和场景。

---

## 一、基础公式

**示例**：  
一只橘猫 + 坐在窗台上 + 治愈插画风 + 午后阳光 + 暖色调 + 侧面特写 + `--ar 4:3`

**简化公式（新手推荐）**：  
`[主体] + [风格关键词] + [--ar 宽高比]`

---

## 二、风格关键词对照表

| 中文风格 | 英文关键词 | 效果描述 |
|----------|-----------|----------|
| 国风水墨 | Chinese ink painting, elegant, misty, brush strokes | 传统水墨意境，留白写意 |
| 赛博朋克 | cyberpunk, neon lights, futuristic city, rain | 科幻未来感，霓虹色彩 |
| 治愈插画 | children's book illustration, soft, dreamy, warm | 温暖治愈风，柔和线条 |
| 宫崎骏风格 | Studio Ghibli style, pastoral, nostalgic | 日系动画质感，清新自然 |
| 极简北欧风 | minimalism, scandinavian design, clean, pastel | 简洁干净，浅色调 |
| 复古胶片 | vintage, film grain, retro, kodak portra | 胶片质感，暖黄调 |
| 奇幻仙境 | fantasy art, magical, glowing, ethereal | 梦幻神秘，发光粒子 |
| 写实摄影 | photorealistic, 8K, detailed, shot on Sony A7 | 逼真照片级细节 |
| 新中式 | modern Chinese style, zen, bamboo, tea house | 现代中式意境，宁静雅致 |
| 蒸汽波 | vaporwave, glitch art, pastel, greek statue | 复古迷幻，粉紫色调 |

---

## 三、常用场景模板

| 场景 | 完整提示词（中英对照） | 参数建议 |
|------|----------------------|----------|
| 古风人物 | 一位穿着汉服的女子在樱花树下弹古筝，飘逸，仙气，国风插画 <br> A woman in Hanfu playing guzheng under cherry blossom trees, elegant, ethereal, Chinese style illustration | `--ar 2:3 --style raw` |
| 科技产品 | 未来主义耳机，发光线条，悬浮展示，科技感，背景虚化 <br> Futuristic headphones with glowing lines, floating display, tech aesthetic, bokeh background | `--ar 16:9 --style raw` |
| 中式庭院 | 雨后江南庭院，青瓦白墙，芭蕉叶，朦胧雾气，水墨风格 <br> Rainy Chinese courtyard, white walls and black tiles, banana leaves, misty, ink painting style | `--ar 4:3 --iw 1.5` |
| 美食摄影 | 一碗热气腾腾的红烧牛肉面，木筷，陶瓷碗，暖光，写实摄影 <br> A bowl of hot braised beef noodles, wooden chopsticks, ceramic bowl, warm light, photorealistic | `--ar 1:1 --style raw` |
| 城市夜景 | 上海外滩夜景，霓虹灯，车流，雨夜玻璃反光，赛博朋克 <br> Shanghai Bund night view, neon lights, traffic, rainy glass reflection, cyberpunk | `--ar 16:9 --no people` |
| 宠物治愈 | 柴犬窝在毛毯里看窗外雪景，温馨，儿童插画风，柔和色调 <br> Shiba inu curled in a blanket watching snowy window, cozy, children's illustration, soft tones | `--ar 4:3` |
| 职场办公 | 深夜写字楼里的工位，一盏台灯，咖啡杯，疲惫但坚持，写实电影质感 <br> Late night office desk, a desk lamp, coffee cup, tired but persistent, realistic movie still | `--ar 16:9 --style raw` |
| 自然风景 | 云南元阳梯田，日出，云海，雾气缭绕，国风水墨 <br> Yuanyang rice terraces in Yunnan, sunrise, sea of clouds, misty, Chinese ink painting | `--ar 3:2` |

---

## 四、进阶技巧

### 1. 负面提示词（避免什么）
在提示词末尾加上 `--no` 参数，排除不想要的元素。
![查看次数](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/manpanzi/ai-business-tools/blob/main/prompts/公众号情感文案.md&title=查看)

```bash
# 示例：不要模糊、不要畸形、不要丑陋
--no blurry, deformed, ugly, extra fingers, bad anatomy
