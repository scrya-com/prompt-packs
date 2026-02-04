# Scrya Prompt Packs

Official prompt library for the [Grok Video Extractor](https://github.com/scrya-com/grok-video-extractor) Chrome extension.

## Overview

This repository contains curated prompts for generating Episode Interactive-style pixel art characters and animations using Grok Imagine.

## Files

| File | Description | Count |
|------|-------------|-------|
| `actions.txt` | Animation action prompts (idle, talk, react, etc.) | ~200 |
| `characters.txt` | Character definitions with appearance prompts | ~250 |
| `outfits.txt` | Clothing and outfit prompts | ~120 |
| `lighting.txt` | Lighting and atmosphere prompts | ~180 |
| `wildcards.json` | Wildcard variations for dynamic prompts | ~3600 |

## Usage

### In Grok Video Extractor

1. Go to **Settings → Prompts**
2. Select **Remote** as the source
3. The default URL is pre-filled: `https://raw.githubusercontent.com/scrya-com/prompt-packs/main/config.json`
4. Click **Load Remote**

### Custom Config URL

You can fork this repo and modify the prompts. Update the config URL in the extension settings to point to your fork.

## File Formats

### actions.txt
```
# Category Header
action_key: Description of the action
```

Example:
```
# TALKING ANIMATIONS
talk_neutral: Speaking with neutral expression
talk_happy: Speaking cheerfully
talk_excited: Speaking with enthusiasm and gestures
```

### characters.txt
```
ID | Name | Category | Base Prompt
```

Example:
```
1 | Emma Classic | protagonist | Young woman with long wavy brown hair, green eyes, casual white t-shirt
2 | Maya Confident | protagonist | Young Black woman with curly natural hair, confident pose, red crop top
```

### outfits.txt
```
outfit_key: Description
```

Example:
```
crop_top_midriff: Crop Top, Midriff Baring
short_dress: Short Dress, Leggy Sophistication
```

### lighting.txt
```
lighting_key: Full lighting description
```

Example:
```
golden_hour_warm: Golden hour lighting with warm orange hues and long soft shadows
blue_hour_cool: Blue hour lighting with cool cerulean tones and low contrast
```

### wildcards.json

JSON structure with folders and files containing variations:
```json
{
  "name": "clothesWildcards_v10",
  "folders": [
    {
      "name": "Cardigan",
      "files": [
        {
          "name": "cardigan_style1.txt",
          "lines": ["Oversized chunky knit cardigan", "..."]
        }
      ]
    }
  ]
}
```

## Contributing

1. Fork this repository
2. Add or modify prompts following the file formats above
3. Submit a pull request

### Guidelines

- Keep prompts concise but descriptive
- Use lowercase with underscores for keys
- Group related prompts under category headers
- Test prompts with Grok Imagine before submitting
- Maintain consistent style within each file

## License

MIT License - Free to use, modify, and distribute.

## Links

- [Grok Video Extractor Extension](https://github.com/scrya-com/grok-video-extractor)
- [Scrya](https://scrya.com)
