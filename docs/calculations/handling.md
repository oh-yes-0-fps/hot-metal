---
description: Learn more about how we test and calculate weapon handling
---

# Handling

## How we calculate draw and stow time

There a few visual hints that can be used to determine when weapons are drawn or stowed. What we use if the changing of the reticle and the firing of the weapon as indicators. we use an automated script to swap weapons that holds down fire. The time from button press to reticle change is the stow time and the time from reticle change to fire is the draw time.

## How we calculate ads speed

Ads speed is also hard because of the largly varying scopess that come on the guns in this game. The most reliable way is to look at when the radar disapears, so it's simply time from button press to radar disapearing.

## Why does my stow stop going down at a certain point?

Stow speed is capped at whatever it is at 100 handling even if scalars should be bringing it lower. There is also *most likely* a cap for draw and ads but these have yet to be delved into and for now are ignored
