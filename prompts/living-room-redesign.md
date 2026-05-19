# Living Room Redesign — Gemini Nano Banana Prompt

Source: photo of a Cape Town-style terrace living room (wall-mounted TV, mid-century walnut credenza, gray sectional, persian rug, french doors to plant-filled patio).

## Settings

| Param | Value |
|-------|-------|
| Model | `gemini-3.1-flash-image-preview` (fallback: `gemini-2.5-flash-image`) |
| Aspect ratio | `16:9` |
| `imageSize` | `2K` (use `1K` for the 2.5 fallback) |
| Thinking | `medium` |

## Run command

```bash
python3 .claude/skills/banana/scripts/generate.py \
  --api-key "$GEMINI_API_KEY" \
  --aspect-ratio "16:9" \
  --resolution "2K" \
  --model "gemini-3.1-flash-image-preview" \
  --prompt "$(cat prompts/living-room-redesign.prompt.txt)"
```

## Design intent

Keep the architectural shell (white walls, oak floors, black-framed french doors, walnut credenza, gray sectional, persian rug) and layer in warm-minimalist Architectural Digest styling:

- **TV wall** — salon-style gallery of six framed pieces around the screen so it reads as part of the composition
- **Credenza styling** — rule-of-three: amber glass vase with pampas, stacked art books with brass tray, matte-black ceramic lamp
- **Greenery** — six-foot fiddle-leaf fig in clay planter beside the credenza
- **Window treatment** — floor-to-ceiling oat-white linen drapery puddled on the floor
- **Floor** — layer the persian rug over a larger jute rug to anchor the seating zone
- **Coffee table** — round travertine on a cylindrical base replacing the small ottoman
- **Sofa styling** — three layered cushions (bouclé cream, terracotta linen, vintage kilim) + chunky cream throw
- **Lighting** — slim arching brass floor lamp from behind the sofa
- **Palette** — warm whites, walnut, terracotta, sage, brass
