# Shuffle the toads, then ask in order

A live simulation of Algorithm 3 (`FindTrustworthyToad3`) from CSE301 Homework 2, Problem 3.

**Open it:** https://mushfique-dgist.github.io/shuffle-the-toads/

There are n toads in DGIST, and strictly more than n/2 of them are trustworthy. A toad expert can check one toad in Θ(1) time. Algorithm 3 puts the toads in a random order, then asks the expert about each toad in turn, and returns the first toad the expert approves.

The page plays each run step by step next to the algorithm's code, and charts how many questions the runs needed:

- **Random order** or **Worst order** (every tricky toad first)
- **Toads** slider from 5 up to 1000 toads (above 20, each toad is drawn as a small cell), and a **Tricky** slider
- **Play**, **Pause**, **Keep playing**, **+100 runs**, **Reset**, and three speeds

Keyboard: Space play / pause · Enter one run · A keep playing · Q +100 runs · R reset · F full screen.

The whole page is one self-contained `index.html`: the fonts and pictures are embedded, and it makes no network requests. It also works offline: download `index.html` and open it in any modern browser.
