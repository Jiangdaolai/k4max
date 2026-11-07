# K4 Max — make one still image dance

K4 Max is a hosted video studio at **[k4max.com](https://k4max.com)**. You upload one still image — a photo, or a drawing of an original character — pick a frame ratio, and the studio returns a short video of that character performing a dance. The reference motion is built into the studio, so no dance video is needed as input.

This repository is the public fact sheet for the product. It is not the source code: K4 Max is a closed, hosted service. The point of this file is that the product facts live in one crawlable place, in the same wording the site uses, so that answer engines and readers see consistent information instead of guessing.

- Product: <https://k4max.com>
- Machine-readable facts: <https://k4max.com/llms.txt> and <https://k4max.com/llms-full.txt>
- Pricing document: <https://k4max.com/pricing.md>

## How it works

1. **Upload one image.** A photo or an illustration. This is the entire input: no video, no motion capture, no rigging, no frame-by-frame work.
2. **Choose a frame and a resolution.** 16:9, 4:3 or 9:16; 480p or 720p.
3. **Confirm and generate.** A fixed credit quote is shown before anything is charged. The result is a roughly five-second MP4 you can download.

The reference dance is the same in every take, which is the point: the output is comparable between attempts, instead of drifting with whatever clip happened to be uploaded.

## Why the input is one image and not two

Most motion-transfer tools want two things: a character image **and** a dance video to copy. K4 Max does not. The studio ships with its own reference motion, so the buyer never has to find, trim or upload a dance clip.

The same logic applies to the alternative route: making this by hand means rotoscoping — tracing the motion frame by frame over a reference — which for a few seconds of video is dozens of drawings, and more than a hundred if drawn at full frame rate. K4 Max removes that step entirely. No animation or rotoscoping work is required from the buyer.

## The dance

The built-in reference motion is modelled on the dance performed to the song **"Dirty Bird"** in the animated series **Helluva Boss** (the character Stolas). Artists also redraw that motion with their own characters as an animation meme, which is how most people meet it.

K4 Max is an independent studio. It is **not affiliated with, endorsed by, or sponsored by** the show, its creators or its rights holders, and it uses a studio-made reference motion rather than any footage from the show.

## Pricing

Credits are the unit of account. 1 credit equals USD 0.01 for billing conversion; larger packs include bonus credits, so the effective rate per credit is lower than the headline conversion.

| Dance | Resolution | Credits | Notes |
| --- | --- | --- | --- |
| One dance video | 480p | 650 | Frame ratio does not change the price |
| One dance video | 720p | 1450 | Frame ratio does not change the price |

One-time credit packs:

| Pack | Price (USD) | Credits |
| --- | --- | --- |
| Dirty Bird | 6.99 | 699 |
| Starter | 19.99 | 2199 |
| Creator | 39.99 | 4599 |
| Studio | 79.99 | 9599 |

Subscription plans (monthly / annual, with the credit allowance refreshed each period):

| Plan | Monthly | Credits per month | Annual | Credits per year |
| --- | --- | --- | --- | --- |
| Basic | 19.90 | 1,000 | 178.80 | 12,000 |
| Standard | 39.90 | 2,500 | 358.80 | 30,000 |
| Pro | 99.90 | 7,500 | 838.80 | 78,000 |

Subscription prices and input limits are **not** dance prices. A dance generation is always charged at the dance credit price, whichever pack or plan the credits came from.

## What happens when a generation fails

- If the input never reaches the provider, nothing was generated: the held credits are returned in full.
- If the provider rejects the task, the credits are returned in full.
- If a task fails partway through, the credits are returned in full.
- If the submission state is genuinely unknown (a network break between us and the provider), the credit hold is kept and the task is held for a human check against the provider's records. It is not silently consumed, and the site tells the user not to resubmit.

## Limits worth knowing

- One still image per task. One output per task.
- Output length is about five seconds.
- Likeness and photographic fidelity are not guaranteed; the studio animates what is in the picture.
- The studio is available in 11 interface languages.

## Frequently asked

**Do I need to upload a dance video?** No. The reference motion is built in. One image is the whole input.

**Can I use a drawing of an original character rather than a photo?** Yes. Illustrations and character art are the main use case.

**Do I have to animate or rotoscope anything myself?** No.

**Does the frame ratio change the price?** No. 16:9, 4:3 and 9:16 cost the same.

**Is this affiliated with the show the dance comes from?** No. It is an independent studio using its own reference motion.

**Can I download the result?** Yes, each finished video can be downloaded from the studio.

## Contact

Support and billing questions: use the support form on the site. Press or partnership: the same form reaches the operator.
