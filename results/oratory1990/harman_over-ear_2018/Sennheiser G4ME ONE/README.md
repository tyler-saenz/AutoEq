# Sennheiser G4ME ONE
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.8; 37 -1.2; 41 -1.8; 45 -2.4; 49 -3.0; 54 -3.5; 60 -4.0; 66 -4.7; 72 -4.8; 79 -4.4; 87 -6.0; 96 -7.1; 106 -7.8; 116 -8.1; 128 -8.7; 141 -9.3; 155 -9.5; 170 -9.6; 187 -9.6; 206 -9.7; 227 -9.6; 249 -9.4; 274 -9.2; 302 -9.0; 332 -8.9; 365 -8.6; 402 -8.5; 442 -8.4; 486 -8.2; 535 -8.1; 588 -7.8; 647 -7.6; 712 -7.7; 783 -7.5; 861 -7.5; 947 -8.0; 1042 -8.1; 1146 -7.9; 1261 -7.3; 1387 -6.0; 1526 -4.7; 1678 -3.9; 1846 -3.9; 2031 -4.8; 2234 -5.9; 2457 -6.9; 2703 -7.0; 2973 -6.1; 3270 -4.7; 3597 -3.2; 3957 -2.0; 4353 -3.3; 4788 -7.3; 5267 -9.6; 5793 -8.4; 6373 -2.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -8.9; 16529 -14.6; 18182 -16.7; 20000 -24.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser G4ME ONE GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser G4ME ONE ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.2dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 29 Hz   | 0.31 | 6.9 dB  |
| Peaking | 151 Hz  | 0.38 | -4.7 dB |
| Peaking | 1753 Hz | 4.26 | 3.3 dB  |
| Peaking | 3938 Hz | 5.89 | 5.2 dB  |
| Peaking | 6570 Hz | 9.9  | 4.9 dB  |
| Peaking | 142 Hz  | 4.67 | -0.4 dB |
| Peaking | 1084 Hz | 3.42 | -1.5 dB |
| Peaking | 2604 Hz | 3.54 | -2.4 dB |
| Peaking | 2924 Hz | 0.97 | 1.5 dB  |
| Peaking | 5382 Hz | 6.08 | -4.9 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.6 dB  |
| Peaking | 62 Hz    | 1.41 | 1.9 dB  |
| Peaking | 125 Hz   | 1.41 | -2.5 dB |
| Peaking | 250 Hz   | 1.41 | -2.8 dB |
| Peaking | 500 Hz   | 1.41 | -0.9 dB |
| Peaking | 1000 Hz  | 1.41 | -1.3 dB |
| Peaking | 2000 Hz  | 1.41 | 1.6 dB  |
| Peaking | 4000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.2 dB  |
| Peaking | 16000 Hz | 1.41 | -7.6 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Sennheiser%20G4ME%20ONE/Sennheiser%20G4ME%20ONE.png)