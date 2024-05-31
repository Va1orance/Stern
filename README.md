# Stern
Stern is a modern keyboard layout optimized for split keyboards. It utilizes one thumb alpha.

```
  v d l p q  / y o u ,
  s t h n b  g c a e i
  x k m f z  j w ' ; .
        r                   

MT-QUOTES:
  Alt: 33.95%
  Rol: 42.55%   (In/Out: 20.95% | 21.60%)
  One:  2.98%   (In/Out:  0.37% |  2.60%)
  Rtl: 45.53%   (In/Out: 21.33% | 24.20%)
  Red:  2.33%   (Bad:     0.24%)

  SFB: 0.35%
  SFS: 4.29%    (Red/Alt: 0.74% | 3.55%)

  LH/RH: 49.92% | 50.08%
```

It is designed to optimize SFBs, Alternation, Redirects, and LSBs in that order. 
Note*: In recent studies, redirects may not have as much of an effect as initially thought.

## Design Process
The first priority of this layout was to maintain the sth homerow. This is to maintain the STR onehand, and TH_ inward roll among others. I already knew that I wanted to use R as the thumb key. AEI homerow was understood as ideal, hence the positions for vowels and punctuation.

Next was deciding what to place on the index fingers. I wanted to use a double stack layout, so C was placed on the right index for the high movement required. Thus, N was left for the left key.

For column specific optimizations, I wanted to have good key positions with appropriate usage. This is why I used a VS_ column instead of using FS_ column. DTK was a really interesting column that I borrowed directly from SNTHR by nechro (prior, SNTH). Continuing on this trend, DTK was chosen for the ring due to usage. It works and has relatively low scissors. The most preferential key position on this layout is the choice of an LHM column. This type of column introduces three issues:
- High movement due to both M and L being commonly used keys
- LM/ML and L_M/M_L skipgrams
- MP/DM as scissors
The advantage of stacking LHM like this is it avoids having higher LSBs (through indirect influence).

As for the right index, a variety of combinations and arrangements can be chosen ranging from Y homerow, C homerow, Y LSB, etc. There are many options.

Overall, this is a nice layout if you are coming from something with an already high column usage such as:

CTGAP (CTGAP) https://github.com/CTGAP/ctgap-keyboard-layout
```
q p l c j  x f o u /
r n t s g  y h e i a
z b m w v  k d ' , .
```
Stronk (Oxey) https://oxey.dev/stronk
```
  f d l b v  j g o u ,
  s t r n k  y m a e i
  z q x h p  w c ' ; .
```
Graphite (Stronglytyped) https://github.com/rdavison/graphite-layout
```
  b l d w z  ' f o u j ; =
  n r t s g  y h a e i ,  
  q x m c v  k p . - /    
```

## Alternatives
Stern is a solid layout, but it does feature some problems (mainly LHM). Here are some other layouts that it compares to:

Dusk (https://altlayouts.com/dusk/)
```
dusk (feminist_chemo_doable) (13 likes)
  x f d p q  j ' o u .
  n s t c y  m h a e i
  b v k g w  z l _ / ,
        | r                 

MONKEYRACER:
  Alt: 28.95%
  Rol: 49.90%   (In/Out: 21.69% | 28.20%)
  One:  1.80%   (In/Out:  0.76% |  1.04%)
  Rtl: 51.69%   (In/Out: 22.46% | 29.24%)
  Red:  3.38%   (Bad:     0.32%)

  SFB: 0.48%
  SFS: 3.89%    (Red/Alt: 1.14% | 2.76%)

  LH/RH: 46.97% | 53.03%
```
An incredibly well-designed layout; Instead of having to deal with LHM as a middle column, Dusk shifts it to the index finger. This arrangement enables Dusk to avoid ML/LM/L_M/M_L as 2U sfs/sfbs. Although this does increase LSBs, the advantage it provides is worth it. On top of this, Dusk does a good job of having low sfs and managing high rolls. Overall, Dusk just does a great job with little wrong.

Aptmak (Eve)
```
aptmak (Eve) (6 likes)
  v w f p b  j l u y '
  r s t h k  x n a i o
  ; c g d q  z m , . /
               e                   

MONKEYRACER:
  Alt: 24.36%
  Rol: 47.84%   (In/Out: 30.52% | 17.31%)
  One:  3.26%   (In/Out:  2.38% |  0.88%)
  Rtl: 51.10%   (In/Out: 32.91% | 18.19%)
  Red:  5.75%   (Bad:     1.75%)

  SFB: 1.10%
  SFS: 5.56%    (Red/Alt: 2.48% | 3.08%)

  LH/RH: 42.79% | 57.21%
```
An older layout that used to be the top recommendation for thumb alpha layouts, Aptmak does an overall decent job, but now it is just worse than the likes of Dusk, Stern, and SNTH. The main reason for this is the high amount of SFBs and SFSs caused by LNM and the left hand in general. YOU is a redirect, and just overall, the layout could be improved. That being said, it does have impressively high inrolls.

RSTHD (Xah Lee) https://xsznix.wordpress.com/2016/05/16/introducing-the-rsthd-layout/
```
RSTHD (cmini) (0 likes)
  j c y f k  z l , u q =
  r s t h d  m n a i o '
  / v g p b  x w . ; -  
               e                     

MONKEYRACER:
  Alt: 24.64%
  Rol: 49.17%   (In/Out: 31.72% | 17.45%)
  One:  3.37%   (In/Out:  2.66% |  0.71%)
  Rtl: 52.54%   (In/Out: 34.38% | 18.16%)
  Red:  4.36%   (Bad:     0.27%)

  SFB: 0.96%
  SFS: 5.91%    (Red/Alt: 3.48% | 2.43%)

  LH/RH: 43.00% | 57.00%
```
You may notice this layout's similarity with Aptmak, but in fact, this is potentially the oldest, semi-well-designed alt layout. Being published in 2016, I have to give it some slack. It does again feature high rolls, but from high sfbs and sfs. I still recommend SNTH, Stern, or Dusk above this.

```
snthr (nehcro) (3 likes)
  f b d m q  = y o u ,
  s n t h v  g c a e i
  x p k l j  z w ' / .
        r                   

MONKEYRACER:
  Alt: 34.23%
  Rol: 43.69%   (In/Out: 26.41% | 17.28%)
  One:  3.01%   (In/Out:  0.53% |  2.49%)
  Rtl: 46.70%   (In/Out: 26.94% | 19.77%)
  Red:  2.48%   (Bad:     0.39%)

  SFB: 0.40%
  SFS: 4.65%    (Red/Alt: 0.70% | 3.95%)

  LH/RH: 49.77% | 50.23%r
```
As mentioned so many times already, this in SNTHR (but in essentially the same layout as SNTH). It bears close resemblance to both Stern and Dusk, but came before both. This layout again uses an index LHM stack, but features more Stern-like other features. There isn't really much for me to say other than this is like a mix of Dusk and Stern. It's a good layout (probably move the M into LSB like Dusk) that works.



As of writing this (using Stern), I have reached 160 WPM on Monkeytype 60s, and can comfortably hit 100-120 WPM on sentences. It certainly does a good job, and feels comfortable, but I do feel that the M position could be resolved, as well as the general usage of the bottom row. I'd feel comfortable recommending people to try this, but do realize that this is a high alternation layout, instead of the usual high roll layout. Otherwise, try out Dusk or SNTH, both are good options as well. If you want minimal bottom row usage, you can check my layout family: Night.
