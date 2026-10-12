# Awesome Nano Banana Prompts

45 条实测过的 Nano Banana 2.1 修图提示词。每条都附真实的前后对比，复制就能用，没有需要你填的占位符。

[English](README.md) · [在 YepShot 里试](https://yepshot.com/zh/explore?utm_source=github&utm_medium=awesome-nano-banana-prompts) · [prompts.json](prompts.json)

<img src="images/studio-pure-white-amazon-after.webp" width="220"> <img src="images/campaign-sale-poster-text-after.webp" width="220"> <img src="images/lifestyle-travertine-stone-after.webp" width="220">

## 示例图是怎么来的

- 原图是合成的：用 Nano Banana 2.1 生成，刻意做成普通、有点乱的手机照，方便看出改动。没有用真人照片，也没有真实品牌。
- 效果图是把英文提示词原文交给 Nano Banana 2.1（1K）跑出来的结果，经过人工检查，没有后期修饰。下面列的是中文译文，英文原文见 [README.md](README.md) 或 prompts.json。
- 🖌 表示需要遮罩：先在图上涂出要改的区域。示例里的遮罩是程序自动框出目标后画的。
- 🖼 表示要两张图：IMG_1 是主图，IMG_2 是参考图。

## 目录

- [产品](#产品) (20)
- [服装](#服装) (6)
- [人像](#人像) (5)
- [营销](#营销) (5)
- [修复](#修复) (4)
- [创意](#创意) (5)
- [用 Gemini API 调用这些提示词](#用-gemini-api-调用这些提示词)

## 产品

### 电商平台纯白底主图

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-pure-white-amazon-before.webp" width="260" alt="电商平台纯白底主图 · 原图"></td><td><img src="images/studio-pure-white-amazon-after.webp" width="260" alt="电商平台纯白底主图 · 效果"></td></tr></table>

适合做电商平台的主图：亚马逊等不少平台要求主图是纯白底、只有商品本身。随手在桌上拍的商品照也能用，只要商品本身清晰。提示词会锁定标签和比例，但发布前还是留意一下包装上的小字有没有走样。

```text
保持商品原样，形状、标签、颜色和比例都不变。把背景换成纯白（#FFFFFF），商品居中。两侧用柔和均匀的影棚光，底部加一道自然的接触阴影。边缘清晰，无色彩溢出，干净的电商主图。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-pure-white-amazon?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Amazon, Shopify, White Background, Packshot

### 黑色亚克力镜面倒影

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-acrylic-reflection-before.webp" width="260" alt="黑色亚克力镜面倒影 · 原图"></td><td><img src="images/studio-acrylic-reflection-after.webp" width="260" alt="黑色亚克力镜面倒影 · 效果"></td></tr></table>

把普通商品照做成高端品牌广告里常见的暗调质感：黑色亚克力台面、镜面倒影、两侧轮廓光。适合瓶装、手表、香水、数码这类轮廓清楚的商品。本身颜色很深的商品容易和背景融在一起，原图最好光线充足。

```text
商品保持不变。放到高光黑色亚克力台面上，下方有清晰且逐渐淡出的镜面倒影。深色无缝背景，两侧轮廓光勾出商品边缘。明暗对比强烈，奢侈品质感，细节锐利。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-acrylic-reflection?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Luxury, Reflection, Dark Studio, Rim Light

### 悬浮主图与柔和投影

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-floating-ambient-shadow-before.webp" width="260" alt="悬浮主图与柔和投影 · 原图"></td><td><img src="images/studio-floating-ambient-shadow-after.webp" width="260" alt="悬浮主图与柔和投影 · 效果"></td></tr></table>

让商品悬浮在米白色无缝背景上约 2 厘米，下方留一道柔和的投影，是鞋包、美妆、数码产品首页大图的常见做法。画面干净，没有多余道具。想调整悬浮高度，直接改提示词里的“2 cm”。

```text
商品保持不变。让它悬浮在无缝米白色影棚背景上方约 2 厘米，正下方地面有一道柔和的漫射阴影。顶部柔光，干净极简的目录图风格。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-floating-ambient-shadow?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Levitation, Studio, Shadow, Catalog

### 浅灰底俯拍平铺图

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-overhead-flat-lay-before.webp" width="260" alt="浅灰底俯拍平铺图 · 原图"></td><td><img src="images/studio-overhead-flat-lay-after.webp" width="260" alt="浅灰底俯拍平铺图 · 效果"></td></tr></table>

把斜拍的随手照变成正上方俯拍的平铺图，浅灰色无缝背景，是钱包、配饰、叠好的衣物和文具在电商平台上常见的顶视图。模型要从上方重新画出商品，原图里没拍到的部分是它推断的，发布前对照实物检查一下边缘和细节。

```text
商品保持原样，形状、缝线、颜色和标志都不变。改成正上方俯拍的平铺图，商品居中放在浅灰色无缝背景上。柔和均匀的光线，只留很淡的阴影。干净简洁的电商商品图。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-overhead-flat-lay?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Flat Lay, Top View, Gray Background, Accessories

### 45 度目录角度

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-three-quarter-angle-before.webp" width="260" alt="45 度目录角度 · 原图"></td><td><img src="images/studio-three-quarter-angle-after.webp" width="260" alt="45 度目录角度 · 效果"></td></tr></table>

把正面拍的商品照转成 45 度的侧前方视角，纯白背景，让目录里的每件商品都用同一个角度。照片拍摄角度不统一、商品列表看起来参差不齐时用它。原图没拍到的侧面是模型想象出来的，发布前要对照实物检查。

```text
商品的设计、颜色、材质和标志都保持不变。改成向左转约 45 度的侧前方视角，纯白背景，底部有柔和的接触阴影。均匀的影棚光，统一的电商目录风格。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-three-quarter-angle?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Catalog, 45 Degree, White Background, Consistency

### 材质细节特写

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-material-detail-closeup-before.webp" width="260" alt="材质细节特写 · 原图"></td><td><img src="images/studio-material-detail-closeup-after.webp" width="260" alt="材质细节特写 · 效果"></td></tr></table>

把商品全景照变成材质、缝线和五金的特写，就是商品详情里跟在主图后面的那种细节图。适合皮具、包袋、鞋子和纺织品。原图看不清的细纹理是模型补出来的，把结果当作氛围细节图，并确认和买家收到的实物一致。

```text
把这张照片变成商品材质与做工的特写。画面里充满它的表面纹理、缝线和五金，用浅景深和柔和的侧光突出质感。颜色、材质和五金的光泽与原图完全一致。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-material-detail-closeup?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Detail Shot, Texture, Leather, Craftsmanship

### 多配色并排预览

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/studio-colorway-lineup-before.webp" width="260" alt="多配色并排预览 · 原图"></td><td><img src="images/studio-colorway-lineup-after.webp" width="260" alt="多配色并排预览 · 效果"></td></tr></table>

把商品的四种配色并排展示：原色加鼠尾草绿、沙米色和炭黑。适合规划新配色，或者在样品到货前先做出颜色选择的效果图。生成的颜色和真实染色不会完全一致，没实拍过的颜色不要直接当商品图用。把三个颜色名换成你自己的即可。

```text
把这件商品的四种配色并排展示：原色、鼠尾草绿、沙米色和炭黑色。四个的形状、材质、细节和标志完全一致。均匀排开在浅灰色背景上，用同样柔和的影棚光和一致的阴影。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/studio-colorway-lineup?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Colorways, Variants, Mockup, Lineup

### 洞石台面与晨光树影

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-travertine-stone-before.webp" width="260" alt="洞石台面与晨光树影 · 原图"></td><td><img src="images/lifestyle-travertine-stone-after.webp" width="260" alt="洞石台面与晨光树影 · 效果"></td></tr></table>

把商品放到粗切洞石台面上，旁边几枝干花，晨光透过树叶洒下斑驳光影，是护肤、香薰、蜡烛品牌常用的温暖自然风格。白底图太冷、想发社交媒体或品牌页时适合用它。形状、标签和颜色都锁定不变。

```text
商品保持原样，形状、标签、颜色都不变。放在一块原切米色洞石上，旁边点缀几枝干花。晨光透过窗户，在画面上投下斑驳的树叶光影。温润自然的氛围，浅景深，杂志风生活方式摄影。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-travertine-stone?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Travertine, Cosmetics, Morning Light, Lifestyle

### 大理石台面与水珠

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-marble-bathroom-dew-before.webp" width="260" alt="大理石台面与水珠 · 原图"></td><td><img src="images/lifestyle-marble-bathroom-dew-after.webp" width="260" alt="大理石台面与水珠 · 效果"></td></tr></table>

把商品放在白色卡拉拉大理石洗手台上，台面带细小水珠，背景是虚化的高级浴室。适合护肤、身体护理、沐浴类产品，突出清爽干净的感觉。背景刻意虚化，商品始终是画面里最清晰的部分，在小尺寸缩略图里也看得清。

```text
商品保持不变。放在抛光的卡拉拉白大理石洗手台上，台面带细密水珠。磨砂窗透进柔光，背景是虚化的轻奢水疗浴室。清新干净的护肤品广告质感，商品对焦清晰。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-marble-bathroom-dew?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Marble, Bathroom, Water Drops, Skincare

### 北欧橡木餐桌与生活道具

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-scandinavian-wood-kitchen-before.webp" width="260" alt="北欧橡木餐桌与生活道具 · 原图"></td><td><img src="images/lifestyle-scandinavian-wood-kitchen-after.webp" width="260" alt="北欧橡木餐桌与生活道具 · 效果"></td></tr></table>

把商品放在橡木餐桌上，旁边一只陶瓷杯、一块亚麻餐巾，侧窗暖光，像在真实的北欧家居里拍的。适合厨具、食品包装、咖啡和家居小物。道具少而素，只负责营造氛围，不会抢商品的风头。

```text
商品保持不变。放在带清晰木纹的天然橡木桌面上，旁边摆一只陶瓷杯和一块亚麻餐巾。侧窗暖色自然光，真实的北欧居家氛围，f/4 景深，商品清晰锐利。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-scandinavian-wood-kitchen?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Kitchen, Oak Wood, Homeware, Warm

### 水泥展台与科技质感

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-industrial-concrete-podium-before.webp" width="260" alt="水泥展台与科技质感 · 原图"></td><td><img src="images/lifestyle-industrial-concrete-podium-after.webp" width="260" alt="水泥展台与科技质感 · 效果"></td></tr></table>

把商品放在素水泥圆柱展台上，周围几块拉丝金属几何体，配硬朗的斜向阴影。冷静的建筑感适合耳机、充电器、手机壳这类数码配件。卖的是别的品类又想要同样的工业风，把提示词里的“tech accessories”换成你的品类即可。

```text
商品保持不变。放在极简的灰色水泥圆柱展台上，周围点缀几个拉丝金属几何体。冷调建筑光，投下利落的棱角阴影。适合科技配件的现代工业风，细节丰富。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-industrial-concrete-podium?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Tech, Concrete, Industrial, Minimalist

### 明亮的现代客厅

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-bright-living-room-before.webp" width="260" alt="明亮的现代客厅 · 原图"></td><td><img src="images/lifestyle-bright-living-room-after.webp" width="260" alt="明亮的现代客厅 · 效果"></td></tr></table>

把商品放到明亮客厅里的浅色橡木边柜上，背后是虚化的沙发和绿植。适合花瓶、台灯、蜡烛、家居摆件和小家具，让买家能想象它放在家里的样子。光线来自大窗户的自然光，商品的形状、表面质感和颜色保持不变。

```text
商品保持原样，形状、表面质感和颜色都不变。放在明亮现代客厅里的浅色橡木边柜上，背后是柔和虚化的沙发和绿植。大窗户透进自然光，阴影方向与光线一致，写实的家居目录照片。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-bright-living-room?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Living Room, Home Decor, Interior, Daylight

### 阳光野餐布

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-outdoor-picnic-before.webp" width="260" alt="阳光野餐布 · 原图"></td><td><img src="images/lifestyle-outdoor-picnic-after.webp" width="260" alt="阳光野餐布 · 效果"></td></tr></table>

把商品放在阳光公园里的格子野餐布上，旁边有藤编篮和新鲜水果。适合水杯、零食、防晒和便携音箱这类夏季或户外商品。公园背景保持虚化，商品始终是画面里最清晰的部分。

```text
商品保持不变。放在阳光公园里的红白格子野餐布上，旁边有藤编篮和新鲜水果，背景的树木柔和虚化。明亮的自然光和柔和阴影，浅景深，轻快的夏日生活方式照片。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-outdoor-picnic?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Picnic, Outdoor, Summer, Drinkware

### 霓虹电竞桌面

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/lifestyle-neon-gaming-desk-before.webp" width="260" alt="霓虹电竞桌面 · 原图"></td><td><img src="images/lifestyle-neon-gaming-desk-after.webp" width="260" alt="霓虹电竞桌面 · 效果"></td></tr></table>

把商品放到电竞桌面的深色鼠标垫上，紫色和青色霓虹灯照明，背后是虚化的键盘和显示器光。适合鼠标、耳机、手柄、键盘这类游戏外设。霓虹灯会在商品边缘打出彩色反光，留意商品本身的颜色是否还看得准。

```text
商品保持不变，形状、按键和标志都不动。放在电竞桌面的深色鼠标垫上，背后是柔和虚化的机械键盘和显示器光。紫色和青色霓虹灯光，商品边缘带一点 RGB 反光。氛围感强、对比度高的数码产品照片。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/lifestyle-neon-gaming-desk?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Gaming, Neon, RGB, Tech

### 去除金属与玻璃反光 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/cleanup-remove-glare-reflections-before.webp" width="260" alt="去除金属与玻璃反光 · 原图"></td><td><img src="images/cleanup-remove-glare-reflections-after.webp" width="260" alt="去除金属与玻璃反光 · 效果"></td></tr></table>

去掉玻璃瓶、镀铬件、首饰、手机屏这类光滑表面上的窗户倒影、炫光和拍摄者自己的倒影。运行前只涂反光的那一块。模型会换成一道顺着表面弧度的柔和高光，材质依然有光泽，只是没了干扰。

```text
去除选区内反光表面上的眩光、窗户倒影和相机倒影，换成顺着曲面走向的平滑均匀高光，与商品其他部分无缝衔接。选区外保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/cleanup-remove-glare-reflections?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 去除杂物 · 标签: Reflection, Glare, Cleanup, Retouch

### 擦除条形码与价格贴纸 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/cleanup-erase-barcode-watermark-before.webp" width="260" alt="擦除条形码与价格贴纸 · 原图"></td><td><img src="images/cleanup-erase-barcode-watermark-after.webp" width="260" alt="擦除条形码与价格贴纸 · 效果"></td></tr></table>

擦掉包装上的条形码、价格贴纸和门店标签，让商品照可以拿去做广告或放进自己的店铺。运行前把贴纸涂出来，模型会把底下的印刷图案补齐。补出来的印刷可能和原样略有差别，完成后检查一下附近的小字。

```text
擦除选区内的条形码、价格贴纸和文字标签，还原下面的包装，让底色、材质和印刷图案自然延续，不留污迹或残边。选区外保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/cleanup-erase-barcode-watermark?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 去除杂物 · 标签: Barcode, Price Tag, Erase, Packaging

### 去除灰尘和指纹

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/cleanup-dust-fingerprints-before.webp" width="260" alt="去除灰尘和指纹 · 原图"></td><td><img src="images/cleanup-dust-fingerprints-after.webp" width="260" alt="去除灰尘和指纹 · 效果"></td></tr></table>

清掉商品表面的灰尘、绒毛、指纹和细小划痕，形状、表面质感、标志和背景都不动。亮面塑料、玻璃和抛光金属最容易留指纹，用它可以省掉一次重拍。较深的划痕和凹痕也可能被抹平，当新品出售的商品不要用它掩盖真实瑕疵。

```text
去掉商品表面所有的灰尘、绒毛、指纹和细小划痕。形状、颜色、亮面质感、标志和反光都保持原样，背景不变。干净得像刚拆封一样。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/cleanup-dust-fingerprints?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 去除杂物 · 标签: Cleanup, Dust, Fingerprints, Retouch

### 把商品放进实拍场景 🖼

<table><tr><th>原图</th><th>参考图（IMG_2）</th><th>效果</th></tr><tr><td><img src="images/compose-product-into-scene-before.webp" width="260" alt="把商品放进实拍场景 · 原图"></td><td><img src="images/compose-product-into-scene-reference.webp" width="260" alt="把商品放进实拍场景 · 参考图（IMG_2）"></td><td><img src="images/compose-product-into-scene-after.webp" width="260" alt="把商品放进实拍场景 · 效果"></td></tr></table>

需要两张图：IMG_1 是场景，IMG_2 是商品。模型会把商品放到 IMG_1 的桌面上，透视、光线方向和色温都和场景对齐，并补上接触阴影。不用搭景就能出生活场景图。场景里没有桌子的话，把提示词里的“on the table”改成实际的台面。

```text
把 IMG_2 里的商品放到 IMG_1 的桌面上。商品的形状、标签和颜色与 IMG_2 完全一致。匹配 IMG_1 的透视、光线方向和色温，并加上自然的接触阴影，让它看起来像是现场拍的。IMG_1 其余部分保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/compose-product-into-scene?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 多图合成 · 标签: Composite, Scene, Lifestyle, Placement

### 两件商品合成套装图 🖼

<table><tr><th>原图</th><th>参考图（IMG_2）</th><th>效果</th></tr><tr><td><img src="images/compose-bundle-group-shot-before.webp" width="260" alt="两件商品合成套装图 · 原图"></td><td><img src="images/compose-bundle-group-shot-reference.webp" width="260" alt="两件商品合成套装图 · 参考图（IMG_2）"></td><td><img src="images/compose-bundle-group-shot-after.webp" width="260" alt="两件商品合成套装图 · 效果"></td></tr></table>

需要两张图：IMG_1 和 IMG_2 分别是两件商品的照片。结果是两件商品并排放在纯白背景上，光线和阴影一致，不用合拍就能做出礼盒或套装图。模型不知道商品的真实尺寸，如果两者大小差别明显，在提示词里写清楚，比如“瓶子的高度是罐子的两倍”。

```text
把 IMG_1 和 IMG_2 里的商品合成一张套装图。两件商品都保持原样，形状、标签和颜色都不变。并排放在纯白背景上，用同样柔和的影棚光和自然的接触阴影。干净的礼盒套装商品图。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/compose-bundle-group-shot?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 多图合成 · 标签: Bundle, Gift Set, Composite, White Background

### 套用已有的目录风格 🖼

<table><tr><th>原图</th><th>参考图（IMG_2）</th><th>效果</th></tr><tr><td><img src="images/compose-match-catalog-style-before.webp" width="260" alt="套用已有的目录风格 · 原图"></td><td><img src="images/compose-match-catalog-style-reference.webp" width="260" alt="套用已有的目录风格 · 参考图（IMG_2）"></td><td><img src="images/compose-match-catalog-style-after.webp" width="260" alt="套用已有的目录风格 · 效果"></td></tr></table>

需要两张图：IMG_1 是新商品的照片，IMG_2 是你现有目录里的一张图。新商品会套用 IMG_2 的背景色、光线方向、阴影风格和调色，新上架的款和老款放在一起不突兀。提示词要求模型不要照搬 IMG_2 里的商品，但还是检查一下有没有混进来。

```text
按 IMG_2 的风格重新处理 IMG_1：用一样的背景色、光线方向、阴影风格和调色。IMG_1 里的商品保持原样，形状、标签和颜色都不变。不要照搬 IMG_2 里的商品和道具。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/compose-match-catalog-style?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 多图合成 · 标签: Consistency, Catalog, Brand Style, Reference

## 服装

### 假人挂拍转模特街拍

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/apparel-ghost-mannequin-to-street-model-before.webp" width="260" alt="假人挂拍转模特街拍 · 原图"></td><td><img src="images/apparel-ghost-mannequin-to-street-model-after.webp" width="260" alt="假人挂拍转模特街拍 · 效果"></td></tr></table>

把隐形模特或平铺拍的服装照，变成模特在欧洲石板路上行走的街拍，黄昏侧光。版型、颜色、图案、纽扣和缝线都锁定不变。可以按品牌调性改提示词里的模特描述和地点，比如换成男模或现代城市街道。

```text
让照片里的这件衣服穿在一位高挑的女模特身上，她走在欧洲的鹅卵石街道上。衣服保持原样：版型、颜色、图案、纽扣和缝线都不变。布料有自然的褶皱和动感，黄金时刻侧光，35mm 街拍风格。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/apparel-ghost-mannequin-to-street-model?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Ghost Mannequin, On-Model, Street Style, Apparel

### 虚拟试穿 🖼

<table><tr><th>原图</th><th>参考图（IMG_2）</th><th>效果</th></tr><tr><td><img src="images/compose-virtual-try-on-before.webp" width="260" alt="虚拟试穿 · 原图"></td><td><img src="images/compose-virtual-try-on-reference.webp" width="260" alt="虚拟试穿 · 参考图（IMG_2）"></td><td><img src="images/compose-virtual-try-on-after.webp" width="260" alt="虚拟试穿 · 效果"></td></tr></table>

需要两张图：IMG_1 是人，IMG_2 是衣服。人物的脸、发型、身形和姿势都不变，穿上 IMG_2 的衣服，褶皱跟着姿势走。可以用来预览穿搭，或者让同一件衣服出现在不同模特身上。衣服图越清晰、越正面，效果越准。

```text
给 IMG_1 里的人穿上 IMG_2 的这件衣服。人物的脸、发型、身形和姿势保持不变。衣服的版型、颜色、面料纹理和缝线与 IMG_2 一致，并随姿势形成自然褶皱。保留 IMG_1 的背景和光线。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/compose-virtual-try-on?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 多图合成 · 标签: Try-On, Outfit, Lookbook, Apparel

### 面料换成真丝质感 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/apparel-silk-texture-upgrade-before.webp" width="260" alt="面料换成真丝质感 · 原图"></td><td><img src="images/apparel-silk-texture-upgrade-after.webp" width="260" alt="面料换成真丝质感 · 效果"></td></tr></table>

把衣服面料换成厚实有光泽的桑蚕丝，版型、缝线、颜色和合身度都不变。运行前先涂出衣服的区域。适合在打样前预览换面料或做高端款的效果。把提示词里的“mulberry silk”换成别的面料，就能试其他材质。

```text
把选区内衣服的面料换成有光泽的重磅桑蚕丝，垂坠流畅，褶皱处带柔和高光。衣服的剪裁、缝线、颜色和版型不变，选区外保持原样。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/apparel-silk-texture-upgrade?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Silk, Fabric, Texture Swap, Apparel

### 抚平衣物褶皱 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/cleanup-smooth-fabric-wrinkles-before.webp" width="260" alt="抚平衣物褶皱 · 原图"></td><td><img src="images/cleanup-smooth-fabric-wrinkles-after.webp" width="260" alt="抚平衣物褶皱 · 效果"></td></tr></table>

像用挂烫机熨过一样抚平衣服上的褶皱，同时保留织物纹理和衣服本身的明暗。先涂出有褶皱的区域。商品图或模特图上有运输压痕时，不用重拍。手肘、腰部这类穿着时自然形成的褶皱别涂，衣服看起来才像真的穿在身上。

```text
抚平选区内的折痕和褶皱，效果像专业熨烫过一样。保留织物纹理、颜色、缝线和衣服自然的明暗。选区外保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/cleanup-smooth-fabric-wrinkles?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 去除杂物 · 标签: Wrinkles, Ironing, Flat Lay, Apparel

### 服装改色出多色款 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/fashion-garment-recolor-before.webp" width="260" alt="服装改色出多色款 · 原图"></td><td><img src="images/fashion-garment-recolor-after.webp" width="260" alt="服装改色出多色款 · 效果"></td></tr></table>

给衣服换颜色，纹理、缝线、褶皱和明暗都保留，看起来就是同一件衣服染成了新颜色。先涂出衣服，再把提示词里的“sage green”改成想要的颜色。每个颜色跑一次，一张照片就能出整套多色款。

```text
把选区内衣服的颜色改成鼠尾草绿。面料纹理、车线、褶皱、阴影和高光都保持原样，看起来就像同一件衣服换了染色。选区外保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/fashion-garment-recolor?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Recolor, Color Variant, Hoodie, Apparel

### 模特图换纯色影棚背景

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/fashion-model-studio-backdrop-before.webp" width="260" alt="模特图换纯色影棚背景 · 原图"></td><td><img src="images/fashion-model-studio-backdrop-after.webp" width="260" alt="模特图换纯色影棚背景 · 效果"></td></tr></table>

把杂乱的实景背景换成浅灰色无缝影棚背景，脚下补一道柔和的投影；模特、姿势、服装和身上的光线都不变。适合把不同场次拍的照片统一成同一套目录风格。想要纯白背景，把提示词里的“light gray”改掉即可。

```text
模特、姿势、服装和身上的光线都保持原样。把杂乱的背景换成无缝浅灰色影棚背景，脚后地面加一道柔和自然的阴影。干净的服装电商风格。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/fashion-model-studio-backdrop?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Model, Studio, Background, Apparel

## 人像

### 发色换成铂金色 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/portrait-platinum-blonde-hair-before.webp" width="260" alt="发色换成铂金色 · 原图"></td><td><img src="images/portrait-platinum-blonde-hair-after.webp" width="260" alt="发色换成铂金色 · 效果"></td></tr></table>

把头发换成带暖金底调的亮铂金色，发型、发丝、光泽和发际线都保留。运行前先涂出头发，脸部就不会被改动。适合发型店和顾客在染发前预览效果。改提示词里的颜色描述，可以试其他发色。

```text
把选区内的头发染成明亮的铂金色，带一点柔和的金色底调。发型、发丝细节、光泽和发际线的自然过渡都保留。脸部和选区外保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/portrait-platinum-blonde-hair?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Hair, Hair Color, Blonde, Portrait

### 保留毛孔的自然修肤

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/portrait-skin-texture-refinement-before.webp" width="260" alt="保留毛孔的自然修肤 · 原图"></td><td><img src="images/portrait-skin-texture-refinement-after.webp" width="260" alt="保留毛孔的自然修肤 · 效果"></td></tr></table>

淡化脸上的泛红和小瑕疵，同时保留真实的毛孔、雀斑和肤色的自然变化，不会修成塑料脸。脸型、五官、表情和光线都不变。适合人像、形象照和头像这类只需要轻度修饰、不想用重度美颜的照片。

```text
修饰面部皮肤：淡化暂时性泛红和小瑕疵，同时保留真实的毛孔纹理、雀斑和自然的肤色变化，不要磨皮成塑料感。脸型、五官、表情和光线都保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/portrait-skin-texture-refinement?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修复精修 · 标签: Skin, Retouch, Beauty, Portrait

### 生活照变职业形象照

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/portrait-business-headshot-before.webp" width="260" alt="生活照变职业形象照 · 原图"></td><td><img src="images/portrait-business-headshot-after.webp" width="260" alt="生活照变职业形象照 · 效果"></td></tr></table>

把生活照变成职业形象照：中灰色影棚背景、藏青西装配白衬衫、正面柔光。脸、五官、发型和表情都保持原样。适合领英、公司官网或演讲嘉宾介绍。原图最好是正对镜头、光线均匀的照片。

```text
把这张照片变成职业形象照。人物的脸、五官、发型和表情完全不变。背景换成平滑的中灰色影棚背景，换上藏青色西装外套配白衬衫，左前方柔和主光。眼睛清晰对焦。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/portrait-business-headshot?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Headshot, LinkedIn, Business, Portrait

### 证件照白底

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/portrait-id-photo-before.webp" width="260" alt="证件照白底 · 原图"></td><td><img src="images/portrait-id-photo-after.webp" width="260" alt="证件照白底 · 效果"></td></tr></table>

生成护照风格的证件照：正面头肩构图、纯白背景、光线均匀无阴影。脸、五官、发型和肤色都保持原样。不同国家和证件对尺寸、背景的要求不一样，提交前请对照官方要求，并裁成规定的尺寸。

```text
做成证件照：正面头肩构图，纯白背景，光线均匀，脸上和背景都没有阴影。人物的脸、五官、发型和肤色完全不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/portrait-id-photo?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: ID Photo, Passport, White Background, Portrait

### 去除背景路人 🖌

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/portrait-remove-photobomber-before.webp" width="260" alt="去除背景路人 · 原图"></td><td><img src="images/portrait-remove-photobomber-after.webp" width="260" alt="去除背景路人 · 效果"></td></tr></table>

去掉照片背景里的陌生人或路人，并把他们身后的景物补齐，不留模糊、涂抹痕迹或残影。运行前涂出要去掉的人。主体和涂抹区域以外的内容都不变，旅行照特别用得上。

```text
去掉选区内的路人，补全他们身后的背景，让景物、光线和透视自然延续，不留模糊、涂抹痕迹或残影。主体人物和选区外保持不变。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/portrait-remove-photobomber?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 去除杂物 · 标签: Photobomber, Tourists, Erase, Travel

## 营销

### 圣诞松枝与暖色光斑

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/seasonal-christmas-pine-bokeh-before.webp" width="260" alt="圣诞松枝与暖色光斑 · 原图"></td><td><img src="images/seasonal-christmas-pine-bokeh-after.webp" width="260" alt="圣诞松枝与暖色光斑 · 效果"></td></tr></table>

把商品放在深色做旧木板上，周围是新鲜松枝和挂霜松果，背景是彩灯形成的暖色光斑。不用搭景就有一套现成的圣诞场景，适合圣诞促销、礼物推荐和节日横幅。商品本身不变，同一张商品图可以反复用来做各个节日的图。

```text
商品保持不变。放在做旧的深色木板上，周围是新鲜松枝和几颗挂霜的松果，背景里金色小灯串形成温暖的圆形光斑。温馨高级的圣诞促销氛围。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/seasonal-christmas-pine-bokeh?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Christmas, Holiday, Winter, Bokeh

### 夏日泳池水波与光影

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/seasonal-summer-pool-water-ripples-before.webp" width="260" alt="夏日泳池水波与光影 · 原图"></td><td><img src="images/seasonal-summer-pool-water-ripples-after.webp" width="260" alt="夏日泳池水波与光影 · 效果"></td></tr></table>

让商品立在清澈的浅蓝泳池水里，阳光在商品上投下水波光纹，底部有一圈涟漪。适合饮料、防晒、泳装配件等主打夏天的商品。防水的商品放在水里最自然；不该沾水的商品，换成泳池边的干燥场景更稳妥。

```text
商品保持不变。让它立在清澈的绿松石色浅水中，阳光焦散在商品表面跳动，底部有轻柔的涟漪。明亮的热带阳光，清凉的夏日促销氛围。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/seasonal-summer-pool-water-ripples?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Summer, Water, Caustics, Refreshing

### 黑五黑金展台

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/seasonal-black-friday-gold-geometry-before.webp" width="260" alt="黑五黑金展台 · 原图"></td><td><img src="images/seasonal-black-friday-gold-geometry-after.webp" width="260" alt="黑五黑金展台 · 效果"></td></tr></table>

把商品放在黄铜包边的哑光黑色六角展台上，背后是深色缎面，顶部一束聚光。提示词明确要求不加文字，你可以在设计工具里自己叠黑五文案和折扣。适合想做促销、又不想显得廉价的高端商品。

```text
商品保持不变。放在带抛光黄铜包边的哑光黑色六角展台上，背景是流动的深色丝缎，顶部一束戏剧性的聚光。奢华的黑五促销氛围，高端商业摄影。不要添加任何文字。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/seasonal-black-friday-gold-geometry?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Black Friday, Gold, Luxury, Promo

### 商品图做成促销海报

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/campaign-sale-poster-text-before.webp" width="260" alt="商品图做成促销海报 · 原图"></td><td><img src="images/campaign-sale-poster-text-after.webp" width="260" alt="商品图做成促销海报 · 效果"></td></tr></table>

把商品照做成促销海报：顶部是“SUMMER SALE”，商品下方是“50% OFF”，珊瑚色背景配简单几何图形。把引号里的两段文字换成你自己的活动，尽量写短，短文字更容易生成准确。发布前逐字校对一遍。

```text
把这张商品图做成促销海报。商品保持不变并居中。顶部加标题 "SUMMER SALE"，商品下方加 "50% OFF"，用粗体干净的无衬线字，背景是明亮的珊瑚色配简单几何图形。文字拼写与给定的完全一致。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/campaign-sale-poster-text?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修改主体 · 标签: Poster, Sale, Typography, Promo

### 新春红金氛围

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/seasonal-lunar-new-year-before.webp" width="260" alt="新春红金氛围 · 原图"></td><td><img src="images/seasonal-lunar-new-year-after.webp" width="260" alt="新春红金氛围 · 效果"></td></tr></table>

把商品放在红漆托盘上，周围是梅花枝和小金饰，背景是发光的红灯笼。适合春节促销、年货礼盒和节日社交媒体图，尤其是面向中文市场的店铺。红色商品容易和背景混在一起，浅色、金色或金属质感的商品最出效果。

```text
商品保持不变。放在红色漆托盘上，周围点缀梅花枝和小金饰，背景是虚化发光的红灯笼。温暖喜庆的新春促销氛围，浓郁的红金色调。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/seasonal-lunar-new-year?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 换背景 · 标签: Lunar New Year, Festive, Red, Gold

## 修复

### 泛黄老照片修复

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/restore-vintage-photo-reconstruction-before.webp" width="260" alt="泛黄老照片修复 · 原图"></td><td><img src="images/restore-vintage-photo-reconstruction-after.webp" width="260" alt="泛黄老照片修复 · 效果"></td></tr></table>

去掉老照片的泛黄、灰尘、划痕和折痕，并恢复面部和眼睛的细节。人物的五官、表情、衣着和原始构图都保留。先把照片平放，在均匀光线下扫描或翻拍；光面相纸上的反光很难修复。

```text
修复这张老照片：去掉泛黄色偏、灰尘斑点、划痕和折痕，还原清晰自然的面部与眼神细节。人物的五官、表情、服装和原始构图都保持不变。干净的档案级画质，对比自然。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/restore-vintage-photo-reconstruction?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修复精修 · 标签: Old Photo, Restoration, Scratches, Vintage

### 黑白照片上色

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/restore-colorize-bw-before.webp" width="260" alt="黑白照片上色 · 原图"></td><td><img src="images/restore-colorize-bw-after.webp" width="260" alt="黑白照片上色 · 效果"></td></tr></table>

给黑白照片加上符合年代感的自然色彩：真实的肤色、衣服和环境，不是滤镜那种整片单色。细节、颗粒和构图都不动，只加颜色。颜色是模型推测的，如果你知道某件衣服或某辆车原本的颜色，可以直接写进提示词。

```text
给这张黑白照片上色，使用自然且符合年代的色彩：真实的肤色、服装和环境颜色。所有细节、颗粒质感和构图完全不变，只添加颜色。避免过饱和或整体单一色调。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/restore-colorize-bw?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修复精修 · 标签: Colorize, Black and White, Vintage, Family

### 去模糊与降噪

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/restore-deblur-sharpen-before.webp" width="260" alt="去模糊与降噪 · 原图"></td><td><img src="images/restore-deblur-sharpen-after.webp" width="260" alt="去模糊与降噪 · 效果"></td></tr></table>

去掉运动模糊和噪点，让模糊的照片恢复清晰边缘和细节纹理。提示词要求不添加新细节、不改变形状，人脸和物体都忠于原图。轻度模糊效果最好；严重失焦的照片能改善的程度有限。

```text
让这张模糊、有噪点的照片变清晰：去掉运动模糊和噪点，恢复锐利的边缘和细腻纹理。主体、颜色、光线和构图完全不变，不要添加新细节或改变任何形状。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/restore-deblur-sharpen?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修复精修 · 标签: Deblur, Denoise, Sharpen, Pet

### 暗光照片提亮

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/restore-low-light-fix-before.webp" width="260" alt="暗光照片提亮 · 原图"></td><td><img src="images/restore-low-light-fix-after.webp" width="260" alt="暗光照片提亮 · 效果"></td></tr></table>

把曝光不足的照片提亮，比如室内聚餐或夜间聚会：提高曝光、找回暗部细节、校正偏色并降噪。场景、人物和构图都不变，光线看起来依然自然。提示词里提到了人脸和桌子，按照你照片里的实际内容改一下这部分。

```text
修复这张曝光不足的照片：提高曝光，让人脸和桌面清晰可见，找回暗部细节，校正偏色并降噪。场景、人物和构图完全不变，光线看起来自然。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/restore-low-light-fix?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 修复精修 · 标签: Low Light, Exposure, Color Cast, Denoise

## 创意

### 宠物照变收藏手办

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/creative-collectible-figure-before.webp" width="260" alt="宠物照变收藏手办 · 原图"></td><td><img src="images/creative-collectible-figure-after.webp" width="260" alt="宠物照变收藏手办 · 效果"></td></tr></table>

把宠物照变成 1/7 比例的收藏手办，立在透明亚克力底座上，摆在电脑桌上，后面放着印有同款形象的包装盒。毛色、花纹和姿势都保留，一眼就能认出是你家的宠物。宠物全身入镜、光线清楚的照片效果最好，其他动物也同样适用。

```text
把照片里的动物做成 1/7 比例的收藏手办，立在电脑桌上的透明亚克力圆底座上。后面放一个印着同一角色的玩具包装盒。保留动物的花纹、颜色和姿态。写实的影棚产品照，柔和光线。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/creative-collectible-figure?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 风格转换 · 标签: Figurine, Toy, Pet, Nano Banana

### 照片变水彩插画

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/creative-watercolor-illustration-before.webp" width="260" alt="照片变水彩插画 · 原图"></td><td><img src="images/creative-watercolor-illustration-after.webp" width="260" alt="照片变水彩插画 · 效果"></td></tr></table>

把照片重绘成纹理纸上的水彩插画：柔和的晕染、看得见的笔触和细墨线，构图依然认得出来。适合旅行照、建筑和街景，可以做贺卡、装饰画或博客头图。主体明确、背景简单的照片画出来最干净。

```text
把这张照片重绘成水彩插画，画在有纹理的纸上：柔和的色彩晕染、可见的笔触和细墨线。构图、建筑和主要形状保持可辨认。色调轻盈通透，留出纸张的白。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/creative-watercolor-illustration?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 风格转换 · 标签: Watercolor, Illustration, Travel, Art

### 照片变 3D 黏土风

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/creative-3d-clay-before.webp" width="260" alt="照片变 3D 黏土风 · 原图"></td><td><img src="images/creative-3d-clay-after.webp" width="260" alt="照片变 3D 黏土风 · 效果"></td></tr></table>

把照片变成手工黏土定格动画风格：圆润的造型、黏土上的指纹质感和微缩场景。主体的姿势、颜色和关键特征都认得出来。人、宠物、商品都能用，适合做有趣的头像、贴纸或社交媒体配图。

```text
把这张照片变成手工 3D 黏土动画风格：圆润柔和的造型、黏土上可见的指纹纹理和微缩布景。保留主体的姿势、颜色和主要特征。温暖柔光，俏皮的定格动画质感。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/creative-3d-clay?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 风格转换 · 标签: Clay, 3D, Stop Motion, Cute

### 线稿变产品效果图

<table><tr><th>原图</th><th>效果</th></tr><tr><td><img src="images/creative-sketch-to-render-before.webp" width="260" alt="线稿变产品效果图 · 原图"></td><td><img src="images/creative-sketch-to-render-after.webp" width="260" alt="线稿变产品效果图 · 效果"></td></tr></table>

把铅笔线稿变成照片级的产品效果图，形状和比例严格按线稿来。示例提示词描述的是一双白色皮革、灰色麂皮、橡胶底的运动鞋，换成你自己的设计时改写材质那一句即可。设计师可以在打样前就把概念展示给客户或工厂。

```text
把这张铅笔线稿变成写实的产品效果图。严格按照线稿的造型、比例和细节。使用真实材质：白色皮革鞋面、灰色麂皮拼接和橡胶鞋底，浅灰色影棚背景，柔和阴影。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/creative-sketch-to-render?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 风格转换 · 标签: Sketch, Render, Product Design, Sneaker

### 参考图风格迁移 🖼

<table><tr><th>原图</th><th>参考图（IMG_2）</th><th>效果</th></tr><tr><td><img src="images/compose-style-transfer-before.webp" width="260" alt="参考图风格迁移 · 原图"></td><td><img src="images/compose-style-transfer-reference.webp" width="260" alt="参考图风格迁移 · 参考图（IMG_2）"></td><td><img src="images/compose-style-transfer-after.webp" width="260" alt="参考图风格迁移 · 效果"></td></tr></table>

需要两张图：IMG_1 是要重绘的图，IMG_2 是风格参考。结果保留 IMG_1 的构图、主体和比例，借用 IMG_2 的配色、质感和笔触，但不会照搬里面的物体。可以用来对齐品牌插画风格，或者把某幅画的风格套到自己的照片上。

```text
按 IMG_2 的视觉风格重绘 IMG_1：采用它的配色、质感和笔触。IMG_1 的构图、主体和比例保持不变，不要照搬 IMG_2 里的任何物体。
```

[在 YepShot 中打开 →](https://yepshot.com/zh/explore/compose-style-transfer?utm_source=github&utm_medium=awesome-nano-banana-prompts) · 多图合成 · 标签: Style Transfer, Reference, Art, Print

## 用 Gemini API 调用这些提示词

把图片和提示词放在同一个请求里发送，模型 ID 是 `gemini-nano-banana-2.1`。

```js
import { GoogleGenAI } from "@google/genai";
import { readFileSync, writeFileSync } from "node:fs";

const ai = new GoogleGenAI({ apiKey: process.env.GEMINI_API_KEY });
const response = await ai.models.generateContent({
  model: "gemini-nano-banana-2.1",
  contents: [{
    role: "user",
    parts: [
      { text: "<a prompt from this list>" },
      { inlineData: { mimeType: "image/jpeg", data: readFileSync("photo.jpg").toString("base64") } },
    ],
  }],
  config: { responseModalities: ["IMAGE"], imageConfig: { imageSize: "1K" } },
});

const image = response.candidates[0].content.parts.find((part) => part.inlineData);
writeFileSync("result.png", Buffer.from(image.inlineData.data, "base64"));
```

🖌 类提示词再加一段文字 `Apply the edit only inside the white region of the following mask.`，后面跟一张黑白遮罩图，白色是要改的区域。这里的示例就是这样做的。

## 参与贡献

有效果更好的写法，或者某条在你的图上不灵？开个 issue，附上提示词和前后对比。

## 许可

提示词、文字和图片采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans) 许可。转载或二次使用请注明 "YepShot" 并附上 https://yepshot.com 链接。

---

由 [YepShot](https://yepshot.com/zh/?utm_source=github&utm_medium=awesome-nano-banana-prompts) 维护：一个 AI 修图工具，支持画笔遮罩和 1K 到 4K 输出。与 Google 无关；Nano Banana 是 Google 对其 Gemini 图像模型的称呼。
