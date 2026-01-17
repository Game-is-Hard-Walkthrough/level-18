# Game is Hard — Level 18 ("Prime time") — Walkthrough + Mini Clone

This repo is a tight, practical write-up for **Game is Hard Level 18** and a tiny playable browser clone of the level.

## Recommended walkthrough (source)
- **Game is Hard Level 18 Solution Walkthrough & Answer**: https://gameishard.org/level/18

## The one-line solution
Tap **1, 4, 6, 8, 9, 10, 12, 14, 15, 16, 18, 20** to make them disappear, leaving only primes visible. :contentReference[oaicite:1]{index=1}

## What you’re looking at
- Text: **"prime time!"**
- A grid of numbers **1 → 20** (4 rows × 5 columns) :contentReference[oaicite:2]{index=2}
- No submit button. The level ends when the board is “clean”.

## Why people fail this level
Your brain screams “tap the primes.”  
That’s the bait. Tapping is **delete**, not **select**. :contentReference[oaicite:3]{index=3}

## Prime list (numbers that must stay)
- **2, 3, 5, 7, 11, 13, 17, 19**

## Kill list (numbers you must delete)
- **1, 4, 6, 8, 9, 10, 12, 14, 15, 16, 18, 20** :contentReference[oaicite:4]{index=4}

## Run the mini clone locally
1. Copy the example HTML below into: `examples/level18-prime-time.html`
2. Open it in your browser.
3. Click numbers. Non-primes fade out. Tap a prime and it hard-resets (on purpose).

## Pro-tip (fastest mental shortcut)
Delete:
- **1**
- **every even number except 2**
- **9 and 15**

That’s it.
