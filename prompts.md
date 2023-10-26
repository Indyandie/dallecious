# Dall E Prompts

## Prompt Template

> #### dalle tips
>
> - **Starting with the Image Type:** The type of illustration (cell shade animation illustration) was moved to the beginning for clarity.
> - **Detailed Descriptions:** Breaking down the character's description into separate sections helps Dall-E understand and prioritize different features.
> - **Consistency:** Repetitive information, such as "Tom Bombadil", was streamlined for coherence.
> - **Color Palette:** Specifying that "vibrant pastel colors" dominate the scene gives Dall-E a clear color direction.
> - **Clear Background:** Emphasizing the "plain empty white background" ensures no unexpected elements appear.

> #### Best Practices for Accurate Images:
>
> - **Be Explicit:** Clearly specify details. The more descriptive, the better.
> - **Sequence Matters:** Start with the general type of image, then delve into specifics.
> - **Limit Conflicting Instructions:** Ensure the prompt doesn't have contradictory details.
> - **Test & Iterate:** If the image isn't perfect the first time, tweak your prompt and try again.

### basic

```
Style/Type |
Composition |
Place/Setting |
Subject |
Color/Mood |
Descriptions
```


### Effective Sequence

Effective Sequence Template for Dall-E 3 Descriptions.

1. **Image Type/Style**
   - This sets the overall context for the image. For example: "photorealistic painting", "cell shade animation illustration", "vintage photograph", etc.
1. **Image Composition/Frame**
   - Establishing the composition can help set the boundaries. For example: "full-length portrait", "landscape orientation", "close-up shot", etc.
1. **Background/Environment**
   - Setting the scene or background before introducing characters or objects can help Dall-E understand the context. Examples include "mountainous backdrop", "plain empty white background", "nighttime city skyline", etc.
1. **Major Elements/Characters**
   - Descriptions of the main subjects of the image. For characters, it would involve details like age, skin color, facial features, clothing, and accessories.
1. **Posture/Actions**
   - Describes the activity or pose of the subjects. For example: "sitting on a stone bench", "dancing under the rain", "staring at the horizon", etc.
1. **Color Palette/Theme**
   - Specifying the color scheme or mood can give Dall-E a direction for the overall tones. For example: "vibrant pastel colors", "monochromatic blue tones", "warm sunset hues", etc.
1. **Additional Details/Accessories**
   - Additional elements or props that are part of the scene but not the main focus. For example: "holding a tree branch", "wearing a silver pendant", "surrounded by floating candles", etc.
1. **View/Perspective**
   - Specifying from which angle the scene should be viewed. For instance: "bird's-eye view", "worm's-eye view", "frontal perspective", etc.

#### Description Types Examples 

##### Image Type/Style:

- Digital vector illustration
- Vintage photograph
- Abstract acrylic painting
- Charcoal sketch
- Voxel rendering

##### Image Composition/Frame:

- Close-up portrait
- Over-the-shoulder shot
- Aerial view of a landscape
- Split-screen comparison
- Full-body portrait capturing a single character from head to toe against a neutral backdrop.
- Close-up of a character's face, highlighting expressive eyes and intricate facial features.
- Wide-angle shot showcasing a vast landscape with tiny silhouettes of people in the distance.
- Tightly framed mid-shot focusing on a character's torso and hands, possibly holding an object of interest.
- Diagonal composition with leading lines directing the viewer's eye towards a central subject.
- Over-the-shoulder perspective, showing the viewpoint of one character looking at another or a specific scene.
- Birds-eye aerial shot, capturing a scene from directly above, offering a unique top-down perspective.
- Dynamic action shot capturing a character in mid-motion, possibly during a jump or sprint.
- Framed using natural elements, like a character viewed through an archway or between hanging tree branches.
- Split-frame composition, where the image is divided into sections, each showcasing different elements or characters.

##### Background/Environment:

- Desert oasis with palm trees
- Snowy mountain peak
- Bustling urban cityscape at dusk
- Tranquil seaside with crashing waves

##### Major Elements/Characters:

- Knight in shining armor with a red crest
- Modern-day scientist in a lab coat examining vials
- Ghostly apparition floating above ground
- Robot with steampunk design elements

##### Posture/Actions:

- Sprinting with determination
- Meditating in a lotus position
- Arguing with animated gestures
- Painting on a canvas with focus

##### Color Palette/Theme:

- Cool blues and silvers for a winter theme
- Bright neon colors for an 80s retro vibe
- Pastel shades for a springtime feel
- Dark and moody with heavy shadows for a noir setting

##### Additional Details/Accessories:

- A raven perched on a shoulder
- Intricate tattoos covering arms
- A pocket watch swinging from a chain
- Luminous crystals embedded in a staff

##### View/Perspective:

- Worm's-eye view looking up at skyscrapers
- Cross-section of an anthill
- First-person perspective from inside a car
- Overhead shot of a dance floor

### Template Sequence:

This sequence can be adapted based on the specific requirements of the image, but it serves as a general guideline for structuring detailed and effective prompts for Dall-E.;

```
Type/Style ;
Composition/Frame ;
Background/Environment ;
Elements/Characters ;
Posture/Actions ;
Color Palette/Theme ;
Additional Details/Accessories ;
View/Perspective```

## Segmenting/Layering

Some strategies to layer prompts.

### Hierarchical Descriptions

Start with a broad setting and then dive into specifics. For instance:

- **General:** A bustling city.
- **Specific:** In the foreground, a woman is walking her dog. In the background, there's a tall skyscraper with a digital clock.

### Sequential Prompts 

You can guide DALL·E through a sequence of events or scenes by describing them in order.

**Example:** A serene lakeside at dawn. As the sun rises, birds start to chirp, and a fisherman casts his line.

### Contrasting Elements

Describe two or more contrasting elements or scenes to give DALL·E multiple focal points.

**Example:** On the left, a desert with cacti and a blazing sun. On the right, a snowy mountain peak.

### Use of Punctuation

Use punctuation like dashes, commas, or semicolons to separate different elements of the scene.

**Example:** A park in autumn - children playing with fallen leaves, joggers on the track, a couple having a picnic.

### Explicit Layering

Directly instruct DALL·E to layer elements.

**Example:** In the first layer, a dense forest. In the second layer, magical creatures peeking through the trees.

### Multiple Iterations

Start with a base prompt to get an initial image. Then, use that image as a reference and provide a new prompt to add more details or layers.

## Cascade Prompts

> [@techhalla](https://x.com/techhalla/status/1715030023613116770?s=46)

[noun] ; Style ; Setting ; Palette ; Description [noun_variants]

```
[country] ; impressionism ; tea party ; neutral colors ; bunnies hops along a corridor [england, india, japan, italy]
```

## Consistent Prompts

> [@umesh_ai](https://x.com/umesh_ai/status/1714975725332373790?s=46)

1. Ask to use the prompt as is.
2. Add a define seed at the end of the prompt.

Please use the exact prompt in double quotes (DO NOT ALTER IT FOR ANY REASON) and generate 2 image(s):

PROMPT: "`prompt`" `seed{seed_number}`
