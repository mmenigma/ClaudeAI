# image-prompts.md — Image Generation & Pinterest Pin Standards
*Read this file whenever generating images or Pinterest pins for Cannademy.com or cannabischeri.com posts.*

---

## Overview

This file governs all image prompt generation for blog posts across both sites. It covers:
- Featured images and in-post images (for Gemini generation)
- Pinterest pins (image prompts + text overlays + pin descriptions)

All image prompts are placed in **Section A only** of the delivered post document. They are never inside Section B.

---

## Model Selection

| Image type | Model |
|---|---|
| Featured/hero image | Gemini 3.1 Pro (higher quality) |
| In-post images | Gemini 3.1 Flash Lite (faster, lower cost) |
| Pinterest pins | Gemini 3.1 Flash Lite (faster, lower cost) |

---

## Cannabis Content Rule

People, cannabis leaves, cannabis plants, and raw cannabis flower may be included when they strengthen the image concept. Finished food and wellness products are always acceptable.

## On composition:

Single-subject images leave too much dead space in the 1500px tall format — always compose with multiple elements (hero food + supporting items like jars, ingredients, utensils, garnishes, or a second food item) to fill the vertical space naturally
Aim for a kitchen, or table setting scene, not a product shot

## On food variety:

gummy worms, gummy cannabis leaves, gummies shapes, brownies of diffrent varieties-not just chocolate, cookies, rice crispy treats, pasta, sauces, soups, salad dressings, hot beverages, pizza
No more than one brownie image per post, and avoid brownies entirely when other foods are equally relevant to the topic

## On infusions:
Whenever depicting the actual infusion or topical it needs to have a green or light green tint so it's known to be infused with cannabis.

---

## Style Palette — Assign a DIFFERENT Style to Each Image in the Post

Do not repeat the same style twice within a single post. Track which styles have been used in recent posts and avoid repeating across consecutive posts.

| Style | Lighting | Mood |
|---|---|---|
| Warm golden hour | Soft directional side light, amber tones | Cozy, homey, abundant |
| Cool bright studio | Diffused overhead daylight, crisp neutral shadows | Clean, modern, editorial |
| Moody dark | Dramatic single-source side light, deep shadows | Sophisticated, artisan |
| Airy minimal | Pale even light, minimal props, lots of negative space | Calm, spa-like, serene |
| Rustic farmhouse | Soft natural window light, textured surfaces | Approachable, handmade, wholesome |
| Modern clean | Bright overhead, geometric arrangements, graphic shadows | Precise, contemporary |
| Cozy evening | Warm lamp or candlelight glow, soft shadow | Intimate, relaxed, personal |
| Bright outdoor | Natural open shade or dappled sunlight | Fresh, energetic, lifestyle |

---

## Surface and Background Palette — Vary Across Images

Never use the same surface in two images within the same post.

**Light surfaces:** white marble, pale limestone, light ash wood, parchment paper, cream linen, white ceramic tile, bleached oak

**Mid-tone surfaces:** butcher block, natural pine, terracotta tile, sage linen, unbleached cotton, warm concrete

**Dark surfaces:** dark walnut, slate, charcoal concrete, black granite, deep espresso wood, aged cast iron

**Textile/soft surfaces:** folded linen towel, knit throw, raw cotton cloth, woven rattan tray, weathered burlap

---

## Pinterest Pins — Keyword and Description Rules

Pinterest is a search engine. Every pin must be optimized for how people actually search, not just written to sound compelling.

### Text Overlay (the headline on the image)

- Lead with the primary search keyword phrase — write it the way someone would type it into Pinterest search
- Example: **"How to Make Edibles Without Wasting Cannabis"** not **"Stop Wasting Cannabis on Weak Edibles"**
- 6–10 words maximum — must be legible at thumbnail size
- Each of the three pins per post should target a different keyword angle on the same post topic

### Pin Description (entered in Pinterest when uploading — not on the image)

- 150–300 characters
- Open with the primary keyword phrase naturally in the first sentence
- Read like a mini intro to the post, not a caption
- Include 2–3 related keyword phrases worked in naturally
- End with a soft CTA: "Get the full guide at Cannademy.com" or similar
- No hashtags — keyword phrases significantly outperform hashtags

**Example — post about dosing homemade edibles:**

> Text overlay: How to Dose Homemade Edibles (Step-by-Step)
>
> Description: Learn how to dose homemade edibles accurately every time — even without a lab test. This step-by-step guide covers the dosing formula, decarb variables, and how to calculate mg per serving for any recipe. Full guide at Cannademy.com.

