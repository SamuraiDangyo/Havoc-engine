# Havoc

Gothic / Capablanca engine. Written in C++17 language.

## Features

- Xboard protocol v2 supported
- Gothic + Capablanca variants supported
- Perft / print board / list / analyze ... supported
- Super fast movegenerator
- Extremely stable code
- Level option ( 0: random mover / 1 -> 100 AI levels )
- Memory supported. 256MB default
- 1,000s of games: No time losses / illegal moves

## Results

Capablanca ( 10x8 ) 1s
```
Score of Havoc 2.2 vs Fairy-Max 5.0b: 659 - 256 - 85  [0.702] 1000
...      Havoc 2.2 playing White: 476 - 20 - 4  [0.956] 500
...      Havoc 2.2 playing Black: 183 - 236 - 81  [0.447] 500
...      White vs Black: 712 - 203 - 85  [0.754] 1000
Elo difference: 148.4 +/- 22.3, LOS: 100.0 %, DrawRatio: 8.5 %
```

Gothic ( 10x8 )  1s
```
Score of Havoc 2.2 vs Fairy-Max 5.0b: 52 - 33 - 15  [0.595] 100
...      Havoc 2.2 playing White: 25 - 20 - 5  [0.550] 50
...      Havoc 2.2 playing Black: 27 - 13 - 10  [0.640] 50
...      White vs Black: 38 - 47 - 15  [0.455] 100
Elo difference: 66.8 +/- 64.5, LOS: 98.0 %, DrawRatio: 15.0 %
```

## Buying The Engine

I'm selling the engine, contact: `kalleankka1 (at) gmail (dot) com`
I'm asking only 5€ for the engine via Paypal.
I'll send the zip-file to you email after the deal is done.

Only binary. No source code.
Only Unix / Windows OS supported at the moment.

First unzip `havoc-2.2.zip`
( On Linux: `> chmod 777 havoc-2.2-x86-unix-modern-64bit` )
Then choose the one that fits your system:
```
havoc-2.2-x86-unix-modern-64bit
havoc-2.2-x86-windows-modern-64bit.exe
```

## License

Private.
Only for personal usage.
You can't redistribute the engine in anyway.
