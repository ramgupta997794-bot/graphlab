# GraphLab

An interactive mathematics visualisation workspace — 2D function graphing and a 3D
surface laboratory, with a rich set of animations you can run several at a time.

## Open it

- **Web app:** https://ramgupta997794-bot.github.io/graphlab/
- **Single file (offline, no install):** https://ramgupta997794-bot.github.io/graphlab/GraphLab.html
- **Android app:** https://ramgupta997794-bot.github.io/graphlab/GraphLab.apk

## What it does

**2D graphing** — plot several functions at once, pan and zoom, trace values, and
run numeric calculus (derivative, integral, roots, limits).

**3D surfaces** — plot z = f(x, y), orbit with touch, colour by height, and read
the coordinates of any point by tapping it.

**Animations (2D: 13, 3D: 11)** — tap as many as you like and they run together:
Draw-on, Comet, Pulse, Wave, March, Rainbow flow, Bounce, Zoom reveal, Fade,
Scanline, Jitter, Spin, Morph. In 3D: Auto-rotate, Orbit, Float, Wave, Pulse,
Colour cycle, Spin, Breathe, Spiral, Bob, Morph.

**One-tap travelling wave** — loads sin(x - a) (2D) or sin(x - a)*cos(y) (3D)
with Morph switched on, so the constant sweeps and the wave travels by itself.

**Record** — save any animation as a shareable video.

## Installing the Android app

1. Open the APK link above on the phone.
2. Tap the downloaded file.
3. If Android asks, allow "Install unknown apps" for your browser.
4. Tap Install.

If you already have an older GraphLab installed, uninstall it first — the app is
signed with a development key and Android will not overwrite a differently signed
build.

## Notes

- The Android build bundles the app as one self-contained HTML file, so it runs
  offline and does not depend on the WebView's ES-module support.
- The maths parser is a hand-written recursive-descent parser; user input is never
  evaluated as JavaScript.