---

## Pinterest Pins — Scheduling Notes

- Pinterest pins are posted to Pinterest only — they are NOT embedded in the blog post
- Space pin uploads out over separate days or weeks via CCM — do not upload all three at once
- Each pin links back to the blog post URL

---

## Required Output Format

```
IMAGE PROMPTS — Gemini Generation

Styles used: [list style name assigned to each image — no repeats within post]

Featured Image — 16:9 landscape (Gemini 3.1 Pro)
Style: [style name from palette]
Surface/background: [surface from palette]
[Prompt — include: subject, food styling details, specific lighting from chosen style,
mood, surface/background detail, aspect ratio, "no text"]

In-Post Image 1 — tied to [Section Name] — 4:3 (Gemini Flash Lite)
Style: [style name — must differ from featured image]
Surface/background: [surface — must differ from featured image]
[Prompt — "no text"]

In-Post Image 2 — tied to [Section Name] — 4:3 (Gemini Flash Lite)
Style: [style name — must differ from images above]
Surface/background: [surface — must differ from images above]
[Prompt — "no text"]

Pinterest Pin 1 — 2:3 portrait, 1000px x 1500px (Gemini Flash Lite)
Style: [style name]
Surface/background: [surface]

Image prompt: [Prompt — include: subject, food styling, lighting from chosen style,
"leave clean space at top or bottom for text overlay, no text"]
Text overlay: [Keyword-led headline — 6–10 words, written as a search query]

Pin description: [150–300 characters, opens with primary keyword phrase, includes
2–3 related keywords naturally, ends with soft CTA to Cannademy.com]

Pinterest Pin 2 — 2:3 portrait, 1000px x 1500px (Gemini Flash Lite)
Style: [style name — must differ from Pin 1]
Surface/background: [surface — must differ from Pin 1]

Image prompt: [Prompt]Text overlay: [Different keyword angle from Pin 1]

Pin description: [150–300 characters, different keyword angle from Pin 1]

Pinterest Pin 3 — 2:3 portrait, 1000px x 1500px (Gemini Flash Lite)
Style: [style name — must differ from Pins 1 and 2]
Surface/background: [surface — must differ from Pins 1 and 2]

Image prompt: [Prompt]
Text overlay: [Different keyword angle from Pins 1 and 2]

Pin description: [150–300 characters, different keyword angle from Pins 1 and 2]
```
*Applies to Cannademy.com and cannabischeri.com*
*Voice rules: brand-voice.md | SEO/AEO standards: seo-aeo-standards.md*
*Blog post workflow: BLOG-WORKFLOW.md*

**recipe titles for food inspiration

