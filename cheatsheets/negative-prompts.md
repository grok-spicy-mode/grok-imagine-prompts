# Negative Prompts Cheat Sheet

While Grok Imagine doesn't directly support negative prompts, you can guide results by emphasizing positive alternatives.

## Understanding Negative Prompting

**Traditional Negative Prompts** (not supported):
```
"portrait --no blurry, bad hands, deformed"
```

**Grok Imagine Approach** (supported):
```
"portrait, sharp focus, anatomically correct hands, well-proportioned face"
```

## Common Issues and Solutions

### Avoiding Blurriness

**Instead of:** "no blur"
**Use:**
```
sharp focus, crystal clear, tack sharp, high resolution, 8k uhd
```

**Example:**
```
"portrait, sharp focus on eyes, crystal clear details, 8k uhd, professional photography"
```

### Avoiding Low Quality

**Instead of:** "no low quality"
**Use:**
```
high quality, professional, 8k uhd, photorealistic, detailed
```

**Example:**
```
"landscape, professional photography, high quality, 8k uhd, award winning"
```

### Avoiding Bad Anatomy

**Instead of:** "no bad hands, no deformed"
**Use:**
```
anatomically correct, well-proportioned, realistic anatomy, natural pose
```

**Example:**
```
"character design, anatomically correct proportions, natural human anatomy, well-formed hands and fingers, professional character art"
```

### Avoiding Artifacts

**Instead of:** "no artifacts, no glitches"
**Use:**
```
clean, smooth, professional, polished, refined
```

**Example:**
```
"digital art, clean lines, smooth gradients, polished finish, professional quality, 8k uhd"
```

### Avoiding Wrong Style

**Instead of:** "no cartoon, no anime"
**Use:**
```
photorealistic, realistic, natural, professional photography
```

**Example:**
```
"portrait, photorealistic style, realistic skin texture, natural lighting, professional photography, 8k uhd"
```

### Avoiding Clutter

**Instead of:** "no busy background"
**Use:**
```
clean background, minimalist, simple composition, negative space, uncluttered
```

**Example:**
```
"product photo, clean white background, minimalist composition, simple and elegant, professional product photography"
```

### Avoiding Dark/Underexposed

**Instead of:** "not too dark"
**Use:**
```
well-lit, bright, proper exposure, good lighting, illuminated
```

**Example:**
```
"interior photo, well-lit room, bright natural lighting, proper exposure, professional photography"
```

### Avoiding Overexposed

**Instead of:** "not blown out"
**Use:**
```
balanced exposure, proper lighting, well-exposed, good dynamic range
```

**Example:**
```
"portrait, balanced exposure, proper lighting, natural skin tones, professional photography"
```

## Style-Specific Positive Alternatives

### For Realistic Photography

**Avoid blurry/soft:**
```
sharp focus, tack sharp, crystal clear, high sharpness, 8k uhd
```

**Avoid artificial:**
```
natural, photorealistic, authentic, realistic, true to life
```

**Avoid bad composition:**
```
professional composition, rule of thirds, balanced, well-framed
```

### For Digital Art

**Avoid low quality:**
```
highly detailed, professional digital art, trending on artstation, concept art quality
```

**Avoid messy:**
```
clean linework, polished, refined, professional illustration
```

**Avoid flat:**
```
dimensional, depth, good lighting, volumetric, atmospheric
```

### For Character Art

**Avoid deformed:**
```
anatomically correct, proper proportions, realistic anatomy, well-formed features
```

**Avoid stiff pose:**
```
natural pose, dynamic stance, fluid movement, realistic body language
```

**Avoid generic:**
```
distinctive features, unique character design, detailed costume, personality
```

### For Landscapes

**Avoid boring:**
```
dramatic lighting, interesting composition, dynamic clouds, vibrant colors
```

**Avoid flat:**
```
atmospheric perspective, depth, layered mountains, foreground interest
```

**Avoid dull:**
```
vibrant colors, good contrast, rich tones, colorful
```

## Emphasis Through Repetition

**Single Mention:**
```
"portrait, sharp focus"
```

**Emphasized:**
```
"portrait, sharp focus, crystal clear, tack sharp, high sharpness"
```

**Very Emphasized:**
```
"portrait, extremely sharp focus, tack sharp, crystal clear definition, maximum sharpness, pin sharp, 8k uhd"
```

