# Common Mistakes and Solutions

Learn from common pitfalls when creating grok imagine prompts and how to fix them.

## Top 10 Most Common Mistakes

### 1. Being Too Vague

**Mistake:**
```
"A person"
"Nice landscape"
"Cool car"
```

**Problem:** AI doesn't know what specific type you want.

**Solution:** Be specific about every element.
```
"Professional businesswoman in her 30s, confident expression, wearing navy suit"
"Mountain landscape at sunset with alpine lake reflection, golden hour lighting"
"Sleek black sports car, lamborghini style, wet city street, neon reflections"
```

### 2. Forgetting Quality Keywords

**Mistake:**
```
"Portrait of wizard"
```

**Problem:** Results may be low quality or unclear.

**Solution:** Always add quality modifiers.
```
"Portrait of wizard, detailed robes with mystical symbols, dramatic lighting,
fantasy digital art, 8k uhd, highly detailed, trending on artstation"
```

### 3. Ignoring Lighting

**Mistake:**
```
"Girl in forest"
```

**Problem:** Lighting dramatically affects mood and quality.

**Solution:** Specify lighting type.
```
"Girl in forest, dappled sunlight through trees, volumetric lighting,
golden hour, soft natural light"
```

### 4. No Style Direction

**Mistake:**
```
"Dragon flying"
```

**Problem:** Could be cartoon, realistic, painting, etc.

**Solution:** Clearly define artistic style.
```
"Dragon flying, fantasy digital art, detailed scales, concept art style,
trending on artstation"
OR
"Dragon flying, photorealistic, nature documentary style, detailed anatomy"
```

### 5. Conflicting Styles

**Mistake:**
```
"Photorealistic anime cartoon oil painting"
```

**Problem:** Contradictory styles confuse the AI.

**Solution:** Choose compatible styles or commit to one.
```
"Anime style character, digital art, studio trigger aesthetic"
OR
"Photorealistic portrait, oil painting technique, traditional art"
```

### 6. Overcomplicating Prompts

**Mistake:**
```
"A mystical enchanted magical fantasy ethereal supernatural otherworldly
dreamlike surreal abstract cosmic spiritual divine transcendent..."
```

**Problem:** Too many similar modifiers dilute effectiveness.

**Solution:** Choose 2-3 strong descriptors per element.
```
"Mystical forest scene, ethereal atmosphere, magical lighting,
fantasy digital art, 8k uhd"
```

### 7. Missing Technical Specifications

**Mistake:**
```
"Portrait of person, photorealistic"
```

**Problem:** Missing camera/lens details for photography style.

**Solution:** Add technical photo/render details.
```
"Portrait of person, photorealistic, 85mm lens, f/1.4,
shallow depth of field, studio lighting, 8k uhd"
```

### 8. Unclear Subject Position

**Mistake:**
```
"Warrior and dragon and castle"
```

**Problem:** Relationship between elements unclear.

**Solution:** Describe spatial relationships.
```
"Warrior standing before massive dragon, with ancient castle in background,
dramatic confrontation, epic fantasy scene"
```

### 9. Neglecting Composition

**Mistake:**
```
"Beach sunset"
```

**Problem:** No compositional guidance.

**Solution:** Specify framing and composition.
```
"Beach sunset, rule of thirds composition, palm tree silhouette in foreground,
sun setting on horizon, wide angle perspective"
```

### 10. Not Matching Resolution to Subject

**Mistake:**
```
"Headshot portrait" (using 1920x1080)
"Wide landscape" (using 1024x1024)
```

**Problem:** Wrong aspect ratio for subject.

**Solution:** Match resolution to subject type.
```
"Headshot portrait" → 1024x1024 (square)
"Wide landscape" → 1920x1080 (wide)
```

## Style-Specific Mistakes

### Realistic Photography Mistakes

**Mistake:** Missing camera specs
```
❌ "Portrait, photorealistic"
✅ "Portrait, photorealistic, 85mm lens, f/1.8, studio lighting, 8k uhd"
```

**Mistake:** Unrealistic lighting combinations
```
❌ "Portrait, sunset and studio lighting"
✅ "Portrait, golden hour natural lighting" OR "Portrait, studio lighting"
```

**Mistake:** Vague photography type
```
❌ "Photo of food"
✅ "Food photography, overhead shot, natural window light, rustic wooden table"
```

### Digital Art Mistakes

**Mistake:** No art platform reference
```
❌ "Fantasy character"
✅ "Fantasy character, digital art, trending on artstation, concept art quality"
```

**Mistake:** Missing detail level
```
❌ "Sci-fi scene"
✅ "Sci-fi scene, hyperdetailed environment, intricate tech details, 8k uhd"
```

### Anime Mistakes

**Mistake:** Just saying "anime" without specifics
```
❌ "Anime girl"
✅ "Anime girl, studio trigger style, vibrant colors, detailed eyes, anime key visual"
```

**Mistake:** Wrong aspect ratio
```
❌ "Anime character" (1920x1080 wide)
✅ "Anime character" (1024x1024 or 1024x1536 for full body)
```

### Oil Painting Mistakes

**Mistake:** No brush technique specified
```
❌ "Oil painting of landscape"
✅ "Oil painting of landscape, visible brush strokes, impasto technique,
impressionist style"
```

