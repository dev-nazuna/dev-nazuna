<div align="center">

<img src="assets/banner.svg" width="100%" alt="Nanakusa Nazuna — Nazuna Nanakusa. Yofukashi no Uta, Call of the Night. A shepherd's purse sprig drawn as a botanical specimen beside an empty night street with a lit vending machine and a crescent moon." />

<img src="assets/type.svg?v=4" width="72%" alt="i build websites, apps and systems" />

<img src="assets/divider.svg?v=4" width="100%" alt="" />

## 自己紹介 &nbsp;<sub>who am i</sub>

<sub>

web developer & designer

part-time vampire.

</sub>

<img src="assets/train.svg" width="28%" alt="Pixel art: a lit night train crossing an elevated track above a sleeping city, under a crescent moon and a street lamp." />

<img src="assets/divider.svg?v=4" width="100%" alt="" />

## 道具箱 &nbsp;<sub>toolbox</sub>

<img src="assets/toolbox.svg?v=1" width="80%" alt="Languages: HTML, CSS, JavaScript, TypeScript, PHP. Tools: React, Tailwind, MySQL, Git, Figma." />

<img src="assets/divider.svg?v=4" width="100%" alt="" />

## つくったもの &nbsp;<sub>selected work</sub>

<a href="https://bloomautolab.ca"><img src="assets/bloom.svg" width="100%" alt="Bloom Auto Lab: the full blossom mark, petals in pale lavender over deep aubergine, on a lit plate with fine corner registration marks." /></a>

<sub>

**Bloom Auto Lab** ・ [bloomautolab.ca](https://bloomautolab.ca)

full website for an auto detailing company.

public site, quotes & booking flow, admin panel.

PHP 8.2, MariaDB, JS.

</sub>

<img src="assets/divider.svg?v=4" width="100%" alt="" />

## れんらく &nbsp;<sub>say hello</sub>

<a href="https://github.com/dev-nazuna"><img src="https://skillicons.dev/icons?i=github&theme=dark" width="9%" alt="GitHub" /></a>

<!-- drop the comment markers once these exist. keep them on one line each.
<a href="mailto:YOUR@EMAIL.COM"><img src="https://skillicons.dev/icons?i=gmail&theme=dark" width="9%" alt="Email" /></a>
<a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://skillicons.dev/icons?i=linkedin&theme=dark" width="9%" alt="LinkedIn" /></a>
-->

<img src="assets/divider.svg?v=4" width="100%" alt="" />

<sub>おやすみ。</sub>

</div>

<!-- notes to self

     · NEVER write "front end" or "back end" here. it reads as a job-board
       phrase, not as a person. say what the work actually is instead.

     · EVERY <sub> PARAGRAPH MUST FIT ON ONE LINE AT PHONE WIDTH — about 40
       characters. github's css sets line-height:0 on sub, so a paragraph that
       wraps renders its second line directly on top of its first. that is why
       the copy here is a stack of short statements. the readme column is 293px
       on a 375px phone; sub renders at ~13px.

     · keep the copy flat and factual. no aphorisms, no "x, not y" constructions,
       no claims about the implementation being pure. state the role, the stack,
       and what the thing is. anything that sounds quotable is a rewrite.

     · the whole page is one <div align="center">. divider.svg is symmetric —
       rule fading out at the middle, moon centred, four stars either side —
       so it only reads correctly in a centred column.

     · type.svg's canvas is sized to its string (450x52 for 34 glyphs at
       textLength 418). that is what makes it centre. a wide canvas with the
       text at x=16 renders left-of-centre no matter what the markdown says.
       change the string and textLength, the canvas width, both keyframe end
       values and steps() all have to move together.

     · toolbox.svg is a five-column grid on a 700x236 canvas: column centres at
       94/222/350/478/606, marks drawn on the standard 24px logo grid and scaled
       1.4166667 to 34px. an eleventh tool means re-deriving the centres and the
       canvas width together — do not squeeze one into the existing spacing.
       the marks are monochrome because the label under each one identifies it;
       the palette is the same two purples the rest of the page uses.

     · NEVER put a % width on a floated image. github wraps every readme image
       in an <a>, which has zero width, so a float's percentage resolves against
       a containing block that shifts with the layout.

     · CAMO CACHES BY URL. editing an svg in place does NOT update what the
       README shows. bump the ?v= number whenever artwork changes.

     · raw.githubusercontent.com ALSO caches, for about five minutes. verify a
       commit through the API (/repos/.../contents/...?ref=main), never by
       re-fetching raw — a stale copy looks exactly like a reverted commit.

     · the moon is cut with a <mask>, not fill-rule="evenodd". evenodd gives
       the SYMMETRIC DIFFERENCE of the two circles, so when the subtracting
       circle is the larger one it lights the wrong limb.

     · GitHub's sanitiser DELETES <small> outright — it renders at standard
       size with no warning. <sub> is the only small-text tag that survives.

     · every svg animates behind a prefers-reduced-motion guard. keep it.
-->
