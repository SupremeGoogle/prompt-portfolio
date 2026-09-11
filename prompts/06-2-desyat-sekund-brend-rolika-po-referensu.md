# Десять секунд бренд-ролика по референсу

**Кейс 5 · шаг 2 — Покадровый таймлайн, палитра и сквозной заказ**

- **Ролик:** [https://disk.yandex.ru/d/mqkh8iDKnGrJcw](https://disk.yandex.ru/d/mqkh8iDKnGrJcw) — DARKHOST, 10 секунд, 16:9
- **Задача:** За 10 секунд показать один связный процесс: заявка → забор ковра → чистка → доставка
- **Инструмент:** Higgsfield, референс по движению — ролик HiggsFit

Модель хорошо держит стиль и плохо держит время. Поэтому в промте нет слов «динамично» и «современно»: есть точный хронометраж с секундами, фиксированная палитра в hex, один и тот же номер заказа №1248 через все кадры и список того, что появляется на экране текстом. Всё, что не перечислено в разделе с видимым текстом, модель дорисовывать не должна — иначе на финальном кадре появляется псевдокириллица рядом с логотипом.

## Промт

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

[https://github.com/SupremeGoogle/prompt-portfolio](https://github.com/SupremeGoogle/prompt-portfolio)