1. Cannabis Rice Krispie Treats Recipe (Easy 10-Min Edibles)
2. Easy Cannabis Peanut Butter Cookies Recipe (Freezer-Friendly)
3. Mango and Black Bean Cannabis Rice Salad
4. Ode to Afroman Infused Lemon Pound Cake Recipe
5. Chicken and Weed Dumplings: Cannabis Comfort Food
6. Sugar Free Cannabis Keto Brownies Recipe
7. Wake and Bake Edibles: How to Make Weed French Toast
8. YUM! How to Make Weed Pancakes: Tips and Infused Recipes
9. Cannabis Gazpacho Recipe – 420 Gazpacho!
10. Cannabis Peach Cobbler Recipe
11. Weed Infused Cheesecake Recipe
12. How to Make Stoned Pizza: Super Easy Weed Pizza Recipe
13. Easy No-Cook Weed Pizza Sauce Recipe
14. Best Cannabis Biscuits Recipe
15. Cannabis Keto Recipes!!!
16. Cannabis Keto Lemon Curd Recipe
17. Cannabis Guacamole Recipe
18. Cannabis Oatmeal Cookies with Raisins Recipe
19. Cannabis-Infused Buffalo Weed Wings Recipe
20. Best Ever Weed Cinnamon Rolls Recipe
21. Recipe for Cannabis Lemon Bars
22. How to Make Cannabis Fudge
23. Cannabis Lemon Curd Recipe
24. How to Make Weed Chocolate Covered Strawberries
25. Danksgiving: Mary Jane's Marijuana Recipes for Thanksgiving
26. Quick and Easy Apple Marijuana Muffins Recipe
27. How to Make Lemon Raspberry Marijuana Muffins
28. Cheri's Favorite Cannabis Potato Salad Recipe
29. Chocolate Chip Chocolate Marijuana Muffins
30. Classic Cannabis Bran Muffins Recipe
31. Recipe for Easy Cast Iron Skillet Cannabis Cornbread
32. Slow Cooker Cannabis Baked Beans Recipe
33. Easy to Make Cannabis BBQ Sauce Recipe
34. Amazing Summer Berry and Lemon Cannabis Trifle Recipe
35. Awesome Weed Strawberry Shortcake Recipe
36. Cannabis Toum – Infused Lebanese Garlic Sauce Recipe
37. Cannabis Vinaigrette – The Easiest, Healthiest, Way to Use Cannaoil
38. 420 Party Food: Cannabis Chex Mix Recipe
39. Churros Style Cinnamon Sugar Cannabis Popcorn Recipe
40. Delicious Nutritious Cannabis Hummus Recipe
41. Recipe for Chocolate Chip Oatmeal Cannabis Bars
42. Recipe for Quick and Easy Blueberry Marijuana Muffins
43. Marijuana Nanaimo Bars Recipe: Canada's Favorite Treat Becomes an Edible
44. Marijuana Butter Tarts Recipe – Canada's Favorite Dessert Gets a Mary Jane Makeover
45. Weed Donuts! Recipe for Canadian Style Cannabis Beaver Tails
46. Recipe for Marijuana Elote en Vaso (Corn in a Glass) – Mexican Style Street Corn
47. Sex Pot: Marijuana Edible Chocolate Body Paint Recipe
48. Marijuana Munchies for the Big Game: Infused Snack Recipes
49. Mary Jane's Soup Kitchen: Cannabis Soups Recipe Collection
50. Recipe for Marijuana French Onion Soup Au Gratin
51. Marijuana Tortilla Soup with Vegetables Recipes
52. Recipe for Easy Marijuana Salsa from Pantry Ingredients
53. Happy Holidaze Merry Marijuana Cookie Swap Party
54. Amazing Marijuana Kugel with Raisins Recipe
55. Pistachio Orange Marijuana Baklava Recipe
56. Festive Holiday Cannabis Recipes for Infused Celebrations
57. Cannabis Infused DIY Edibles Gifts from Your Kitchen
58. That Turkey's High! How to Make Marijuana Deep Fried Turkey
59. Mary Jane's Marijuana Pumpkin Spice Recipes
60. Pumpkin Spice Weed Latte Recipe
61. Marijuana Pumpkin Pie Recipe
62. 420 Halloween Party: Marijuana Halloween Recipes and Tips
63. Dank Dorm Room Marijuana Recipes for Starving Students
64. Make Pretzel Marijuana S'Mores with a Dab Torch!
65. Microwave Marijuana Pizzadillas Recipe
66. Quick and Easy Microwave Marijuana Omelet in a Mug Recipe
67. Chocolate Marijuana Molten Lava Cake Recipe
68. Cheese Stuffed Marijuana Jalapeño Poppers Recipe
69. Infused Coconut Oil Key Lime Weed Cupcakes Recipe
70. Recipe for Mota Mint Marijuana Brownies
71. Marijuana Ice Cream: Espresso Cannabis Gelato Recipe
72. Easy to Make Weed Cupcakes Marijuana Recipe Collection
73. Marijuana Deviled Eggs Recipe
74. Strawberry Banana Vegan Cannabis Smoothie Recipe
75. Thai Style Peanut Sauce Marijuana Macrobiotic Bowl Recipe
76. Versatile Cannabis Peanut Sauce Recipe
77. Quick Edibles! How to Quickly Make Marijuana Snack Foods
78. Marijuana Bundt Cake: Pistachio Irish Cream Mini Weed Bundt Cakes
79. Cannabis King Cake Recipe for Marijuana Mardi Gras
80. Infused Cannabis Shrimp Creole Recipe
81. Marijuana Steel Cut Oats with Blueberries and Hemp Seeds Recipe
82. Marijuana Egg Salad Recipe
83. Cranberries and Cannabis Banana Bread Recipe
84. Recipe for Heart Shaped Linzer Cannabis Cookies
85. Marijuana Spinach Salad Recipe with Orange and Grilled Salmon Recipe
86. CBD Caramels: Recipe for Soft and Chewy Orange CBD Caramels
87. Soft and Chewy Orange Marijuana Caramels Recipe
88. Soft and Chewy Nutty Cannabis Caramels Recipe
89. Reefer Raspberry Cannabis Rugelach Cookies Recipe
90. Festive Marijuana Gingerbread Cookies Recipe
91. Recipe for Marijuana Pfeffernusse Cookies
92. Recipe for Peppermint Candy Cane Cannabis Brownies
93. Cannabis Eggnog Custard Recipe
94. Marijuana Gingerbread Cupcakes with Cream Cheese Molasses Icing
95. Refreshing Ginger Orange CBD Tea With Honey Recipe
96. Marijuana Pies: How to Make Cannabis Infused Pies
97. Cannabis Pecan Pie Recipe
98. Marijuana Blueberry Pie Edibles Recipe Baked in a Mason Jar Lid
99. Cannabis Apple Pie Recipe Baked in Mason Jar Lids
100. Amazing Marijuana Pie Crust Recipe
101. Marijuana Green Bean Casserole Recipe
102. Marijuana Pumpkin Cheesecake Recipe
103. Marijuana Pumpkin Roll Cake Recipe
104. Halloween Chocolate Mini Cannabis Cupcakes Recipe
105. Roasted Cannabis Infused Pumpkin Seeds Recipe
106. Marijuana Ratatouille Recipe
107. Jalapeño Marijuana Mac and Cheese Recipe
108. Cannabis Bruschetta Recipe
109. Recipe for Easy Overnight Marijuana Monkey Bread
110. Marijuana Shrimp Cocktail Recipe
111. Marijuana Blueberry Cobbler Cupcakes Recipe
112. Cannabis Hot Fudge Sauce Recipe
113. Best Ever Recipe for Gluten Free Marijuana Brownies
114. Dank and Decadent Marijuana Lobster Bisque Recipe
115. How to Make Weed Jerky, Plus Cannabis Jerky Recipes
116. Marijuana French Bread Pizza Recipe
117. Cocoa Kahlua Cannabis Cupcakes Recipe
118. Watermelon Marijuana Salad Recipe with Cucumber and Feta
119. Blueberry Cannabis Cupcakes Recipe w/ Lemon Weed Frosting
120. Cream Cheese Filled Lemon Cannabis Cookies Recipe
121. Mango Marijuana Lassi Recipe
122. Mango and Cucumber Cannabis Salad Recipe
123. Mango and Almond Marijuana Quinoa Salad Recipe
124. Mango Marijuana Upside Down Cake Recipe
125. Marijuana Mango Salsa Recipe with Infused Tortilla Chips
126. Won Ton Chips, Avocado and Spicy THC Tuna Recipe
127. Mango Marijuana Chutney Recipe
128. Orange Nutella Marijuana Cupcakes Recipe
129. Cannabis Tuna Salad with White Beans Recipe
130. Red Velvet Weed Cupcakes Recipe
131. How to Make Cannabis Chili: Marijuana Chili Recipe
132. Marijuana Avgolemono Recipe: Infused Lemon Chicken Soup
133. Chocolate Chip Banana Weed Muffins Recipe
134. Marijuana Eggs Benedict Recipe
135. Recipe for Amazing Vegan CBD Eggnog
136. DIY Stoner Gifts from the Kitchen
137. Chocolate Peanut Butter Marijuana Tarts Recipe
138. Cannabis Apple Crisp Recipe
139. Recipe for Marijuana Snickerdoodles Cookies
140. Baked Ham and Egg Cannabis Recipe
141. Grilled Fish Tacos with Green Chile Cannabis Salsa Recipe
142. Almond, Orange, Cucumber and Cannabis Stuffed Avocado Recipe
143. Herbed Red Potato Vegan Cannabis Potato Salad Recipe
144. Best Ever Cannaburger Recipe
145. Vegan Heirloom Tomato Marijuana Salad Recipe
146. Recipe for Amazing Raspberry Cheesecake Marijuana Brownies
147. Vegan Marijuana Veggie Wraps Recipe w Medicated Peanut Sauce
148. Almond Coconut Cannabis Brownies Made with Coconut Oil
149. Recipe for Rocky Road Pot Brownies
150. Recipe for Amazing Cheesecake Marijuana Brownies
151. Recipe for Pecan Chocolate Chip Marijuana Blondies
152. Coconut Oil Cannabis Brownies Recipe
153. Awesome Avocado, Tomato, and Cucumber Cannabis Salad Recipe
154. Weed Munchies: THC Pretzels Sweet and Spicy Cannabis Snack Mix
155. Cannabis Pesto Recipe
156. Recipe for Peanut Butter Pot Brownies
157. Tomato, Cauliflower and Garbanzo Bean Marijuana Curry Recipe
158. Roast or Grilled Chicken with Marijuana Cilantro Sauce Recipe
159. Marijuana Italian Sub Weed Sandwich Recipe
160. Mayonnaise-less Lemon Garlic Marijuana Slaw Recipe
161. Homemade Hempy Marijuana Granola Recipe
162. Salted Cannabis Caramel Corn Recipe
163. Sweet and Spicy and Mixed Marijuana Nuts Recipe
164. Marijuana Tabouli Recipe
165. Wowie Wedge Salad with Marijuana Blue Cheese Dressing Recipe
166. Orange and Chocolate Chip Marijuana Scones Recipe
167. Marijuana Corn Chowder Recipe
168. Hearty Vegan Winter Vegetable Marijuana Soup Recipe
169. Marijuana Jambalaya Recipe
170. Tamale Style Marijuana Stuffed Peppers Recipe
171. Marijuana Kale Chips Recipe
172. Mushroom and Blue Cheese Weed Risotto Recipe
173. Recipe for Cannabis Cinnamon Roll Cookies
174. Injectable Lemon Herb Marijuana Marinade Recipe
175. Injectable Cajun Cannabis Marinade Recipe for Poultry
176. Injectable BBQ Marijuana Marinade for Turkey or Chicken
177. Marijuana Mashed Potatoes Recipe
178. HERBed Apple Marijuana Stuffing Recipe
179. Weed Steak: Filet Mignon With Chive Cannabutter and Blue Cheese
180. Roasted Garlic, Sour Cream and Chive Cannabis Mashed Potatoes Recipe
181. Pecan Streusel Stuffed Cannabis Sweet Potatoes Recipe
182. Apples with Cannabis Caramel Dip Recipe
183. Death by Chocolate Halloween Decorated Weed Cupcakes Recipe
184. Halloween Spiderweb Marijuana Bean Dip with "Baked" Tortilla Chips
185. Infused Marijuana Pot Stickers Recipe
186. Sweet and Spicy Marijuana Meatballs Recipe
187. Marijuana Stuffed Mushrooms Recipe
188. The Future Is Uncertain and the End Is Always Near: Cannabis Cocktail Recipe
189. Marijuana Boba Tea Recipe: Honey Duke Relaxer Cannabis Cocktail
190. Potato Head Blues: Cannabis Coffee Cocktail Recipe by Warren Bobrow
191. Dark Chocolate Raspberry Marijuana Trifle Recipe
192. Black Bean and Corn Marijuana Salad Recipe
193. Stoner Snack Recipes: Infused Movie Night Popcorn Mix
194. Roasted Lemon Parmesan Marijuana Brussels Sprouts Recipe
195. Berry Lemon Weed Pound Cake Recipe
196. Recipe for Chocolate Peanut Butter Cup Cannabis Cookies
197. Balsamic Roasted Cannabis Brussels Sprouts Recipe
198. Halloween Marijuana Cookies: Creepy Finger Cookies Recipe
199. Cold Soba Marijuana Noodles Recipe with Chicken and Veggies
200. Amazing Vegan Raw Chocolate Weed Pudding Recipe
201. Marijuana Spinach Salad Recipe with Reefer Raspberry Vinaigrette
202. Very Berry Frozen Weed Yogurt Pops Recipe
203. Sesame Honey Lime THC Chicken Wings Recipe
204. Grilled Flank Steak with Cannabis Chimichurri Sauce Recipe
205. Meatball Parm Marijuana Sliders Recipe
206. Easy Baked Cannabis Tortilla Chips Recipe
207. Bacon Wrapped Weed and Goat Cheese Stuffed Dates Recipe
208. Weed Matzo Ball Soup Recipe
209. Marijuana Shrimp Salad Stuffed Tomato Recipe
210. Cucumber and Radish Marijuana Salad Recipe
211. Apple Parmesan Cannabis Risotto Recipe
212. Enlightened Marijuana Waldorf Salad Recipe
213. Mixed Green Salad with Marijuana Pomegranate Vinaigrette Recipe
214. Recipe for Chocolate Chip Toffee Weed Cookies
215. Devilishly Good Weed and Orange Juice THC Drink Recipe
216. Dulce de Leche Weed Banana Caramel Cupcakes Recipe
217. Stir Fried Marijuana Ginger Shrimp and Asparagus Recipe
218. Marijuana Chicken Salad Recipe with Cashews and Grapes
