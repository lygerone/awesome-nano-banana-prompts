# Awesome Nano Banana Prompts

48 tested photo-editing prompts for Nano Banana 2.1, Google's image model. Every prompt comes with a real before-and-after, and every prompt is ready to paste: no placeholders to fill in.

[中文版](README.zh-CN.md) · [Try them in YepShot](https://yepshot.com/explore?utm_source=github&utm_medium=awesome-nano-banana-prompts) · [prompts.json](prompts.json)

<img src="images/studio-pure-white-amazon-after.webp" width="220"> <img src="images/campaign-sale-poster-text-after.webp" width="220"> <img src="images/lifestyle-travertine-stone-after.webp" width="220">

## How the examples were made

- The before photos are synthetic. They were generated with Nano Banana 2.1 to look like ordinary, slightly messy phone photos, so the edit is easy to see. No real people's photos and no real brands are used.
- The after images are the output of running the prompt exactly as written, on Nano Banana 2.1 at 1K. They were checked by hand and not retouched.
- 🖌 means the prompt needs a mask: paint over the area to change first. In the examples the mask was drawn automatically around the target.
- 🖼 means the prompt takes two images: IMG_1 is the main photo, IMG_2 is the reference.

## Contents

- [Product](#product) (22)
- [Fashion](#fashion) (6)
- [Portrait](#portrait) (5)
- [Campaigns](#campaigns) (6)
- [Restoration](#restoration) (4)
- [Creative](#creative) (5)
- [Using the prompts with the Gemini API](#using-the-prompts-with-the-gemini-api)

## Product

### Pure White Marketplace Packshot

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-pure-white-amazon-before.webp" width="260" alt="Pure White Marketplace Packshot · Before"></td><td><img src="images/studio-pure-white-amazon-after.webp" width="260" alt="Pure White Marketplace Packshot · After"></td></tr></table>

Use this for marketplace main images, where Amazon and many other marketplaces ask for the product alone on pure white. It works from any reasonably sharp product photo, even one shot on a cluttered desk. The prompt keeps the label and proportions fixed, but check small text on the packaging before you publish.

```text
Keep the product exactly as it is, including its shape, label, colors and proportions. Replace the background with pure white (#FFFFFF) and center the product. Light it with soft, even studio light from both sides and add a subtle natural contact shadow under its base. Crisp edges, no color spill, clean e-commerce packshot.
```

[Open in YepShot →](https://yepshot.com/explore/studio-pure-white-amazon?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Amazon, Shopify, White Background, Packshot

### Black Acrylic Mirror Reflection

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-acrylic-reflection-before.webp" width="260" alt="Black Acrylic Mirror Reflection · Before"></td><td><img src="images/studio-acrylic-reflection-after.webp" width="260" alt="Black Acrylic Mirror Reflection · After"></td></tr></table>

Gives an ordinary product shot the dark, glossy look of a premium brand ad: black acrylic, a mirror reflection and rim light on both edges. It suits bottles, watches, perfume and electronics with clear outlines. Products that are already very dark can blend into the background, so start from a well-lit photo.

```text
Keep the product unchanged. Place it on glossy black acrylic with a crisp mirror reflection that fades downward. Use a dark, seamless background and a dramatic rim light along both edges of the product. Deep contrast, luxury brand look, ultra-sharp detail.
```

[Open in YepShot →](https://yepshot.com/explore/studio-acrylic-reflection?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Luxury, Reflection, Dark Studio, Rim Light

### Floating Hero Shot

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-floating-ambient-shadow-before.webp" width="260" alt="Floating Hero Shot · Before"></td><td><img src="images/studio-floating-ambient-shadow-after.webp" width="260" alt="Floating Hero Shot · After"></td></tr></table>

Lifts the product a couple of centimeters off a seamless off-white backdrop with a soft shadow underneath, a common hero-image style for shoes, bags, cosmetics and gadgets. It looks clean and modern without a busy scene. To change how high the product floats, edit the "2 cm" in the prompt.

```text
Keep the product unchanged. Make it float about 2 cm above a seamless off-white studio backdrop, with a soft, diffused shadow on the floor directly beneath it. Soft overhead lighting, clean and minimal catalog style.
```

[Open in YepShot →](https://yepshot.com/explore/studio-floating-ambient-shadow?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Levitation, Studio, Shadow, Catalog

### Overhead Flat Lay on Light Gray

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-overhead-flat-lay-before.webp" width="260" alt="Overhead Flat Lay on Light Gray · Before"></td><td><img src="images/studio-overhead-flat-lay-after.webp" width="260" alt="Overhead Flat Lay on Light Gray · After"></td></tr></table>

Turns an angled snapshot into a straight-down flat lay on a light gray seamless background, the clean top view marketplaces often use for wallets, accessories, folded apparel and stationery. Because the model redraws the product from above, it has to infer parts your photo did not show, so compare edges and details with the real item before you publish.

```text
Keep the product exactly as it is, including its shape, stitching, colors and any logo. Show it as an overhead flat lay, photographed straight down and centered on a light gray seamless background. Soft, even lighting with only a faint shadow. Clean, minimal marketplace listing photo.
```

[Open in YepShot →](https://yepshot.com/explore/studio-overhead-flat-lay?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Flat Lay, Top View, Gray Background, Accessories

### Three-Quarter Catalog Angle

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-three-quarter-angle-before.webp" width="260" alt="Three-Quarter Catalog Angle · Before"></td><td><img src="images/studio-three-quarter-angle-after.webp" width="260" alt="Three-Quarter Catalog Angle · After"></td></tr></table>

Turns a straight-on product photo into a three-quarter view on pure white, so every product in a catalog can share the same 45-degree angle. Use it when your photos were shot from different angles and the listing grid looks uneven. The model has to imagine the side your photo did not show, so check it against the real product before you publish.

```text
Keep the product's design, colors, materials and logo exactly as they are. Show it at a three-quarter angle, turned about 45 degrees to the left, on a pure white background with a soft contact shadow. Even studio lighting, consistent e-commerce catalog style.
```

[Open in YepShot →](https://yepshot.com/explore/studio-three-quarter-angle?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Catalog, 45 Degree, White Background, Consistency

### Material Close-Up for Detail Images

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-material-detail-closeup-before.webp" width="260" alt="Material Close-Up for Detail Images · Before"></td><td><img src="images/studio-material-detail-closeup-after.webp" width="260" alt="Material Close-Up for Detail Images · After"></td></tr></table>

Turns a full product shot into a close-up of its material, stitching and hardware, the kind of detail image that follows the main photo in a listing. It suits leather goods, bags, shoes and textiles. The model fills in fine texture your photo may not resolve, so treat the result as a styled detail shot and make sure it matches what buyers will receive.

```text
Turn this into a close-up detail shot of the product's material and craftsmanship. Fill the frame with its surface texture, stitching and hardware, using a shallow depth of field and soft side light that brings out the texture. Keep the colors, materials and hardware finish exactly as in the original photo.
```

[Open in YepShot →](https://yepshot.com/explore/studio-material-detail-closeup?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Detail Shot, Texture, Leather, Craftsmanship

### Preview Colorways Side by Side

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/studio-colorway-lineup-before.webp" width="260" alt="Preview Colorways Side by Side · Before"></td><td><img src="images/studio-colorway-lineup-after.webp" width="260" alt="Preview Colorways Side by Side · After"></td></tr></table>

Shows your product in four colors side by side: the original plus sage green, sand beige and charcoal. It helps when planning new colors or mocking up a color selector before samples arrive. Generated colors will not match real dye lots exactly, so do not use the result as the listing photo for a color you have not photographed. Swap the three color names for your own.

```text
Show this product in four colorways side by side: its original color, sage green, sand beige and charcoal black. Keep the shape, materials, details and logo identical across all four. Space them evenly on a light gray background with the same soft studio light and matching shadows.
```

[Open in YepShot →](https://yepshot.com/explore/studio-colorway-lineup?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Colorways, Variants, Mockup, Lineup

### Change the Name on a Product Label 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/text-label-name-swap-before.webp" width="260" alt="Change the Name on a Product Label · Before"></td><td><img src="images/text-label-name-swap-after.webp" width="260" alt="Change the Name on a Product Label · After"></td></tr></table>

Swaps one word on a label, such as a flavor or variant name, keeping the lettering around it. Brush over the word, then put the new name in the quotes; a name of similar length fits the space most easily. In our test, LAVENDER came out in the same green serif capitals, followed the curve of the jar, and nothing else on the label changed. Use it for mockups and ads; photograph the real variant for its listing.

```text
Replace the text in the marked area with "LAVENDER". Match the original lettering exactly: the same typeface, weight, color and letter spacing, following the curve of the label. Keep everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/text-label-name-swap?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Label, Packaging, Text, Variant

### Translate the Text on Packaging

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/text-translate-packaging-before.webp" width="260" alt="Translate the Text on Packaging · Before"></td><td><img src="images/text-translate-packaging-after.webp" width="260" alt="Translate the Text on Packaging · After"></td></tr></table>

Translates the English text on a box or label into Spanish while keeping the brand name, layout and illustration. Change "Spanish" to the language you need. In our test every line was translated correctly, including the text on the box's top flap, but the model kept English title case ("Té de Hierbas" where Spanish writes "Té de hierbas"). Have a native speaker check it, and use it for ads and mockups, since the real package is unchanged.

```text
Translate the English text on the packaging into Spanish. Keep the brand name as it is, and give each translated line the same typeface, size, color and position as the original. Leave the product, the rest of the packaging and the background unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/text-translate-packaging?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Translation, Packaging, Localization, Text

### Travertine Block in Morning Light

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-travertine-stone-before.webp" width="260" alt="Travertine Block in Morning Light · Before"></td><td><img src="images/lifestyle-travertine-stone-after.webp" width="260" alt="Travertine Block in Morning Light · After"></td></tr></table>

Places the product on a raw travertine block with dried stems and dappled morning light, the warm, natural look used by skincare, candle and fragrance brands. Use it when a white background feels too clinical for social posts or a brand page. Shape, label and colors are held fixed, so the product stays recognizable.

```text
Keep the product exactly as it is, including its shape, label and colors. Place it on a raw-cut beige travertine block with a few dried botanical stems beside it. Soft morning window light casts dappled leaf shadows across the scene. Warm, organic mood, shallow depth of field, editorial lifestyle photo.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-travertine-stone?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Travertine, Cosmetics, Morning Light, Lifestyle

### Marble Vanity with Water Droplets

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-marble-bathroom-dew-before.webp" width="260" alt="Marble Vanity with Water Droplets · Before"></td><td><img src="images/lifestyle-marble-bathroom-dew-after.webp" width="260" alt="Marble Vanity with Water Droplets · After"></td></tr></table>

Sets the product on a white Carrara marble vanity with water droplets and a blurred spa bathroom behind it. It fits skincare, body care and bath products that should look fresh and clean. The background stays soft so the product is the sharpest thing in the frame, which helps on small listing thumbnails.

```text
Keep the product unchanged. Place it on a polished white Carrara marble bathroom vanity with fine water droplets on the surface. Soft light through a frosted window, a blurred luxury spa bathroom in the background. Fresh, clean skincare advertising look with crisp focus on the product.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-marble-bathroom-dew?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Marble, Bathroom, Water Drops, Skincare

### Oak Table with Kitchen Props

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-scandinavian-wood-kitchen-before.webp" width="260" alt="Oak Table with Kitchen Props · Before"></td><td><img src="images/lifestyle-scandinavian-wood-kitchen-after.webp" width="260" alt="Oak Table with Kitchen Props · After"></td></tr></table>

Puts the product on an oak table with a ceramic cup and a linen napkin in warm side light, like a photo taken in a real Scandinavian home. It suits kitchenware, food packaging, coffee and small home goods. The props are few and neutral, so they set the mood without competing with what you sell.

```text
Keep the product unchanged. Place it on a natural oak tabletop with visible wood grain, with a ceramic cup and a linen napkin nearby. Warm daylight from a side window, authentic Scandinavian home atmosphere, f/4 depth of field, product in sharp focus.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-scandinavian-wood-kitchen?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Kitchen, Oak Wood, Homeware, Warm

### Concrete Podium, Tech Style

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-industrial-concrete-podium-before.webp" width="260" alt="Concrete Podium, Tech Style · Before"></td><td><img src="images/lifestyle-industrial-concrete-podium-after.webp" width="260" alt="Concrete Podium, Tech Style · After"></td></tr></table>

Places the product on a raw concrete cylinder with a few brushed-metal shapes and hard, angular shadows. The cool, architectural look suits headphones, chargers, phone cases and other tech accessories. If you sell something else and want the same industrial set, swap "tech accessories" in the prompt for your own category.

```text
Keep the product unchanged. Place it on a minimalist raw gray concrete cylinder podium with a few brushed-metal geometric shapes around it. Cool architectural light with sharp, angular shadows. Modern industrial look for tech accessories, high detail.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-industrial-concrete-podium?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Tech, Concrete, Industrial, Minimalist

### Bright Modern Living Room

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-bright-living-room-before.webp" width="260" alt="Bright Modern Living Room · Before"></td><td><img src="images/lifestyle-bright-living-room-after.webp" width="260" alt="Bright Modern Living Room · After"></td></tr></table>

Places the product on a light oak sideboard in a bright living room with a sofa and plants softly blurred behind it. It suits vases, lamps, candles, decor and small furniture that buyers want to picture at home. Daylight comes from a large window, and the product's shape, finish and colors are held fixed.

```text
Keep the product exactly as it is, including its shape, finish and colors. Place it on a light oak sideboard in a bright, modern living room, with a sofa and green plants softly blurred behind it. Natural daylight from a large window, shadows that match the light, photorealistic interior catalog photo.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-bright-living-room?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Living Room, Home Decor, Interior, Daylight

### Sunny Picnic Blanket

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-outdoor-picnic-before.webp" width="260" alt="Sunny Picnic Blanket · Before"></td><td><img src="images/lifestyle-outdoor-picnic-after.webp" width="260" alt="Sunny Picnic Blanket · After"></td></tr></table>

Sets the product on a checkered picnic blanket in a sunny park with a wicker basket and fresh fruit nearby. It fits drinkware, snacks, sunscreen, portable speakers and other summer or outdoor products. The park stays softly blurred so the product remains the sharpest thing in the frame.

```text
Keep the product unchanged. Place it on a red and white checkered picnic blanket in a sunny park, with a wicker basket and fresh fruit nearby and trees softly blurred in the background. Bright natural daylight with soft shadows, shallow depth of field, cheerful summer lifestyle photo.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-outdoor-picnic?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Picnic, Outdoor, Summer, Drinkware

### Neon Gaming Desk

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/lifestyle-neon-gaming-desk-before.webp" width="260" alt="Neon Gaming Desk · Before"></td><td><img src="images/lifestyle-neon-gaming-desk-after.webp" width="260" alt="Neon Gaming Desk · After"></td></tr></table>

Puts the product on a dark desk mat in a gaming setup lit by purple and cyan neon, with a keyboard and monitor glow blurred behind it. It suits mice, headsets, controllers, keyboards and other gaming gear. The neon adds colored reflections along the product's edges, so check that its own colors still read correctly.

```text
Keep the product unchanged, including its shape, buttons and logo. Place it on a dark desk mat in a gaming setup, with a mechanical keyboard and the glow of a monitor softly blurred behind it. Purple and cyan neon light with subtle RGB reflections along the product's edges. Moody, high-contrast tech product photo.
```

[Open in YepShot →](https://yepshot.com/explore/lifestyle-neon-gaming-desk?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Gaming, Neon, RGB, Tech

### Remove Glare on Shiny Surfaces 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/cleanup-remove-glare-reflections-before.webp" width="260" alt="Remove Glare on Shiny Surfaces · Before"></td><td><img src="images/cleanup-remove-glare-reflections-after.webp" width="260" alt="Remove Glare on Shiny Surfaces · After"></td></tr></table>

Removes window reflections, glare and the photographer's own reflection from glossy surfaces such as glass bottles, chrome, jewelry and phone screens. Brush over only the reflective area before you run it. The glare is replaced with a smooth highlight that follows the curve of the surface, so it still looks shiny, just without the distractions.

```text
Remove the glare, window reflections and camera reflection in the marked area of the shiny surface. Replace them with a smooth, even highlight that follows the surface's curvature, so it blends seamlessly with the rest of the product. Keep everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/cleanup-remove-glare-reflections?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Remove · Tags: Reflection, Glare, Cleanup, Retouch

### Erase Barcode and Price Sticker 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/cleanup-erase-barcode-watermark-before.webp" width="260" alt="Erase Barcode and Price Sticker · Before"></td><td><img src="images/cleanup-erase-barcode-watermark-after.webp" width="260" alt="Erase Barcode and Price Sticker · After"></td></tr></table>

Erases barcodes, price stickers and store labels from packaging so the product photo can be reused in ads or on your own shop. Brush over the sticker before you run it, and the model rebuilds the printed pattern underneath. Check fine text near the edited area afterward, since rebuilt print can differ slightly from the original.

```text
Erase the barcode, price sticker and any text label in the marked area. Rebuild the packaging underneath so its color, texture and printed pattern continue naturally, with no smudges or leftover edges. Keep everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/cleanup-erase-barcode-watermark?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Remove · Tags: Barcode, Price Tag, Erase, Packaging

### Remove Dust and Fingerprints

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/cleanup-dust-fingerprints-before.webp" width="260" alt="Remove Dust and Fingerprints · Before"></td><td><img src="images/cleanup-dust-fingerprints-after.webp" width="260" alt="Remove Dust and Fingerprints · After"></td></tr></table>

Cleans dust, lint, fingerprints and fine scratches off the product's surface while leaving its shape, finish, logo and the background alone. Glossy plastic, glass and polished metal show smudges the most, and this saves a reshoot. Deeper scratches and dents can get smoothed over too, so do not use it to hide real damage on items you sell as new.

```text
Remove all dust, lint, fingerprints and fine scratches from the product's surface. Keep its shape, color, glossy finish, logo and reflections exactly as they are, and leave the background unchanged. Clean, freshly unboxed look.
```

[Open in YepShot →](https://yepshot.com/explore/cleanup-dust-fingerprints?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Remove · Tags: Cleanup, Dust, Fingerprints, Retouch

### Place a Product into Your Scene 🖼

<table><tr><th>Before</th><th>Reference (IMG_2)</th><th>After</th></tr><tr><td><img src="images/compose-product-into-scene-before.webp" width="260" alt="Place a Product into Your Scene · Before"></td><td><img src="images/compose-product-into-scene-reference.webp" width="260" alt="Place a Product into Your Scene · Reference (IMG_2)"></td><td><img src="images/compose-product-into-scene-after.webp" width="260" alt="Place a Product into Your Scene · After"></td></tr></table>

Uses two images: IMG_1 is your scene, IMG_2 is the product. The product is placed on the table in IMG_1 with matching perspective, light direction and color temperature, plus a contact shadow. It is a quick way to get lifestyle shots without building a set. If your scene has no table, change "on the table" to the surface you have.

```text
Place the product from IMG_2 on the table in IMG_1. Keep the product's shape, label and colors exactly as in IMG_2. Match IMG_1's perspective, lighting direction and color temperature, and add a natural contact shadow so the product looks photographed in place. Keep the rest of IMG_1 unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/compose-product-into-scene?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Combine · Tags: Composite, Scene, Lifestyle, Placement

### Bundle Two Products into One Shot 🖼

<table><tr><th>Before</th><th>Reference (IMG_2)</th><th>After</th></tr><tr><td><img src="images/compose-bundle-group-shot-before.webp" width="260" alt="Bundle Two Products into One Shot · Before"></td><td><img src="images/compose-bundle-group-shot-reference.webp" width="260" alt="Bundle Two Products into One Shot · Reference (IMG_2)"></td><td><img src="images/compose-bundle-group-shot-after.webp" width="260" alt="Bundle Two Products into One Shot · After"></td></tr></table>

Uses two images: IMG_1 and IMG_2 are separate product photos. The result places both products side by side on pure white with matching light and shadows, a quick way to make a gift-set or bundle image without shooting them together. The model cannot know the products' real sizes, so if one is much larger, say so in the prompt, for example "the bottle is twice as tall as the jar".

```text
Combine the product in IMG_1 and the product in IMG_2 into one bundle photo. Keep both products exactly as they are, including their shapes, labels and colors. Arrange them side by side on a pure white background with the same soft studio light and natural contact shadows. Clean gift-set listing image.
```

[Open in YepShot →](https://yepshot.com/explore/compose-bundle-group-shot?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Combine · Tags: Bundle, Gift Set, Composite, White Background

### Match Your Existing Catalog Look 🖼

<table><tr><th>Before</th><th>Reference (IMG_2)</th><th>After</th></tr><tr><td><img src="images/compose-match-catalog-style-before.webp" width="260" alt="Match Your Existing Catalog Look · Before"></td><td><img src="images/compose-match-catalog-style-reference.webp" width="260" alt="Match Your Existing Catalog Look · Reference (IMG_2)"></td><td><img src="images/compose-match-catalog-style-after.webp" width="260" alt="Match Your Existing Catalog Look · After"></td></tr></table>

Uses two images: IMG_1 is the new product photo, IMG_2 is a photo from your existing catalog. The new product gets IMG_2's background color, lighting direction, shadow style and color grade, so a new SKU sits naturally next to the old ones. The prompt tells the model not to copy the product in IMG_2, but check that nothing from it slipped in.

```text
Restyle IMG_1 to match the look of IMG_2: use the same background color, lighting direction, shadow style and color grade. Keep the product in IMG_1 exactly as it is, including its shape, label and colors. Do not copy the product or props from IMG_2.
```

[Open in YepShot →](https://yepshot.com/explore/compose-match-catalog-style?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Combine · Tags: Consistency, Catalog, Brand Style, Reference

## Fashion

### Ghost Mannequin to Street Model

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/apparel-ghost-mannequin-to-street-model-before.webp" width="260" alt="Ghost Mannequin to Street Model · Before"></td><td><img src="images/apparel-ghost-mannequin-to-street-model-after.webp" width="260" alt="Ghost Mannequin to Street Model · After"></td></tr></table>

Turns a ghost-mannequin or flat-lay garment photo into a street-style shot of a model walking on cobblestones in golden-hour light. Cut, color, pattern, buttons and seams are held fixed. Edit the model description or the location in the prompt to match your brand, for example a male model or a modern city street.

```text
Show the garment in this photo worn by a tall female model walking on a European cobblestone street. Keep the garment exactly as it is: cut, color, pattern, buttons and seams. Natural fabric folds and movement, golden-hour side light, 35mm street fashion photo.
```

[Open in YepShot →](https://yepshot.com/explore/apparel-ghost-mannequin-to-street-model?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Ghost Mannequin, On-Model, Street Style, Apparel

### Virtual Try-On 🖼

<table><tr><th>Before</th><th>Reference (IMG_2)</th><th>After</th></tr><tr><td><img src="images/compose-virtual-try-on-before.webp" width="260" alt="Virtual Try-On · Before"></td><td><img src="images/compose-virtual-try-on-reference.webp" width="260" alt="Virtual Try-On · Reference (IMG_2)"></td><td><img src="images/compose-virtual-try-on-after.webp" width="260" alt="Virtual Try-On · After"></td></tr></table>

Uses two images: IMG_1 is the person, IMG_2 is the garment. The person keeps their face, hair, body shape and pose, and wears the garment with folds that follow that pose. It helps you preview an outfit or show one item on different people. A clear, front-facing garment photo gives the most accurate result.

```text
Dress the person in IMG_1 in the garment from IMG_2. Keep the person's face, hairstyle, body shape and pose unchanged. Keep the garment's cut, color, fabric texture and seams exactly as in IMG_2, with natural folds that fit the pose. Keep IMG_1's background and lighting.
```

[Open in YepShot →](https://yepshot.com/explore/compose-virtual-try-on?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Combine · Tags: Try-On, Outfit, Lookbook, Apparel

### Upgrade Fabric to Silk 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/apparel-silk-texture-upgrade-before.webp" width="260" alt="Upgrade Fabric to Silk · Before"></td><td><img src="images/apparel-silk-texture-upgrade-after.webp" width="260" alt="Upgrade Fabric to Silk · After"></td></tr></table>

Changes the fabric of a garment to heavy, lustrous mulberry silk while keeping its cut, seams, color and fit. Brush over the garment before you run it. It is useful for previewing a material upgrade or a premium version of a design before ordering samples. Replace "mulberry silk" with another fabric to try other materials.

```text
Change the fabric of the garment in the marked area to heavy, lustrous mulberry silk with a fluid drape and soft highlights along the folds. Keep the garment's cut, seams, color and fit unchanged, and keep everything outside the marked area as it is.
```

[Open in YepShot →](https://yepshot.com/explore/apparel-silk-texture-upgrade?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Silk, Fabric, Texture Swap, Apparel

### Smooth Out Fabric Wrinkles 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/cleanup-smooth-fabric-wrinkles-before.webp" width="260" alt="Smooth Out Fabric Wrinkles · Before"></td><td><img src="images/cleanup-smooth-fabric-wrinkles-after.webp" width="260" alt="Smooth Out Fabric Wrinkles · After"></td></tr></table>

Smooths creases in clothing as if it had been steamed, without flattening the weave or the garment's natural shading. Brush over the wrinkled area first. It saves a reshoot when a product or model photo shows packing folds. Leave natural folds at the elbows or waist unmarked so the garment still looks worn.

```text
Smooth out the creases and wrinkles in the marked area as if the garment had been professionally steamed. Keep the woven fabric texture, color, seams and the garment's natural shading. Keep everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/cleanup-smooth-fabric-wrinkles?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Remove · Tags: Wrinkles, Ironing, Flat Lay, Apparel

### Recolor a Garment 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/fashion-garment-recolor-before.webp" width="260" alt="Recolor a Garment · Before"></td><td><img src="images/fashion-garment-recolor-after.webp" width="260" alt="Recolor a Garment · After"></td></tr></table>

Recolors a garment while keeping its texture, stitching, folds and shading, so it looks like the same piece dyed in another color. Brush over the garment first, then change "sage green" in the prompt to the color you want. Run it once per color to build a full colorway set from a single photo.

```text
Change the color of the garment in the marked area to sage green. Keep the fabric texture, stitching, folds, shadows and highlights exactly as they are, so it looks like the same garment dyed in a new color. Keep everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/fashion-garment-recolor?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Recolor, Color Variant, Hoodie, Apparel

### Clean Studio Backdrop for Model Shots

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/fashion-model-studio-backdrop-before.webp" width="260" alt="Clean Studio Backdrop for Model Shots · Before"></td><td><img src="images/fashion-model-studio-backdrop-after.webp" width="260" alt="Clean Studio Backdrop for Model Shots · After"></td></tr></table>

Replaces a cluttered location background with a seamless light gray studio backdrop and a soft floor shadow, keeping the model, pose, outfit and the light on them unchanged. Use it to make photos from different shoots look like one consistent catalog. For a pure white background, change "light gray" in the prompt.

```text
Keep the model, pose, outfit and the lighting on the model exactly as they are. Replace the cluttered background with a seamless light gray studio backdrop and add a soft, natural shadow on the floor behind the feet. Clean fashion e-commerce look.
```

[Open in YepShot →](https://yepshot.com/explore/fashion-model-studio-backdrop?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Model, Studio, Background, Apparel

## Portrait

### Change Hair to Platinum Blonde 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/portrait-platinum-blonde-hair-before.webp" width="260" alt="Change Hair to Platinum Blonde · Before"></td><td><img src="images/portrait-platinum-blonde-hair-after.webp" width="260" alt="Change Hair to Platinum Blonde · After"></td></tr></table>

Recolors hair to bright platinum blonde with soft golden undertones, keeping the hairstyle, individual strands, shine and hairline. Brush over the hair before you run it so the face stays untouched. It lets salons and clients preview a color before committing to it. Edit the color description in the prompt to try other shades.

```text
Recolor the hair in the marked area to a bright platinum blonde with soft golden undertones. Keep the hairstyle, individual strands, shine and natural hairline transitions. Keep the face and everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/portrait-platinum-blonde-hair?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Hair, Hair Color, Blonde, Portrait

### Natural Skin Retouch

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/portrait-skin-texture-refinement-before.webp" width="260" alt="Natural Skin Retouch · Before"></td><td><img src="images/portrait-skin-texture-refinement-after.webp" width="260" alt="Natural Skin Retouch · After"></td></tr></table>

Reduces redness and small blemishes on the face while keeping real pores, freckles and natural variation in skin tone, so the result does not look plastic. Face shape, features, expression and lighting stay the same. It suits portraits, headshots and profile photos that need a light retouch rather than a heavy beauty filter.

```text
Retouch the skin on the face: reduce temporary redness and small blemishes while keeping the real pore texture, freckles and natural skin tone variation. No plastic smoothing. Keep the face shape, features, expression and lighting exactly as they are.
```

[Open in YepShot →](https://yepshot.com/explore/portrait-skin-texture-refinement?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Retouch · Tags: Skin, Retouch, Beauty, Portrait

### Casual Photo to Business Headshot

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/portrait-business-headshot-before.webp" width="260" alt="Casual Photo to Business Headshot · Before"></td><td><img src="images/portrait-business-headshot-after.webp" width="260" alt="Casual Photo to Business Headshot · After"></td></tr></table>

Turns a casual photo into a professional headshot: a mid-gray studio backdrop, a navy blazer over a white shirt, and soft front light. Face, features, hairstyle and expression are kept the same. Use it for LinkedIn, company pages or speaker bios. A photo where you face the camera in even light works best.

```text
Turn this into a professional business headshot. Keep the person's face, features, hairstyle and expression exactly the same. Replace the background with a smooth mid-gray studio backdrop, dress the person in a navy blazer over a white shirt, and use soft key light from the front left. Sharp focus on the eyes.
```

[Open in YepShot →](https://yepshot.com/explore/portrait-business-headshot?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Headshot, LinkedIn, Business, Portrait

### ID Photo with White Background

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/portrait-id-photo-before.webp" width="260" alt="ID Photo with White Background · Before"></td><td><img src="images/portrait-id-photo-after.webp" width="260" alt="ID Photo with White Background · After"></td></tr></table>

Produces a passport-style ID photo: a front-facing head-and-shoulders crop on a plain white background, with even lighting and no shadows. Face, features, hairstyle and skin tone are kept as they are. Size and background rules differ by country and document, so check the official requirements and crop to the exact dimensions before you submit it.

```text
Turn this into a passport-style ID photo: a front-facing head-and-shoulders crop on a plain white background, with even lighting and no shadows on the face or background. Keep the person's face, features, hairstyle and skin tone exactly the same.
```

[Open in YepShot →](https://yepshot.com/explore/portrait-id-photo?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: ID Photo, Passport, White Background, Portrait

### Remove People from the Background 🖌

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/portrait-remove-photobomber-before.webp" width="260" alt="Remove People from the Background · Before"></td><td><img src="images/portrait-remove-photobomber-after.webp" width="260" alt="Remove People from the Background · After"></td></tr></table>

Removes strangers and passers-by from the background of a photo and rebuilds the scenery behind them, with no blur, smears or leftover shadows. Brush over the people you want gone before you run it. The main subject and everything outside the marked area stay as they are, which makes it handy for travel photos.

```text
Remove the people in the marked area and rebuild the background behind them so the scenery, lighting and perspective continue naturally, with no blur, smears or leftover shadows. Keep the main subject and everything outside the marked area unchanged.
```

[Open in YepShot →](https://yepshot.com/explore/portrait-remove-photobomber?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Remove · Tags: Photobomber, Tourists, Erase, Travel

## Campaigns

### Christmas Pine and Warm Bokeh

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/seasonal-christmas-pine-bokeh-before.webp" width="260" alt="Christmas Pine and Warm Bokeh · Before"></td><td><img src="images/seasonal-christmas-pine-bokeh-after.webp" width="260" alt="Christmas Pine and Warm Bokeh · After"></td></tr></table>

Sets the product on dark rustic wood with fresh pine branches, frosted pinecones and warm bokeh from fairy lights. It is a ready-made holiday scene for Christmas campaigns, gift guides and seasonal banners, without building a set. The product itself stays unchanged, so one product photo can be reused for every season.

```text
Keep the product unchanged. Place it on dark rustic wood surrounded by fresh pine branches and a few frosted pinecones, with golden fairy lights forming warm, round bokeh in the background. Cozy, premium Christmas campaign look.
```

[Open in YepShot →](https://yepshot.com/explore/seasonal-christmas-pine-bokeh?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Christmas, Holiday, Winter, Bokeh

### Summer Pool Water and Caustics

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/seasonal-summer-pool-water-ripples-before.webp" width="260" alt="Summer Pool Water and Caustics · Before"></td><td><img src="images/seasonal-summer-pool-water-ripples-after.webp" width="260" alt="Summer Pool Water and Caustics · After"></td></tr></table>

Stands the product in clear turquoise pool water with sunlight caustics across it and ripples around its base. It suits drinks, sunscreen, swimwear accessories and anything sold with a summer angle. Waterproof products look most natural here; for items that should never get wet, a dry poolside scene may be the safer choice.

```text
Keep the product unchanged. Place it standing in shallow, crystal-clear turquoise pool water, with dancing sunlight caustics across the product and gentle ripples around its base. Bright tropical sunlight, refreshing summer campaign look.
```

[Open in YepShot →](https://yepshot.com/explore/seasonal-summer-pool-water-ripples?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Summer, Water, Caustics, Refreshing

### Black Friday Black-and-Gold Pedestal

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/seasonal-black-friday-gold-geometry-before.webp" width="260" alt="Black Friday Black-and-Gold Pedestal · Before"></td><td><img src="images/seasonal-black-friday-gold-geometry-after.webp" width="260" alt="Black Friday Black-and-Gold Pedestal · After"></td></tr></table>

Puts the product on a matte black hexagonal pedestal with brass edges, dark satin behind it and a spotlight from above. The prompt tells the model not to add text, so you can lay your own Black Friday copy and discount on top in your design tool. It suits premium products that should look discounted, not cheap.

```text
Keep the product unchanged. Place it on a matte black hexagonal pedestal with polished brass edges, with flowing dark satin fabric in the background and a dramatic spotlight from above. Luxurious Black Friday campaign look, premium commercial photography. Do not add any text.
```

[Open in YepShot →](https://yepshot.com/explore/seasonal-black-friday-gold-geometry?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Black Friday, Gold, Luxury, Promo

### Turn a Product Photo into a Sale Poster

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/campaign-sale-poster-text-before.webp" width="260" alt="Turn a Product Photo into a Sale Poster · Before"></td><td><img src="images/campaign-sale-poster-text-after.webp" width="260" alt="Turn a Product Photo into a Sale Poster · After"></td></tr></table>

Turns a product photo into a sale poster with "SUMMER SALE" at the top, "50% OFF" under the product and a coral background with simple shapes. Change the two quoted texts to your own offer and keep them short, since short headlines are rendered more reliably. Proofread every letter before you publish.

```text
Turn this product photo into a sale poster. Keep the product unchanged and centered. Add the headline "SUMMER SALE" at the top and "50% OFF" below the product in a bold, clean sans-serif, on a bright coral background with simple geometric shapes. Spell the text exactly as given.
```

[Open in YepShot →](https://yepshot.com/explore/campaign-sale-poster-text?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Poster, Sale, Typography, Promo

### Update the Discount on a Promo Graphic

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/text-promo-discount-update-before.webp" width="260" alt="Update the Discount on a Promo Graphic · Before"></td><td><img src="images/text-promo-discount-update-after.webp" width="260" alt="Update the Discount on a Promo Graphic · After"></td></tr></table>

Changes the discount on an existing sale graphic, so last month's banner can be reused without opening the design file. In our test only the digits changed, from 20% to 35%, in the same bold type inside the same badge; the headline, the button and the product were left alone. Put your own number in the quotes and proofread the result before you post it.

```text
Change the discount to "35% OFF" wherever it appears. Keep the typeface, colors, layout, product photo and every other word exactly as they are.
```

[Open in YepShot →](https://yepshot.com/explore/text-promo-discount-update?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Modify · Tags: Promo, Discount, Banner, Text

### Lunar New Year Red and Gold

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/seasonal-lunar-new-year-before.webp" width="260" alt="Lunar New Year Red and Gold · Before"></td><td><img src="images/seasonal-lunar-new-year-after.webp" width="260" alt="Lunar New Year Red and Gold · After"></td></tr></table>

Sets the product on a red lacquer tray with plum blossoms, small gold ornaments and glowing paper lanterns behind it. Use it for Lunar New Year promotions, gift boxes and festive social posts, especially for shoppers in Chinese-speaking markets. Red products can blend into the background; light, gold or metallic products stand out most.

```text
Keep the product unchanged. Place it on a red lacquer tray with plum blossom branches and small gold ornaments around it, and blurred red paper lanterns glowing in the background. Warm, festive Lunar New Year campaign look with rich red and gold tones.
```

[Open in YepShot →](https://yepshot.com/explore/seasonal-lunar-new-year?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Background · Tags: Lunar New Year, Festive, Red, Gold

## Restoration

### Restore a Faded Old Photo

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/restore-vintage-photo-reconstruction-before.webp" width="260" alt="Restore a Faded Old Photo · Before"></td><td><img src="images/restore-vintage-photo-reconstruction-after.webp" width="260" alt="Restore a Faded Old Photo · After"></td></tr></table>

Removes the yellow cast, dust, scratches and fold creases from an old photo and brings back detail in faces and eyes. People's features, expressions, clothing and the original composition are kept. Scan or photograph the print flat and in even light first, because glare on a glossy print is hard to recover from.

```text
Restore this old photograph: remove the yellow age cast, dust spots, scratches and fold creases, and bring back clear, natural detail in the faces and eyes. Keep the people's features, expressions, clothing and the original composition unchanged. Clean archival quality with natural contrast.
```

[Open in YepShot →](https://yepshot.com/explore/restore-vintage-photo-reconstruction?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Retouch · Tags: Old Photo, Restoration, Scratches, Vintage

### Colorize a Black-and-White Photo

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/restore-colorize-bw-before.webp" width="260" alt="Colorize a Black-and-White Photo · Before"></td><td><img src="images/restore-colorize-bw-after.webp" width="260" alt="Colorize a Black-and-White Photo · After"></td></tr></table>

Adds natural, period-appropriate color to a black-and-white photo: realistic skin tones, clothing and surroundings, without the flat tint of a filter. Detail, grain and composition are left as they are; only color is added. The colors are the model's best guess, so if you know a dress or car was a specific color, write it into the prompt.

```text
Colorize this black-and-white photo with natural, period-accurate colors: realistic skin tones, clothing and surroundings. Keep every detail, the grain structure and the composition exactly as they are; only add color. Avoid oversaturated or uniform tints.
```

[Open in YepShot →](https://yepshot.com/explore/restore-colorize-bw?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Retouch · Tags: Colorize, Black and White, Vintage, Family

### Fix Blur and Noise

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/restore-deblur-sharpen-before.webp" width="260" alt="Fix Blur and Noise · Before"></td><td><img src="images/restore-deblur-sharpen-after.webp" width="260" alt="Fix Blur and Noise · After"></td></tr></table>

Sharpens a blurry, noisy photo by removing motion blur and grain and recovering crisp edges and fine texture. The prompt tells the model not to add new details or change shapes, so faces and objects stay true to the original. It works best on mild blur; a badly out-of-focus shot can only be improved so far.

```text
Sharpen this blurry, noisy photo: remove motion blur and grain, and recover crisp edges and fine texture. Keep the subject, colors, lighting and composition exactly the same. Do not add new details or change any shapes.
```

[Open in YepShot →](https://yepshot.com/explore/restore-deblur-sharpen?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Retouch · Tags: Deblur, Denoise, Sharpen, Pet

### Brighten an Underexposed Photo

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/restore-low-light-fix-before.webp" width="260" alt="Brighten an Underexposed Photo · Before"></td><td><img src="images/restore-low-light-fix-after.webp" width="260" alt="Brighten an Underexposed Photo · After"></td></tr></table>

Brightens an underexposed photo, such as an indoor dinner or a night gathering: it raises exposure, recovers shadow detail, neutralizes the color cast and reduces noise. The scene, people and composition stay the same, and the light still looks natural. The prompt mentions faces and a table, so edit that part to describe what is in your photo.

```text
Fix this underexposed photo: raise the exposure so the faces and the table are clearly visible, recover detail in the shadows, neutralize the color cast and reduce noise. Keep the scene, people and composition exactly the same, and keep the light looking natural.
```

[Open in YepShot →](https://yepshot.com/explore/restore-low-light-fix?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Retouch · Tags: Low Light, Exposure, Color Cast, Denoise

## Creative

### Turn Your Pet into a Collectible Figure

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/creative-collectible-figure-before.webp" width="260" alt="Turn Your Pet into a Collectible Figure · Before"></td><td><img src="images/creative-collectible-figure-after.webp" width="260" alt="Turn Your Pet into a Collectible Figure · After"></td></tr></table>

Turns a pet photo into a 1/7 scale collectible figure on a clear acrylic base, with a matching toy box behind it on a desk. The animal's markings, colors and pose are kept, so it still looks like your pet. A clear, well-lit photo of the whole animal gives the best figure, and it works for other animals too.

```text
Turn the animal in this photo into a 1/7 scale collectible figure standing on a round clear acrylic base on a computer desk. Behind it, place a toy packaging box printed with the same character. Keep the animal's markings, colors and pose. Realistic studio product photo with soft light.
```

[Open in YepShot →](https://yepshot.com/explore/creative-collectible-figure?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Restyle · Tags: Figurine, Toy, Pet, Nano Banana

### Photo to Watercolor Illustration

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/creative-watercolor-illustration-before.webp" width="260" alt="Photo to Watercolor Illustration · Before"></td><td><img src="images/creative-watercolor-illustration-after.webp" width="260" alt="Photo to Watercolor Illustration · After"></td></tr></table>

Redraws a photo as a loose watercolor on textured paper, with soft washes, visible brush strokes and fine ink outlines, while keeping the composition recognizable. It suits travel photos, buildings and street scenes, and makes good cards, prints or blog headers. Photos with a clear main subject and a simple background give the cleanest painting.

```text
Redraw this photo as a loose watercolor illustration on textured paper, with soft color washes, visible brush strokes and fine ink outlines. Keep the composition, buildings and main shapes recognizable. Light, airy palette with white paper showing through.
```

[Open in YepShot →](https://yepshot.com/explore/creative-watercolor-illustration?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Restyle · Tags: Watercolor, Illustration, Travel, Art

### Photo to 3D Clay Character

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/creative-3d-clay-before.webp" width="260" alt="Photo to 3D Clay Character · Before"></td><td><img src="images/creative-3d-clay-after.webp" width="260" alt="Photo to 3D Clay Character · After"></td></tr></table>

Restyles a photo as a handmade clay stop-motion scene, with soft rounded shapes, fingerprint texture and a miniature set. The subject's pose, colors and key features stay recognizable. It works for people, pets and products, and makes a playful profile picture, sticker or social post that still looks like the original subject.

```text
Transform this photo into a handmade 3D clay animation style, with soft rounded shapes, visible fingerprint texture in the clay and a miniature set. Keep the subject's pose, colors and key features recognizable. Warm soft lighting, playful stop-motion look.
```

[Open in YepShot →](https://yepshot.com/explore/creative-3d-clay?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Restyle · Tags: Clay, 3D, Stop Motion, Cute

### Sketch to Product Render

<table><tr><th>Before</th><th>After</th></tr><tr><td><img src="images/creative-sketch-to-render-before.webp" width="260" alt="Sketch to Product Render · Before"></td><td><img src="images/creative-sketch-to-render-after.webp" width="260" alt="Sketch to Product Render · After"></td></tr></table>

Turns a pencil sketch into a photorealistic product render that follows the sketch's shape and proportions. The example prompt describes a sneaker in white leather, gray suede and rubber, so rewrite the materials line for your own design. Designers use it to show a concept to a client or factory before any sample exists.

```text
Turn this pencil sketch into a photorealistic product render. Follow the sketch's shape, proportions and details exactly. Use realistic materials: white leather upper, gray suede panels and a rubber sole, on a light gray studio background with soft shadows.
```

[Open in YepShot →](https://yepshot.com/explore/creative-sketch-to-render?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Restyle · Tags: Sketch, Render, Product Design, Sneaker

### Borrow the Style of a Reference Image 🖼

<table><tr><th>Before</th><th>Reference (IMG_2)</th><th>After</th></tr><tr><td><img src="images/compose-style-transfer-before.webp" width="260" alt="Borrow the Style of a Reference Image · Before"></td><td><img src="images/compose-style-transfer-reference.webp" width="260" alt="Borrow the Style of a Reference Image · Reference (IMG_2)"></td><td><img src="images/compose-style-transfer-after.webp" width="260" alt="Borrow the Style of a Reference Image · After"></td></tr></table>

Uses two images: IMG_1 is the picture to redraw, IMG_2 is the style reference. The result keeps IMG_1's composition, subject and proportions and takes the color palette, texture and brushwork from IMG_2, without copying its objects. Use it to match a brand's illustration style or to give your photo the look of a painting.

```text
Redraw IMG_1 in the visual style of IMG_2: use its color palette, texture and brushwork. Keep IMG_1's composition, subject and proportions intact. Do not copy any objects from IMG_2.
```

[Open in YepShot →](https://yepshot.com/explore/compose-style-transfer?utm_source=github&utm_medium=awesome-nano-banana-prompts) · Combine · Tags: Style Transfer, Reference, Art, Print

## Using the prompts with the Gemini API

Send the photo and the prompt in one request. The model ID is `gemini-nano-banana-2.1`.

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

For 🖌 prompts, add a text part `Apply the edit only inside the white region of the following mask.` followed by a black-and-white mask image, where white marks the area to edit. That is how the examples here were made.

## Contributing

Found a prompt that works better, or one that fails on your photos? Open an issue with the prompt and a before-and-after.

## License

Prompts, text and images are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). If you reuse them, credit "YepShot" with a link to https://yepshot.com.

---

Maintained by [YepShot](https://yepshot.com/?utm_source=github&utm_medium=awesome-nano-banana-prompts), an AI photo editor that runs these prompts with a brush mask and 1K to 4K output. Not affiliated with Google; Nano Banana is Google's name for its Gemini image models.