## Positive Specification Strategies

### Strategy 1: Describe What You Want

**Instead of:** "no modern elements"
**Use:**
```
traditional, classical, period-accurate, historical, authentic medieval
```

### Strategy 2: Specify Quality

**Instead of:** "no bad quality"
**Use:**
```
high quality, professional, 8k uhd, detailed, polished
```

### Strategy 3: Define Style Clearly

**Instead of:** "no cartoon style"
**Use:**
```
photorealistic, realistic photography, natural, professional photo
```

### Strategy 4: Emphasize Correct Features

**Instead of:** "no six fingers"
**Use:**
```
anatomically correct hands, five fingers per hand, realistic hand anatomy, well-formed hands
```

## Common Problem Solutions Table

| Problem | Positive Alternative |
|---------|---------------------|
| Blurry | sharp focus, crystal clear, 8k uhd |
| Dark | well-lit, bright lighting, proper exposure |
| Distorted | accurate proportions, well-formed, realistic |
| Flat | depth, atmospheric, dimensional, volumetric |
| Messy | clean, organized, polished, refined |
| Generic | unique, distinctive, detailed, specific |
| Artificial | natural, realistic, authentic, genuine |
| Boring | dynamic, interesting, dramatic, compelling |
| Cluttered | clean, simple, minimalist, uncluttered |
| Oversaturated | natural colors, balanced, realistic tones |
| Washed out | vibrant, rich colors, good contrast |
| Noisy | clean, smooth, professional quality |

## Advanced Positive Prompting

### Layered Specification

**Level 1 - Basic:**
```
"portrait, photorealistic"
```

**Level 2 - Enhanced:**
```
"portrait, photorealistic, sharp focus, professional photography"
```

**Level 3 - Detailed:**
```
"portrait, photorealistic, sharp focus on face, crystal clear eyes, natural skin texture, professional photography, 8k uhd"
```

**Level 4 - Maximum:**
```
"portrait, photorealistic, tack sharp focus on eyes, crystal clear facial features, realistic skin pores and texture, natural makeup, professional studio photography, perfect exposure, 8k uhd, commercial quality"
```

### Contextual Guidance

**Vague:**
```
"forest scene"
```

**Guided:**
```
"forest scene, bright daylight, clear visibility, well-defined trees, sharp details, vibrant green foliage, professional nature photography"
```

## Testing Your Positive Prompts

### A/B Test Method

**Test 1: Basic vs Detailed**
- A: "character design"
- B: "character design, anatomically correct proportions, natural pose, realistic features, detailed"

**Test 2: Generic vs Specific**
- A: "good quality portrait"
- B: "portrait, sharp focus, crystal clear, photorealistic skin, professional lighting, 8k uhd"

### Iteration Method

1. Generate with basic prompt
2. Identify issues in result
3. Add positive alternatives for those issues
4. Regenerate and compare
5. Repeat until satisfied

**Example Iteration:**

**v1:** "dragon"
- Problem: Too vague, low detail

**v2:** "dragon, detailed"
- Problem: Still generic

**v3:** "dragon, highly detailed scales, sharp focus, photorealistic, professional digital art"
- Better: More specific

**v4:** "dragon, hyperdetailed individual scales, sharp focus on face, photorealistic textures, dramatic lighting, professional concept art, 8k uhd, trending on artstation"
- Best: Comprehensive positive specification

## Quick Reference Positive Replacements

### Quality Issues
- Blurry → sharp focus, crystal clear
- Low quality → high quality, professional, 8k uhd
- Artifacts → clean, polished, refined

### Composition Issues
- Cluttered → clean, simple, minimalist
- Boring → dynamic, interesting, dramatic
- Bad framing → professional composition, well-framed

### Lighting Issues
- Too dark → well-lit, bright, good lighting
- Too bright → balanced exposure, proper lighting
- Flat → dramatic lighting, volumetric, atmospheric

### Anatomy Issues
- Deformed → anatomically correct, realistic proportions
- Wrong fingers → well-formed hands, five fingers
- Unnatural → natural pose, realistic anatomy

### Style Issues
- Wrong style → [specify exact style wanted]
- Inconsistent → cohesive style, uniform aesthetic
- Unclear → clearly defined [style name]

---

**Perfect Your Prompts**: Test positive alternatives at [GrokPrompts.app](https://grokprompts.app)
