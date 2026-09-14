# Два ролика для DARKHOST: 2D бренд-ролик и ролик CRM из трёх генераций

**Кейс 5 · шаг 2 — Четыре видеопромта, каждый отдельным блоком**

- **Ролики:** [https://disk.yandex.ru/d/mqkh8iDKnGrJcw](https://disk.yandex.ru/d/mqkh8iDKnGrJcw) — 2D бренд-ролик DARKHOST и склейка трёх генераций для DarkHost CRM
- **Модели:** Gemini Omni Flash 1.1, Seedance 2.5 · Higgsfield

Содержание:

1. 2D бренд-ролик DARKHOST, 10 секунд
2. Ролик DarkHost CRM, акт 1: хаос в приёмке одним дублем
3. Ролик DarkHost CRM, акт 2: волна порядка и переход в CRM
4. Ролик DarkHost CRM, вставка: одна карточка заказа проходит всю систему

---

## 1. 2D бренд-ролик DARKHOST, 10 секунд

- **Задача:** За 10 секунд показать один связный процесс: заявка → забор ковра → чистка → доставка
- **Инструмент:** Higgsfield, референс по движению — ролик HiggsFit
- **Модель:** Gemini Omni Flash 1.1 · 10 секунд · 16:9 · 1080p

Модель хорошо держит стиль и плохо держит время. Поэтому в промте нет слов «динамично» и «современно»: есть точный хронометраж с секундами, фиксированная палитра в hex, один и тот же номер заказа №1248 через все кадры и список того, что появляется на экране текстом. Всё, что не перечислено в разделе с видимым текстом, модель дорисовывать не должна — иначе на финальном кадре появляется псевдокириллица рядом с логотипом.

### Промт

```text
DARKHOST ONLINE — 10-SECOND EXPRESSIVE 2D MOTION FILM

FORMAT
16:9 · 1920×1080 · 30 fps
Exact duration: 10 seconds.

REFERENCE DIRECTION
Use the supplied HiggsFit video as the primary reference for animation
rhythm, character movement, composition, kinetic typography and scene
transitions.
Translate its motion language into the DARKHOST brand:
chunky illustrated characters,
oversized illustrated objects,
expressive anticipation and follow-through,
springy entrances,
short readable actions,
bold typography,
graphic marker highlights,
decisive cuts between colored scenes.
Use DARKHOST branding, characters and story throughout.

CORE MESSAGE
One request becomes one connected process and one completed order.
Follow the same beige carpet and the same order №1248 throughout:
request → collection → cleaning → delivery.
DARKHOST is visibly present through a recurring order card and
changing status.

VISUAL STYLE
Entirely flat 2D illustration.
Solid color fills.
Rounded, slightly organic silhouettes.
Small heads and chunky rounded limbs.
Minimal faces.
Simple clothing.
Large, clear props.
Sparse environments with generous empty space.
Use a bold rounded sans-serif for Russian text.
Render all text accurately and keep letterforms stable.
Devices are illustrated props with a slight graphic tilt and a flat
colored edge.
Their depth is drawn using simple shapes.
No photography, realistic rendering, 3D lighting, gradients, grain
or textures.

BRAND PALETTE
Off-white: #F7FAFB
Dark teal: #05374A
Secondary teal: #023D53
Bright cyan: #55C9E8
Success green: #50B067
Blue-gray: #DDE7EA
Carpet beige: #E8DDD0
Stain coral: #EF766C
Use pale tints of cyan and green for scene backgrounds.
Create contrast with large cyan and teal foreground shapes.
Keep the final frame off-white.
Use natural skin and hair colors for characters.
Do not introduce purple or neon pink.

CHARACTERS AND CONTINUITY
Mother: dark shoulder-length hair, off-white top, beige trousers.
Courier: off-white shirt, dark teal trousers, cyan accent.
Cleaner: simple teal workwear.
Keep each character recognizable across shots.
Allow controlled temporary squash and stretch during movement.
Preserve clothing, face and body design after each action settles.
The carpet is always the same beige rounded rectangle.
A coral stain identifies it before cleaning.
After cleaning, preserve its color, proportions and design.
The order card always uses:
№1248,
a small carpet illustration,
one status pill,
a small DARKHOST brand label.

ANIMATION LANGUAGE
Build each main action in three phases:
anticipation → decisive movement → soft settling.
Before lifting the carpet, the courier bends slightly.
During the lift, the arms and torso extend.
After the lift, the carpet end follows with a small delay.
Before pushing the cleaning machine, the cleaner leans back slightly.
Then the body follows one broad forward push.
Hands, body and machine settle at slightly different times.
Use:
soft limb bending,
controlled squash and stretch,
short rotational entrances,
small overshoots,
delayed secondary motion,
brief graphic smears on fast limbs or props.
Keep faces, text and logos clear during movement.
Give every action a readable finishing pose.

UI RESPONSE
Show only oversized, simplified elements:
one button,
one order card,
one status pill,
one checkmark.
A button press has a visible physical response:
finger approaches,
button compresses,
finger releases,
button rebounds once,
confirmation appears.
Keep the typography readable while the surrounding button shape reacts.
Do not show dashboards, tables, sidebars, menus or detailed app screens.

TYPOGRAPHY
Introduce short headline phrases word by word.
Use a quick upward movement with gentle settling.
Draw a broad cyan marker-style highlight behind selected words.
The highlight has a slightly irregular silhouette and a solid fill.
It does not cover the letters.
Allow the completed phrase to remain still long enough to read.
Use only the text specified in the timeline.

TRANSITIONS
Use the reference's direct editorial cuts between distinct
compositions and background colors.
Maintain continuity through:
the same order number,
the same carpet,
consistent screen direction,
a recurring status card.
Within shots, use scale, rotation, sliding and elastic deformation.
Use one small shape transformation for a confirmation circle becoming
a status pill.
Keep most objects recognizable throughout their movement.
Do not force every object to transform into another object.
Avoid repeated dissolves, spinning scene transitions and continuous
zooming.

CAMERA AND COMPOSITION
Keep the viewpoint fixed within each shot.
Create energy through the animation of the artwork.
Use one dominant action per shot.
Place supporting objects around it without competing for attention.
Keep the recurring order card near the upper-right area after the
opening shot.
Use left-to-right movement for collection, cleaning and delivery.
The final composition should be spacious and stable.

EXACT TIMELINE

0.00–2.20 — CREATE THE REQUEST
Off-white background.
The mother stands beside a beige carpet with an existing coral stain.
A small sofa silhouette suggests a home.
An oversized illustrated smartphone rises beside her with a slight
rotation and soft overshoot.
Its screen contains only:
a small stained-carpet illustration,
one large cyan button: «Создать заявку».
Above the scene, the phrase appears word by word:
«Чистка — в один клик».
A cyan marker highlight draws behind «в один клик».
The mother makes one clear tap.
The button compresses and rebounds.
A green confirmation circle pops up, then widens into a simple
status pill.
The order card appears: «№1248», «НОВАЯ».
Hold the result briefly.
Keep the carpet stain visible.
At 2.20 seconds, cut directly to the collection scene.

2.20–3.80 — COURIER COLLECTION
Pale cyan background.
Minimal doorway.
Mother on the left, courier on the right.
The same carpet is already rolled between them.
The courier bends slightly, takes the carpet and lifts it into
a comfortable carrying position.
Make the movement broad and springy.
The loose carpet edge follows the lift with a small delayed bounce.
The order card remains in the upper-right area: «№1248».
As the lift finishes, its status updates to: «ЗАБРАНО».
The status pill enters with a small vertical overshoot and settles.
Hold the courier's final pose long enough to understand the collection.
No tablet, signature or additional button.
At 3.80 seconds, cut directly to the workshop.

3.80–6.00 — CLEANING
Warm off-white background with a simple cyan workshop accent.
Only one cleaner, one cleaning machine and one background rack.
The same rolled carpet unrolls from left to right.
Animate the curled edge opening and gently flattening, inspired by
the exercise mat in the reference.
The order card reads: «№1248», «В РАБОТЕ».
The cleaner makes one broad, continuous pass across the carpet.
Use expressive body weight and soft bending arms.
The coral stain disappears exactly where the machine passes.
A few cyan and white foam circles trail behind it.
The bubbles rise and shrink with staggered timing.
The machine reaches the end.
The clean carpet remains visible.
The cleaner settles into a finishing pose.
The status updates to: «ГОТОВ».
A small green check appears with one controlled bounce.
At 6.00 seconds, cut directly to the customer's doorway.

6.00–8.20 — DELIVERY AND COMPLETION
Pale green background.
The courier hands the clean rolled carpet to the mother.
Use one clear transfer with a small body dip and follow-through.
The mother receives it and settles into a relaxed pose.
Beside them, show one large floating cyan button: «Доставлено».
The courier taps it once.
The button compresses and rebounds.
A green check grows into view.
The recurring order card becomes slightly larger: «№1248»,
«ВЫПОЛНЕН».
Use a brief burst of a few flat circles and triangles around the check.
The particles spread, slow down and disappear.
Keep them clear of the text.
Hold the completed order visibly before the final cut.

8.20–10.00 — DARKHOST BRAND FRAME
Cut to a clean off-white background.
The supplied official DARKHOST logo enters with a short upward
movement and subtle settling.
Below it, reveal: «Весь процесс. В одной системе.»
Complete the composition by 8.70 seconds.
Hold the logo and message still from 8.70 to 10.00.
Use the supplied logo artwork unchanged.
Preserve its exact symbol, lettering, colors and proportions.
Animate the logo as a complete graphic.
No additional text, particles or scene changes during the final hold.

PACING
Make the film energetic through expressive movement inside each shot.
Entrances are quick.
Main actions are broad and easy to follow.
Completed actions receive a short visual pause.
Use staggered timing for secondary details.
Do not introduce multiple new actions simultaneously.
Do not add extra story beats.
If a shot becomes crowded, remove background detail or secondary
animation.
Preserve the main action, readable status and final brand hold.

VISIBLE TEXT ONLY
«Чистка — в один клик»
«Создать заявку»
«DARKHOST»
«№1248»
«НОВАЯ»
«ЗАБРАНО»
«В РАБОТЕ»
«ГОТОВ»
«Доставлено»
«ВЫПОЛНЕН»
«Весь процесс. В одной системе.»

FINAL CREATIVE PRIORITY
Match the reference's expressive character animation, oversized props,
kinetic typography, graphic color changes and satisfying action
responses.
The viewer should immediately understand:
the customer creates a request,
the carpet is collected and cleaned,
the completed order returns to the customer,
DARKHOST connects every stage.
```

---

## 2. Ролик DarkHost CRM, акт 1: хаос в приёмке одним дублем

- **Модель:** Seedance 2.5 · 15 секунд · 16:9 · 1080p · звук
- **Референсы:** @Image1 фото приёмки, @Image2 героиня, @Image3 руководитель, @Image4 ковёр
- **Задача:** Показать «до»: приёмка химчистки тонет в бумагах, заказ клиента потерян

Seedance 2.5 тянет дубль до 30 секунд, но на длинных дублях начинают плыть лица, поэтому здесь 15. Весь акт — один непрерывный пролёт камеры, таймлайн расписан по секундам. Любой текст в кадре запрещён: русские буквы Seedance пишет криво, надписи появляются только в третьей генерации. Последний кадр — спокойный крупный план героини. С него начинается второй акт.

### Промт

```text
SINGLE CONTINUOUS ONE-TAKE SHOT, NO CUTS, 15 seconds, 16:9, premium stylized 3D animated feature film style, soft rounded shapes, expressive large eyes, smooth stylized skin with subtle subsurface scattering, soft fabric and paper materials, high quality 3D render, cinematic depth of field, film-like motion blur, rich volumetric light, tense energetic commercial pacing.



LOCATION: the dry cleaning and carpet cleaning reception from @Image1, keep its exact layout and design: the curved deep petrol blue reception counter with a white top, the monitor on the left side of the counter, the tablet on the right side, the white wall behind the counter with the circular logo sign of three petrol blue arrows and a green four-pointed star, the petrol blue wall frames and the light wood floor, the large window on the left with plants. But the room is now in total CHAOS: tall messy stacks of paper receipts, order forms and cardboard folders piled on the counter, colorful yellow and pink sticky notes stuck all around the edges of the monitor, crumpled paper balls and loose sheets scattered across the floor, an old beige landline phone with a tangled cord, a smartphone, and a half-empty coffee cup on the counter, the neat carpet rack on the right is overloaded and collapsed into a messy heap of rolled carpets in warm red, beige and brown tones leaning against the wall and lying on the floor, each with a random handwritten paper tag hanging on a string, the teal green geometric carpet from @Image4 with sage green diamond pattern and cream stripes lies half unrolled and trampled on the floor under the other carpets. The logo sign on the wall is switched off, unlit and dull. The monitor glows with a crowded bright spreadsheet grid of tiny cells without any readable text.



LIGHTING AND MOOD: warm dim yellowish tungsten light with a slight tired greenish tint, harsh overhead highlights, heavy soft shadows, dust particles floating in the light beams, stressful overwhelmed atmosphere, slightly desaturated warm color grade.



CHARACTERS:

The young woman from @Image2 — the reception administrator. Keep her face, eyes, hairstyle, body proportions and uniform exactly identical to @Image2. In this scene she is exhausted and stressed: several strands of hair have fallen out of her bun, tired eyes, furrowed brows, a pen tucked behind her ear, her uniform shirt slightly wrinkled with unevenly rolled sleeves.

The man from @Image3 — the business owner. Keep his face, beard, hairstyle and outfit exactly identical to @Image3. In this scene he is worried and impatient.



ACTION AND CAMERA TIMELINE:



0.0–3.0s — EXTREME MACRO OPENING: an ultra close-up of the smartphone lying face up on a messy pile of paper receipts on the counter, its screen glowing bright with an incoming call animation, the phone vibrating hard and slowly sliding across the paper, tiny sticky notes around it trembling from the vibration, shallow depth of field, in the blurry warm background the silhouette of the young woman from @Image2 is moving, the camera very slowly creeps closer to the phone creating tension.



3.0–6.0s — EXPLOSIVE PULL-BACK REVEAL: a sudden fast speed-ramped camera pull-back and rise, the camera flies backward and upward through a burst of paper sheets fluttering up into the air, passing between the flying papers, revealing the whole chaotic reception from @Image1, the exhausted young woman from @Image2 behind the counter quickly grabs the vibrating smartphone and presses it to her ear with her shoulder, while with both hands she frantically flips through a thick paper folder, glancing nervously at the glowing spreadsheet on the monitor.



6.0–10.0s — ORBIT AND OWNER ENTRANCE: the camera smoothly and swiftly orbits 180 degrees around the young woman from @Image2 at chest height, keeping her in the center of the frame, papers slipping off the counter and falling in slow motion around her, a sticky note peels off the monitor and flutters down, during the orbit the man from @Image3 enters the frame from the side walking fast, stops in front of the counter, spreads both arms wide in a frustrated questioning gesture and points at the messy carpet heap as if asking where the customer's order is, the young woman shrugs helplessly while still holding the phone to her ear.



10.0–13.0s — SEARCHING THE CARPETS: the young woman from @Image2 puts the phone down, rushes around the counter to the messy heap of rolled carpets and starts digging through it, pulling out wrong red and beige carpets, reading their paper tags and tossing them aside, the carpets roll and flop onto the floor, the camera follows her with energetic handheld movement at low height, in the foreground the teal green geometric carpet from @Image4 lies lost and unnoticed under the pile, the man from @Image3 stands behind her in soft focus holding his head with one hand.



13.0–15.0s — DOLLY ZOOM ENDING: the young woman from @Image2 stands up and turns toward the camera, a dramatic vertigo dolly zoom effect pushes in on her overwhelmed face while the chaotic room behind her stretches away, she closes her eyes and exhales in frustration, loose papers slowly drifting down around her face, the shot ends on a clean stable close-up of her tired face with the dull logo sign from @Image1 blurred in the background.



CONSISTENCY AND QUALITY RULES: faces, hairstyles and outfits of both characters stay identical to @Image2 and @Image3 throughout the entire shot from every angle, the room layout stays consistent with @Image1, the green carpet stays identical to @Image4, natural anatomy with correct hands and five fingers, smooth physically plausible motion of papers and carpets, no morphing, no flickering, no extra people, stable ending frame.



SOUND DESIGN (sound effects only, no voice): 0-3s loud rhythmic smartphone vibration buzzing against paper, a low tense ambient hum building up; 3-6s a sharp whoosh as the camera pulls back, a loud flutter of many paper sheets flying; 6-10s rustling pages being flipped fast, papers sliding and falling, quick footsteps of the man entering, a muffled old landline phone ringing in the background; 10-13s heavy soft thuds of rolled carpets flopping onto the floor, rustling paper tags; 13-15s a deep stretching whoosh of the dolly zoom, a tense low rumble rising, then a tired exhale.

STRICTLY AVOID: readable text, letters, numbers, words on screens, papers, tags or anywhere in the scene, subtitles, captions, watermarks, human speech, voices, talking, lip sync, dialogue, music, realistic live-action look, camera cuts, scene changes.
```

---

## 3. Ролик DarkHost CRM, акт 2: волна порядка и переход в CRM

- **Модель:** Seedance 2.5 · 13 секунд · 16:9 · 1080p · звук
- **Референсы:** First Frame — последний кадр акта 1; @Image1 чистая приёмка, @Image2 героиня, @Image3 руководитель, @Image4 ковёр, @Image5 логотип, @Image6–@Image9 скриншоты CRM: список заказов, карточка заказа, курьеры, мобильный дашборд
- **Задача:** Бесшовно продолжить акт 1 и превратить хаос в порядок, закончив белой вспышкой под CRM-вставку

Генерация стартует с последнего кадра первого акта, поэтому первый абзац промта описывает этот кадр до мелочей: карандаш за ухом, выбившиеся пряди, свет. В первом акте героиня получилась в бежевом свитере вместо формы, и дальше промт держит именно свитер, иначе на склейке будет скачок. Скриншоты CRM идут только как референс стиля: мелкий текст на панелях размыт, читаются лишь блоки, цвета и бейджи. Финал — белая вспышка, из которой начинается третья генерация.

### Промт

```text
SINGLE CONTINUOUS ONE-TAKE SHOT, NO CUTS, 13 seconds, 16:9, premium stylized 3D animated feature film style, soft rounded shapes, expressive large eyes, smooth stylized skin with subtle subsurface scattering, soft knit fabric texture, glossy clean materials, high quality 3D render, cinematic shallow depth of field, anamorphic lens feel, film-like motion blur, rich volumetric light, magical yet premium technology commercial mood. This shot is the magical transformation moment of a commercial: the world turns from chaos into perfect order.



SEAMLESS CONTINUITY WITH THE FIRST FRAME: the video starts exactly from the provided first frame and continues it without any jump: a centered close-up of the young woman from @Image2 with her eyes closed, exhaling tiredly, lips slightly parted, a yellow pencil tucked behind her ear, a few loose wavy strands of dark hair hanging beside her face, the circular logo from @Image5 softly glowing green behind her head, warm dim greenish-yellow light, floating dust particles and blurry drifting paper in the background. Match the framing, lighting, colors, hair and outfit of the first frame perfectly in the first moment.



CHARACTERS:

THE YOUNG WOMAN from @Image2 — the reception administrator and main hero. Keep her face, eyes, eyebrows, nose, lips, skin tone, hairstyle and body proportions exactly identical to @Image2 and to the first frame. Outfit exactly as in the first frame: a soft cream beige knit sweater with a crisp white shirt collar. At the start she is exhausted with loose hair strands and a pencil behind her ear; after the magic wave passes her, her hair smoothly tidies itself back into a neat low bun, the pencil dissolves into tiny green sparkles, her face becomes fresh, calm, confident and gently smiling.

THE MAN from @Image3 — the business owner. Keep his face, beard, hairstyle and outfit exactly identical to @Image3. In this shot he is calm, relaxed and satisfied.



LOCATION — BEFORE AND AFTER:

BEFORE (0–4s): the same dry cleaning and carpet cleaning reception in chaos: warm dim yellowish tungsten light with a tired greenish tint, messy stacks of paper receipts and folders on the counter, sticky notes stuck around the monitor, crumpled papers on the floor, a messy heap of rolled carpets in red, beige and brown tones with paper tags, the teal green geometric carpet from @Image4 lying lost under the heap.

AFTER (from 6s): the room becomes EXACTLY the clean reception from @Image1: the curved deep petrol blue reception counter with a white top, the monitor on the left side of the counter, the tablet on the right side, the white wall behind the counter with the brightly and beautifully backlit logo sign from @Image5, petrol blue wall frames, light wood floor, the large bright window on the left with green plants, the neat wooden rack on the right with rolled carpets wrapped in shiny transparent film with small green tags, bright soft cool white daylight, clean airy calm premium atmosphere.



INTERFACE PANELS: the floating holographic panels and all screens show clean modern CRM interface layouts matching the visual style, colors and block structure of @Image6, @Image7, @Image8 and @Image9: white and light grey cards, deep petrol blue headers, fresh green status badges and buttons, tidy tables, order cards, progress stages, simple charts and a small map. @Image6 style appears on the monitor, @Image7 style on the tablet and on one floating panel, @Image8 style on another floating panel, @Image9 style on the man's smartphone. Panels are semi-transparent frosted glass with soft glowing petrol blue edges and a gentle green rim light, floating smoothly in the air with slight parallax. Any small text on them is blurred, abstract and unreadable, only shapes, blocks, lines, icons and color badges are clearly visible.



ACTION, CAMERA, LIGHT AND VFX TIMELINE:



0.0–2.0s — TIME FREEZE: a static intimate close-up continuing from the first frame, the young woman from @Image2 finishes her tired exhale with closed eyes, a faint visible breath in the air, and at that exact moment the whole world freezes: the drifting papers in the blurry background stop mid-air, dust particles stop and hang still like tiny stars, a falling sticky note freezes in place, the camera very slowly pushes in by a few centimeters, complete stillness and silence, the color grade slightly desaturates and cools as if time has stopped.



2.0–4.0s — THE SPARK: behind her head the green four-pointed star of the logo from @Image5 suddenly flares with an intense bright fresh green light, a soft glowing lens flare and a gentle ring-shaped pulse of light expands from the star, the pulse washes over her face and lights her cheeks and eyes with a green-white rim light, she slowly opens her eyes, surprised and curious, her pupils reflecting the green sparkle, tiny green glowing particles begin to rise around her, the camera slowly racks focus between her eyes and the glowing star behind her.



4.0–7.0s — THE WAVE OF ORDER: the star releases a powerful but elegant spherical shockwave of white and fresh green light that expands outward through the whole room, the camera rapidly pulls back and rises in a smooth speed-ramped motion, revealing the entire reception as the wave passes through it. Everything the wave touches transforms in real time: the frozen floating paper sheets fold, flatten and morph into glowing semi-transparent floating CRM interface panels; the sticky notes on the monitor burst into swirls of tiny green sparks and vanish; the stacks of receipts on the counter dissolve into streams of light particles that fly into the monitor; the crumpled papers on the floor evaporate into glowing dust; the messy heap of carpets lifts into the air, each carpet neatly rolls itself up tightly, gets wrapped in shiny transparent film with a small green tag, and flies gracefully onto the wooden rack in perfect order; the teal green geometric carpet from @Image4 rolls up last and lands on the rack in the front center position; the warm dim yellow light sweeps away and is replaced by bright clean cool white daylight pouring through the big window; the logo sign on the wall lights up fully and beautifully; the woman's loose hair strands smoothly tidy back into a neat bun and the pencil behind her ear dissolves into green sparkles. By the end of this moment the room is exactly the clean reception from @Image1.



7.0–10.0s — CALM ORDER AND CRM: the camera smoothly glides into a graceful slow 120-degree orbit around the young woman from @Image2, who now stands behind the counter calm, confident and smiling warmly, three or four floating CRM interface panels hover around her at different depths in a beautiful arc, gently bobbing and catching the light. At about 7.5s she lifts her hand and lightly swipes one floating panel with her fingertips; the panel slides smoothly through the air and docks into the monitor, the monitor screen lights up with a clean CRM interface in the style of @Image6 and holds perfectly steady, flat and clearly visible facing the camera for about one second. At about 8.5s the man from @Image3 walks into the frame from the side with a relaxed confident posture, stops near the counter, raises his smartphone and looks at it; the screen shows a clean mobile CRM dashboard in the style of @Image9 with simple charts and green status badges, the phone screen is briefly shown clearly facing the camera and held steady; he looks up at the woman, nods approvingly and smiles; she smiles back.



10.0–13.0s — DIVE INTO THE SCREEN: the camera leaves the orbit and flies smoothly and confidently forward over the counter toward the tablet on the right side, the woman's hand gently taps the tablet screen, which lights up with a clean order card interface in the style of @Image7 with progress stages and a green status badge, the tablet is held steady and flat facing the camera for a moment at around 11s, then the camera accelerates and dives straight into the tablet screen, the glowing interface grows until it completely fills the frame, soft green light streaks rush past the lens, and the shot ends in a bright clean white flash filling the entire frame, ready for the next scene.



LIGHTING PROGRESSION: 0–2s warm dim yellow-green frozen light; 2–4s intense green spark light and rim light on her face; 4–7s sweeping white-green wave with volumetric light rays and particles; 7–13s bright clean cool white daylight with soft petrol blue and green accent glows from the logo, panels and screens; final frame pure bright white.



COLOR PALETTE: deep petrol blue #0A4F78, fresh green #52C872, clean white, soft light grey, light wood, the teal green carpet, the woman's cream beige sweater.



SOUND DESIGN (sound effects and music only, no voice): 0–2s the tired exhale, then every sound abruptly stops into a deep muffled silence with a faint high airy tone; 2–4s a crisp magical crystal chime as the star flares, followed by a soft rising shimmering swell; 4–7s a powerful deep cinematic whoosh and a satisfying bass drop as the wave expands, magical sparkle sounds, soft paper flutters morphing into clean digital interface swooshes, soft thumps of carpets landing neatly on the rack; 7–10s a light modern upbeat electronic pulse begins, gentle UI click and soft digital pop when the panel docks into the monitor, calm footsteps of the man; 10–13s a soft tap on the tablet screen, a rising airy whoosh as the camera dives into the screen, ending with a bright clean shimmer on the white flash.



CONSISTENCY AND QUALITY RULES: the woman's face, hairstyle and cream beige sweater with white collar stay identical to the first frame and @Image2 from every angle throughout the entire shot; the man stays identical to @Image3; the clean room matches @Image1 exactly; the logo matches @Image5 exactly with three petrol blue arrows in a circle and one green four-pointed star; the green carpet matches @Image4; natural anatomy with correct hands and five fingers; smooth, elegant, physically believable magical transformations; no morphing of faces; no flickering; no extra people; screens stay flat and stable when shown to the camera; stable clean ending on a pure white frame.



STRICTLY AVOID: readable text, letters, words or numbers anywhere including on screens, panels, papers and tags; subtitles; captions; watermarks; human speech, voices, talking, lip sync, dialogue; realistic live-action look; camera cuts; scene changes; changing the woman's outfit to a uniform; dark or gloomy lighting after the wave; chaotic or messy elements remaining after the wave.
```

---

## 4. Ролик DarkHost CRM, вставка: одна карточка заказа проходит всю систему

- **Модель:** Gemini Omni Flash 1.1 · 10 секунд · 16:9 · 1080p · звук
- **Референсы:** канбан CRM, таблица заказов, экран маршрутов, логотип — скриншоты с darkhost.tj
- **Задача:** Показать работу CRM изнутри: заказ, цех, маршрут, доставка, выручка, финальный локап с адресом сайта

Для этой части взял Gemini Omni Flash, потому что на экране нужен русский текст, а Seedance пишет буквы криво. Это вторая версия. Первая напечатала на экране hex-коды и размеры из промта, поэтому здесь цвета описаны только словами, а в конце стоит закрытый список строк, которые можно писать. Всё остальное размыто в серые линии. Логотип модель вставить не может, поэтому он описан геометрически: три стрелки, их положение по циферблату, форма звезды. Рубль заменён на доллар, в финале адрес Дархост.онлайн.

### Промт

```text
Dynamic 3D CG product-launch film, 16:9, 10 seconds, style: white-void SaaS hyper-motion 3D. A premium software launch film where a real CRM interface is deconstructed into floating frosted-glass interface slabs living in an infinite bright white space. Every element is physical: cards have thickness, columns extrude into depth, status chips flip like tiles, lines draw themselves like light. Motion is fast, snappy and engineered, with springs that overshoot slightly and settle fully, and every transition has one leading element the eye follows. There are no people, no characters, no faces, no human silhouettes and no hands anywhere in the film, only interface objects and the logo.

ABSOLUTE TEXT RULE: the only readable text allowed in the entire video is the exact on-screen text listed at the end of this prompt, plus the dollar sign symbol. Never print color names, color codes, hashtags, numbers, measurements, technical terms, timestamps, file names, the word STATUS, or any other words from these instructions. All other small interface text is rendered only as soft blurred light grey lines and bars, never as letters.

WORLD: the film opens on a pure solid white frame that seamlessly continues a previous white flash. The white gains depth and becomes an infinite soft white studio space with a very faint glossy floor reflection, no horizon line, a soft key light from the top left and gentle contact shadows under every floating object.

REFERENCES: reference image 1 is the CRM kanban board, reference image 2 is the CRM orders table, reference image 3 is the CRM routes screen, reference image 4 is the brand logo with its wordmark. The interface slabs copy the layout, card shapes, pill chips, colored column top edges and light theme of reference images 1 to 3. The logo symbol and the wordmark letterforms follow reference image 4 exactly. Personal data from the references, such as names, addresses and phone numbers, is never reproduced.

THE LOGO SYMBOL (described precisely, it opens the film): a flat, bold, perfectly geometric circular recycling-style symbol made of three separate thick curved arrow segments that together form one clockwise circle with three small gaps between them. The arrow strokes are very thick, with a uniform stroke width of about one seventh of the circle's diameter, fully rounded tail ends, and a solid deep petrol blue color, a muted dark teal-blue like deep sea water. Each arrow ends in a solid triangular arrowhead with softly rounded corners, about twice as wide as the stroke. Segment one starts at the left side of the circle at roughly the ten o'clock position with a rounded tail, sweeps clockwise up over the top of the circle, and ends with its arrowhead at roughly the two o'clock position, pointing down and to the right. Segment two starts at roughly the four o'clock position just below the right side with a rounded tail, sweeps clockwise down around the lower right, and ends with its arrowhead at roughly the seven o'clock position near the bottom, pointing down and to the left. Segment three starts at roughly the six o'clock position at the bottom with a rounded tail, sweeps clockwise up the lower left side, and ends with its arrowhead at roughly the nine o'clock position on the left, pointing straight up. In the gap on the right side of the circle, at roughly the three o'clock position, sits one bright fresh green four-pointed sparkle star: a twinkle shape with four long sharp points facing up, down, left and right, deeply concave curved sides between the points, and slightly rounded tips; the star is about one third of the circle's diameter wide, overlaps the circle's path, and is the only green element of the symbol. The symbol is flat vector-like, with no outline, no gradient and no inner detail, perfectly clean and symmetric in weight, on white.

COLOR PALETTE, described in words only and never printed: pure white and very soft light grey for the space and card surfaces; deep petrol blue, the exact blue of the logo arrows, for the logo arrows, the hero card's left edge strip, primary buttons, the route line, the chart bars and the wordmark; dark navy for the app top bar; bright fresh green, the exact green of the logo star, for the sparkle, success chips, progress lines, the last chart bar, one accent word per headline and the letters CRM; warm amber yellow only for the in-progress chip and the in-progress column top edge; soft sky blue only for the new-requests column top edge; near-black ink for headline type. No other hues exist in the film.

THE HERO, ORDER CARD AA045: a rounded-rectangle order card in landscape proportions, made of thick frosted white glass with generous rounded corners and a soft inner glow, a solid deep petrol blue vertical edge strip along its left side, and a small bright green four-pointed sparkle star set into its top-right corner. This green star in the corner is the identity anchor and must be visible in every shot. On its face: the monospace order code AA045 at top left, exactly one status pill chip at top right beside the star, a small flat teal-green rolled-carpet icon, a small square tile with a bold dollar sign symbol, two soft blurred grey lines instead of client text, and a bold sum shown as a rolling odometer of blank blurred digit tiles at bottom right. The card is the one object the camera follows from start to finish.

THE INTERFACE SYSTEM: a clean light-theme web app look copied from reference images 1 to 3: white cards on light grey, thin light grey hairline borders, rounded corners, a dark navy top bar, a left sidebar with simple line icons and no readable labels, a four-column kanban board whose columns have colored top edges in soft sky blue, warm amber, dark navy and fresh green, filled with small order cards showing only blurred lines and colored pill chips. Column headers show no text, only a small icon and a colored bar.

HEADLINE TYPE: bold geometric grotesque sans with tight tracking in near-black ink, Russian Cyrillic rendered exactly letter by letter as given, set as floating slightly extruded 3D type with a soft shadow, left-aligned in the empty space beside the action, large and crisp. Each word rises from below with a small stagger and a spring that overshoots slightly and settles. Exactly one accent word per headline is bright fresh green. Never more than one headline on screen at a time. Each headline is held sharp and still for almost a second while readable, then slides away in the direction of the next camera move.

MOTION LANGUAGE: spring physics with slight overshoot and full settle on every landing. The hero card travels between stages along smooth curved arcs. Columns, panels and charts assemble by snapping in from depth like magnetic tiles, never fading in from nothing. Status chips change state by flipping over like a tile, revealing the new color on the back, and only one chip exists at a time. Progress lines draw left to right as solid light. Transitions between modules are continuous camera travel through the interface space: dives, pull-backs, lateral glides and one tilt, never dissolves or hard cuts.

BEAT SHEET:
0.0–1.6s, LOGO IGNITION: the pure white frame holds for a few frames, then the logo symbol from reference image 4 builds itself in the center of the frame as a slightly extruded glossy 3D version of the flat symbol: the three thick deep petrol blue arrow segments draw themselves clockwise one after another with rounded tails leading and arrowheads snapping into place at the end of each stroke, then the bright green four-pointed sparkle star pops into the gap on the right side of the circle with a spring and a small glint of light. The complete symbol holds for a moment exactly matching reference image 4, then rotates once clockwise quickly. The green star detaches from the circle, flies toward the camera and unfolds like origami into the hero order card AA045, which lands facing camera with a soft spring while the blue arrows dissolve into the white. No headline.
1.6–3.2s, ORDER INTAKE: macro push-in on the card. Three small tiles snap onto its face one by one: the teal-green carpet icon, a small area icon tile, and the dollar sign tile. The blank odometer digits spin and lock. A small code tag prints out from the card's bottom edge and clicks into place. The single status chip pops in amber. Headline: Сумма — автоматически, with the word автоматически in green.
3.2–4.8s, BOARD AND WORKSHOP: fast speed-ramped pull-back. Around the card the kanban board from reference image 1 assembles in space: four column slabs snap in from depth with their colored top edges and no header text, filled with small order cards made of blurred lines and chips. The hero card arcs into the amber column, its single chip reads В цеху, and beside it three small round stage dots light up one after another as a green progress line draws through them, each followed by a small green checkmark. Headline: Все заказы в одной системе, with the word одной in green.
4.8–6.4s, ROUTES: the camera tilts down steeply as the board lays flat and morphs into a minimal abstract 3D city of white and light grey blocks. A deep petrol blue route line draws itself from a workshop pin to a home pin. A small rounded deep petrol blue van glides along the line. The hero card hovers above the route and a small round chip with a simple van pictogram clicks onto it. Headline: Маршруты водителей, with the word водителей in green.
6.4–8.0s, DELIVERED AND REVENUE: the camera rises and glides right. The hero card's single status chip flips over from amber to green and reads Доставлен. The card compresses into a glowing green token with a dollar sign, drops and lands on top of a 3D bar chart. Seven deep petrol blue bars grow upward in a staggered wave and the last bar turns green. Headline: Выручка — сразу, with the word сразу in green.
8.0–9.4s, LOCKUP: all interface slabs retreat and align into one clean hero app window at a gentle angle on the right half of the frame, fully inside the frame. On the left half, fully inside the frame with safe margins, the logo symbol appears small next to the wordmark Дархост CRM, with Дархост in deep petrol blue matching the letterforms of reference image 4 and CRM in bright green. Below it the line Заказы, цех, маршруты, касса rises in. Below that a rounded white pill chip with a thin deep petrol blue border pops in with a spring, containing the web address Дархост.онлайн in deep petrol blue. Everything is fully in place by 8.5s and holds perfectly still until 9.4s.
9.4–10.0s: the entire frame brightens and fades to pure white.

SOUND DESIGN (sound effects and a subtle music bed, absolutely no voice, no speech, no singing, no vocals): 0.0–1.6s a soft airy rising swell from silence, three crisp satisfying whoosh-sweeps as each blue arrow draws itself, a bright crystal chime with a sparkle glint when the green star pops in, a quick spin whoosh, and a soft glassy thud as the card lands; a minimal modern electronic music bed with a clean punchy beat around 120 beats per minute starts at the card landing and stays low in the mix under the effects. 1.6–3.2s three light tactile interface clicks as the tiles snap on, a fast mechanical ticking roll of the odometer ending in a firm click, a short zip sound as the tag prints. 3.2–4.8s a deep cinematic whoosh on the pull-back with a light bass hit, four soft magnetic clunks as the columns snap in, three rising digital blips as the stage dots light up, a small tick for each checkmark. 4.8–6.4s an airy tilt whoosh, a shimmering line-drawing sweep along the route, a soft smooth electric motor hum of the gliding van, a click as the chip attaches. 6.4–8.0s a satisfying tile flip followed by a bright positive success chime, a warm digital coin-drop thud as the token lands, a quick rising arpeggio as the bars grow. 8.0–9.4s a deep polished impact hit with a shimmering tail as the lockup lands, then calm. 9.4–10.0s an airy bright shimmer fading into silence with the white.

ON-SCREEN TEXT, the exact and only strings that may appear:
AA045
Сумма — автоматически
Все заказы в одной системе
В цеху
Маршруты водителей
Доставлен
Выручка — сразу
Дархост CRM
Заказы, цех, маршруты, касса
Дархост.онлайн
plus the dollar sign symbol. Nothing else is written anywhere in frame.

CONTENT SAFETY: the brand Дархост and its logo are supplied by the client. No people, faces, avatars or hands. No real personal data. No real map, only an abstract grid. No operating system chrome, browser logos, third-party icons or device brand details. No ruble sign, only the dollar sign.

CONSISTENCY: the hero card AA045 keeps the same shape, thickness, rounded corners, deep petrol blue left edge strip and the green four-pointed star in its top-right corner in every shot, especially when its chip flips to Доставлен. The logo symbol always matches reference image 4: three thick blue arrows in a clockwise circle and one green four-pointed star on the right. Column top-edge colors stay fixed. The interface stays in light theme throughout. Every headline and the lockup stay fully inside the frame.

CAMERA: allowed are speed-ramped push-ins and pull-backs, smooth lateral glides, one steep tilt-down into the route scene, gentle orbits, and macro close-ups on the card; every move eases in and out and ends in a clean settle. Forbidden are handheld shake, random jitter, tilted horizons, hard cuts, dissolves and crash zooms. Directional motion blur only during fast moves; everything is tack-sharp at rest, on every landing and whenever text is readable.

RENDER: premium clean 3D product render, frosted glass with soft glow and thin deep petrol blue edge highlights, matte white surfaces, soft global illumination, soft top-left key light with long gentle contact shadows, faint floor reflections, crisp anti-aliased edges and type. The only glow is on the green star, the green token and the green success chip. No film grain, no vignette, no lens flare, no chromatic aberration, no bokeh, no dark backgrounds, no neon, no clutter.
```

---

[https://github.com/SupremeGoogle/prompt-portfolio](https://github.com/SupremeGoogle/prompt-portfolio)