**Mistake:** Missing artist reference
```
❌ "Portrait painting"
✅ "Portrait painting, rembrandt lighting, oil painting technique,
old master style"
```

## Quality-Related Mistakes

### Mistake: Single Quality Keyword

**Wrong:**
```
"Forest scene, 8k"
```

**Better:**
```
"Forest scene, 8k uhd, highly detailed, photorealistic, professional photography"
```

### Mistake: Quality Keywords Don't Match Style

**Wrong:**
```
"Anime character, photorealistic, 8k uhd"
```

**Better:**
```
"Anime character, sharp linework, vibrant colors, anime aesthetic, 8k uhd"
```

## Composition Mistakes

### Mistake: No Depth Indication

**Wrong:**
```
"Castle on hill"
```

**Better:**
```
"Castle on hilltop in background, meadow with wildflowers in foreground,
atmospheric perspective, depth of field"
```

### Mistake: Cluttered Scene

**Wrong:**
```
"Castle and dragon and wizard and knights and village and mountains and forest and river..."
```

**Better:**
```
"Epic fantasy scene: wizard confronting dragon at castle gates,
with mountains and forest in background, dramatic composition"
```

## Color and Lighting Mistakes

### Mistake: Conflicting Color Instructions

**Wrong:**
```
"Monochrome vibrant colorful scene"
```

**Better:**
```
"Vibrant colorful scene, rich saturated colors"
OR
"Monochrome scene, black and white, high contrast"
```

### Mistake: Impossible Lighting

**Wrong:**
```
"Noon sunlight with golden hour glow and blue hour atmosphere"
```

**Better:**
```
"Golden hour lighting, warm sunset glow"
```

## Character Design Mistakes

### Mistake: Contradictory Features

**Wrong:**
```
"Young elderly tall short muscular thin character"
```

**Better:**
```
"Elderly wizard, tall and thin, weathered features, wise expression"
```

### Mistake: Missing Distinctive Features

**Wrong:**
```
"Elf character"
```

**Better:**
```
"Elf ranger, long silver hair, emerald eyes, pointed ears,
leather armor with nature motifs, detailed character design"
```

## Technical Mistakes

### Mistake: Incompatible Technical Specs

**Wrong:**
```
"Macro photography, wide angle lens"
```

**Better:**
```
"Macro photography, 100mm macro lens, f/2.8"
```

### Mistake: Wrong Depth of Field

**Wrong:**
```
"Landscape with everything sharp focus, shallow depth of field"
```

**Better:**
```
"Landscape with deep depth of field, everything in focus, f/11"
```

## How to Fix Your Prompts

### The Checklist Method

Go through this checklist for every prompt:

- [ ] **Subject clearly defined?**
- [ ] **Action/pose specified?**
- [ ] **Environment described?**
- [ ] **Lighting type included?**
- [ ] **Style clearly stated?**
- [ ] **Technical specs appropriate?**
- [ ] **Quality keywords present?**
- [ ] **No contradictions?**
- [ ] **Resolution matches subject?**

### The Expansion Method

Start simple and add layers:

**Version 1:** "Dragon"

**Version 2:** "Red dragon in cave"

**Version 3:** "Massive red dragon in mountain cave with treasure"

**Version 4:** "Massive red dragon in mountain cave with treasure hoard,
dramatic lighting from lava"

**Version 5:** "Massive red dragon in mountain cave with treasure hoard,
dramatic lighting from lava, detailed scales, fantasy digital art,
8k uhd, trending on artstation"

### The Subtraction Method

If prompt is too long or conflicting:

1. Remove duplicate modifiers
2. Remove contradicting styles
3. Keep strongest descriptors
4. Ensure clarity over complexity

**Before:**
```
Mystical magical ethereal supernatural dreamlike surreal fantasy portrait,
photorealistic anime style oil painting digital art, dramatic soft bright dark lighting
```

**After:**
```
Mystical portrait, ethereal atmosphere, fantasy digital art,
soft dramatic lighting, 8k uhd, trending on artstation
```

## Testing for Mistakes

### A/B Testing Method

Generate two versions:

**Test 1: With vs Without Lighting**
- A: "Forest scene, 8k uhd"
- B: "Forest scene, volumetric sunlight through trees, golden hour, 8k uhd"

**Test 2: Vague vs Specific**
- A: "Character design"
- B: "Cyberpunk hacker character, neon hair, tech implants, detailed design, 8k uhd"

**Test 3: Generic vs Styled**
- A: "Mountain, 8k"
- B: "Mountain range at sunset, ansel adams style, dramatic clouds, 8k uhd"

## Quick Reference: Before & After

| Wrong | Right |
|-------|-------|
| "Person" | "Professional woman in her 30s, business attire, confident pose" |
| "Nice view" | "Mountain landscape, golden hour, lake reflection, wide angle" |
| "8k" | "8k uhd, photorealistic, highly detailed, professional" |
| "Photo" | "Professional photography, 85mm lens, studio lighting" |
| "Art" | "Digital art, trending on artstation, concept art quality" |
| "Colorful" | "Vibrant saturated colors, rich color palette" |
| "Dark" | "Dark moody atmosphere, low key lighting, dramatic shadows" |

---

**Avoid These Mistakes**: Use our prompt builder at [GrokPrompts.app](https://grokprompts.app) with built-in validation
