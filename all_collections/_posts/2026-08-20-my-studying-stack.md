---
layout: post
title: My Studying Stack
date: 2026-08-20 01:54 +0300
categories: ["productivity"]
---

The title might sound a bit weird. Why would anyone have a "stack" for studying,
and what does that even mean?

"Studying stack" means the tools, utils, and rituals I use to actually sit down
and study

## The full stack

- Workspace: [niri](https://github.com/niri-wm/niri),
  [Ghostty](https://github.com/ghostty-org/ghostty),
  [tmux](https://github.com/tmux/tmux), [nvim](https://github.com/neovim/neovim)
- Annotation: [Xournal++](https://github.com/xournalpp/xournalpp)
- Notes: [Typst](https://github.com/typst/typst),
  [typst-preview.nvim](https://github.com/chomosuke/typst-preview.nvim),
  [EinkBro](https://github.com/plateaukao/einkbro)
- Automation: [OpenCode](https://github.com/anomalyco/opencode),
  [poppler-utils](https://poppler.freedesktop.org)
- Attention & memory: [taskbeep](https://github.com/youssefadly237/taskbeep),
  [mneme](https://github.com/youssefadly237/mneme)
- Misc: Wacom tablet, [Brave](https://github.com/brave/brave-browser), Spotify
  (lofi beats)

## Hardware and environment

I ditched pen and paper a long time ago and switched to a small Wacom tablet. It
just feels cleaner and more flexible, with dual monitors, one is always the
terminal, the other is whatever I need alongside it, a YouTube explanation, a
reference book, depends on the subject.

I hate floating window managers, so I use niri. Since I'm on Linux, I try to use
it properly, which means living in the terminal. I went with Ghostty because it
has shaders (nice cursor animations like Kitty) without Kitty's weird text
rendering quirks.

tmux is always running so I can jump between different tools without thinking.

I also use taskbeep, my own little Pomodoro-style (not really) timer, which lets
me track my productivity stats per topic, ensuring that I am actually studying
not just wasting time, and when I do waste time, it is clear as day.

## Annotation and understanding

I use Xournal++ to annotate PDFs and books. When the PDFs are uni material, it
helps me mark important parts and figure out how I want to refactor them later.

## Handling uni material

University material eats up most of my time (because it sucks), here's how I
deal with it:

1. Extract text and images from the PDFs with poppler-utils
2. Recreate the material in Typst using nvim (cleaner and better than the
   original)
3. Use OpenCode while rewriting (it helps a lot)
4. Live preview with typst-preview.nvim, viewed full-screen on my phone through
   EinkBro

A question may arise here: ain't that time consuming? Surprisingly not that
much. My Typst template covers most of what I need, so I don't waste time
fighting the tool itself. I'm also okay with touch typing (~70 WPM consistent).
More importantly, it forces you to output what you just took in. A lot of the
time you think you understood something after reading it, but nah, you actually
didn't.

This way I end up with proper notes instead of messy slides, that I was forced
to study to create the notes.

## Spaced repetition

I use mneme (which is my own app, still in alpha, and I'm basically the only
user) an Anki-like app, combined with OpenCode + MCP, you get the perfect card
generation workflow.

## Background noise and the internet

No study session is complete without Spotify in the background (lofi beats).

Brave for the rest wiki, docs, whatever comes up, and chat jipiti as a personal
tutor when I need to check if I actually understood the shit I am studying.

Most of the config for all of this is available in my
[dotfiles](https://github.com/youssefadly237/dotfiles).

Sooooo, is this a good studying stack? tbh I have no idea. It works, I study,
and that's pretty much it. At some point you have to stop optimizing the stack
and just use it.
