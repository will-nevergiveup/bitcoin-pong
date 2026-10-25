# Bitcoin Pong

A classic Pong game in a single HTML file, with the ball replaced by the Bitcoin logo — on a 3D glowing circuit-board arena with lightning and digital bursts on every hit.

**Play:** https://will-nevergiveup.github.io/bitcoin-pong/

## Controls
- W / S, ↑ / ↓, mouse or touch: move your paddle (on a phone held upright the board turns so you play from the bottom: drag left / right, or use ← / →)
- Space or click / tap: start / pause
- M, the 🔇/🔊 pill on the start screen, or the top-right button: sound on / off (off by default, remembered)
- With sound on, soft ambient synth music plays on the start screen only; during a game you hear just the sound effects
- First to 5 points wins

## Pause
During play a ⏸ button sits next to the sound toggle (top-right). Tap it to pause.
- **Continue / Resume** — keep playing
- **Main menu** — reset the score and return to the start screen (where you can change language and difficulty)

On a keyboard: Space toggles pause, Esc pauses. Tapping the dimmed background does not resume.

The win / lose screen has **Play again** and **Main menu**.

## Difficulty
Pick **Easy / Normal / Hard** (繁體中文: 難度：低 / 中 / 高) on the start screen — tap a pill, press 1 / 2 / 3, or use the arrow keys when it is focused.
- Easy: slower serve and speed-up, a slow CPU that reacts late and misjudges often — easy to win.
- Normal: the original game.
- Hard: faster ball, a quicker CPU that predicts bounces but still misreads some shots — hard, but beatable.

Your choice is remembered on that device (default Normal). Link straight to one with `?diff=easy`, `?diff=normal` or `?diff=hard`.
The current level is shown during play and on the win / lose screen.

## Languages
Pick a language from the 🌐 button on the start screen:
English, 繁體中文, 简体中文, 한국어, 日本語, ไทย, Français, Español, Italiano, Deutsch, Русский.

Your choice is remembered on that device. On a first visit the game uses your browser language if it is supported (otherwise English).
You can also link straight to a language with `?lang=`, e.g. `?lang=ja`, `?lang=zh-Hant`, `?lang=zh-Hans`, `?lang=th`, `?lang=fr`.

## Extras
- `?demo=1` — attract mode: the computer plays both sides.
- The board fills most of the screen and adapts its camera to the screen shape; in portrait it rotates so the play area runs top to bottom.
