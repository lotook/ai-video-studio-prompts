# AI Video Studio Prompt Notes

Practical prompt patterns for multi-model AI video generation, collected while testing [AI Video Studio](https://ai-studio.video/), a web workspace that runs Seedance, Kling, Veo and Sora video models plus Nano Banana, GPT Image, Seedream and Z Image image models from one account with shared credits.

## Why compare models side by side
Different video models read the same prompt differently. Running one brief through two or three models is the fastest way to learn which one handles motion, faces or text best for a given shot.

## A prompt template that travels well between models
```
[Subject] doing [action] in [setting].
Camera: [shot size], [movement].
Light: [time of day / style].
Mood and pacing: [calm / energetic], [duration].
```
Example: "A ceramic coffee cup on a wooden table, steam rising slowly. Camera: close-up, slow push-in. Light: soft morning window light. Mood: calm, 5 seconds."

## Image first, then video
1. Make a still frame with an image model (text-to-image).
2. Edit details with image-to-image until the frame looks right.
3. Feed that frame into image-to-video so the motion starts from a frame you already approved.

## Checklist before generating
- One subject and one main action per clip
- Name the camera movement explicitly
- Pick 16:9 for web/YouTube, 9:16 for Shorts/Reels/TikTok

## Links
- Website: https://ai-studio.video/

AI Video Studio is an independent product of Lotook, LLC and is not affiliated with Google AI Studio, Google, OpenAI, ByteDance or Kuaishou.
