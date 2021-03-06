# Shure SE535
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -4.4; 23 -4.5; 25 -4.6; 28 -4.7; 31 -4.7; 34 -4.8; 37 -5.0; 41 -5.2; 45 -5.3; 49 -5.5; 54 -5.7; 60 -6.0; 66 -6.3; 72 -6.8; 79 -7.1; 87 -7.4; 96 -7.7; 106 -8.0; 116 -8.2; 128 -8.5; 141 -8.8; 155 -9.0; 170 -9.2; 187 -9.3; 206 -9.4; 227 -9.5; 249 -9.5; 274 -9.5; 302 -9.4; 332 -9.2; 365 -8.8; 402 -8.7; 442 -8.6; 486 -8.6; 535 -8.1; 588 -7.9; 647 -7.7; 712 -7.5; 783 -7.3; 861 -7.3; 947 -7.5; 1042 -7.7; 1146 -7.9; 1261 -8.0; 1387 -8.3; 1526 -8.6; 1678 -8.7; 1846 -8.5; 2031 -8.3; 2234 -7.4; 2457 -5.7; 2703 -4.2; 2973 -2.6; 3270 -0.8; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.3; 8482 -7.8; 9330 -7.0; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Shure SE535 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SE535 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 25 Hz    | 0.41 | 2.2 dB  |
| Peaking | 217 Hz   | 0.46 | -3.2 dB |
| Peaking | 1914 Hz  | 1.15 | -5.4 dB |
| Peaking | 4294 Hz  | 0.61 | 8.1 dB  |
| Peaking | 8600 Hz  | 1.97 | -4.8 dB |
| Peaking | 3350 Hz  | 4.68 | 1.4 dB  |
| Peaking | 4162 Hz  | 1.46 | -0.9 dB |
| Peaking | 6195 Hz  | 5.84 | 1.7 dB  |
| Peaking | 13531 Hz | 1.71 | -0.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.2 dB  |
| Peaking | 62 Hz    | 1.41 | 0.3 dB  |
| Peaking | 125 Hz   | 1.41 | -1.8 dB |
| Peaking | 250 Hz   | 1.41 | -2.8 dB |
| Peaking | 500 Hz   | 1.41 | -1.2 dB |
| Peaking | 1000 Hz  | 1.41 | -0.6 dB |
| Peaking | 2000 Hz  | 1.41 | -3.2 dB |
| Peaking | 4000 Hz  | 1.41 | 8.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.3 dB |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Shure%20SE535/Shure%20SE535.png)