# engine-sim-garage
 An unofficial repository for custom parts and engines for AngeTheGreat's Engine Simulator: https://github.com/ange-yaghi/engine-sim

Tested working on Build v0.1.8a.

## Installing an engine
1. Clone/download the repo and copy the `assets` folder from it into the `engine-sim` root folder.
2. Edit `engine-sim/assets/main.mr` and add `import` line(s) for the new engines:  
`import "engines/kirbyguy22/toyota_2jz_ge.mr"`
3. Change the engine in the `set_engine` function in `engine-sim/assets/main.mr` to the Node name of the engine:  
```
set_engine(
        engine: toyota_2jz_ge()
    )
```

## Available Engines
| Origin | Manufacturer | Engine | Layout | Displacement (L) | Node Name | Author |
| --- | ------------ | ------ | ------ | ---------------- | ---------- | ------ |
| JPN | TOYOTA | 2JZ-GE | I6 | 3.0 | toyota_2jz_ge | kirbyguy22 |
| JPN | SUBARU | EJ25 | F4 | 2.5 | subaru_ej25 | kirbyguy22 |
| JPN | HONDA | C30A | V6 | 3.0 | honda_c30a | kirbyguy22 |
| USA | DODGE | VIPER SR II | V10 | 8.0 | dodge_viper_srii | kirbyguy22 |
| GER | PORSCHE | 980/01 | V10 | 5.7 | porsche_980_01 | kirbyguy22 |
| GER | BMW | S70/2 | V12 | 6.1 | bmw_s70_2 | kirbyguy22 |
