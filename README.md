# Tanamr's layouts

Many of the layouts developed by [trialyzer](https://github.com/samuelxyz/trialyzer) are rather strange. However, now and then a few of them look like they might actually be good. I may also end up making layouts by other means, and those will be included here as well if I deem them sufficiently noteworthy.

These layouts may be subject to change; any changes will be indicated if they occur.

# ints

```
f o u m j  x c d b ,
 h a e r q  y s t n i
  ' / l w z  v g k p .
```

This layout is designed for a row-staggered board with angle mod. Preferably, the right thumb should be used for spacebar. A non-angle-modded version can be obtained by cycling `z` to the left end of the bottom row.

Notable characteristics:
- High rolls, majority inward.
- Unusually high onehands, extremely inward (2.4 inward ratio, increases to 3.3 when adding space on the right thumb).
- High redirects, though only slightly higher than Colemak.
- Low alternation.
- Low lateral stretching.
- Reasonably low dsfb (according to the genkey skipgram weightings).
- Index fingers can support alt fingering to remove same finger sequences such as `wl`, `syst`, `cyc`, and possibly `lm`.

## genkey stats

Statistics from [semi's genkey analyzer](https://github.com/semilin/genkey) using the `-stagger` flag.

```
ints
f o u m j  x c d b ,
h a e r q  y s t n i
' / l w z  v g k p .
Rolls (l): 29.87%
        Inward: ~18.78%
        Outward: ~11.09%
Rolls (r): 21.05%
        Inward: ~12.56%
        Outward: ~8.49%
Alternates: ~21.49%
Onehands: ~6.47%
Redirects: ~12.20%
Finger Speed (weighted): [0.12 2.05 1.12 4.49 3.24 0.71 0.74 1.19]
Finger Speed (unweighted): [0.18 7.38 5.37 24.68 17.82 3.40 2.65 1.79]
Highest Speed (weighted): 4.49 (LI)
Highest Speed (unweighted): 24.68 (LI)
Index Usage: 14.8% 14.8%
SFBs: 0.923%
DSFBs: 6.605%
LSBs: 0.57%
Top SFBs:
        sc 0.138%       rm 0.136%       ue 0.129%       ys 0.105%
        rl 0.077%       oa 0.075%       gs 0.061%       sy 0.049%

Worst Bigrams:
        ml 21.358       rl 18.368       oa 16.790       ue 14.676
        cs 11.290       o' 10.904       mr 10.294       ys 8.489
```

## Previous versions

2022-04-20: Rearranged keys on the index fingers to improve `wl`, `'l`, and `g`.
Previous version:

```
f o u l q  x y d b ,
 h a e r j  v s t n i
  ' / w m z  g c k p .
```

# seht-drai

```
f u l v b  ; g n o j 
 s e h t k  z d r a i .
  ' m p w q  y c x / , 
```

This layout is designed for a row-staggered board with angle mod. A non-angle-modded version can be obtained by cycling `q` to the left end of the bottom row.

Notable characteristics:
- Incredibly high onehands, including the most frequent trigrams such as `the`, `and`, `ing`, `ion`
- Rolls tend to be leftward, interestingly.
- Low sfb and dsfb stats.
- Redirect levels comparable to Colemak.
- Low alternation.
- The left ring and pinky may be a problem point (imagine typing `useful`).

## genkey stats

Statistics from [semi's genkey analyzer](https://github.com/semilin/genkey) using the `-stagger` flag.

```
seht-drai
f u l v b  ; g n o j
s e h t k  z d r a i .
' m p w q  y c x / ,
Rolls (l): 23.00%
        Inward: ~7.82%
        Outward: ~15.18%
Rolls (r): 25.08%
        Inward: ~16.19%
        Outward: ~8.89%
Alternates: ~22.10%
Onehands: ~10.09%
Redirects: ~11.10%
Finger Speed (weighted): [0.64 2.49 2.25 3.47 1.80 1.19 1.23 1.50]
Finger Speed (unweighted): [0.96 8.97 10.79 19.11 9.88 5.72 4.44 2.24]
Highest Speed (weighted): 3.47 (LI)
Highest Speed (unweighted): 19.11 (LI)
Index Usage: 16.3% 10.9%
SFBs: 0.776%
DSFBs: 6.035%
LSBs: 0.67%
Top SFBs:
        rn 0.137%       ue 0.129%       pt 0.078%       tw 0.075%
        oa 0.075%       dy 0.049%       e' 0.048%       cy 0.032%

Worst Bigrams:
        lm 24.472       ue 19.568       oa 16.790       nr 16.162
        tp 15.416       i. 11.352       e' 10.620       bt 9.998
```
