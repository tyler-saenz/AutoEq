# NAD Viso HP70
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.9; 25 -1.6; 28 -3.0; 31 -4.1; 34 -5.0; 37 -5.6; 41 -6.1; 45 -6.5; 49 -6.8; 54 -7.3; 60 -7.8; 66 -8.3; 72 -8.5; 79 -8.8; 87 -9.2; 96 -9.4; 106 -9.3; 116 -8.9; 128 -8.1; 141 -7.1; 155 -7.1; 170 -7.5; 187 -7.5; 206 -7.1; 227 -6.4; 249 -5.7; 274 -4.9; 302 -4.4; 332 -4.8; 365 -5.0; 402 -5.2; 442 -5.6; 486 -6.3; 535 -6.8; 588 -6.6; 647 -6.8; 712 -7.2; 783 -6.7; 861 -6.7; 947 -6.9; 1042 -7.0; 1146 -7.2; 1261 -7.8; 1387 -6.9; 1526 -5.6; 1678 -4.5; 1846 -4.1; 2031 -4.0; 2234 -3.8; 2457 -4.1; 2703 -4.6; 2973 -5.2; 3270 -6.1; 3597 -7.8; 3957 -7.4; 4353 -9.9; 4788 -9.6; 5267 -8.3; 5793 -8.3; 6373 -8.9; 7010 -10.1; 7711 -7.9; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -7.5; 13660 -11.4; 15026 -8.8; 16529 -7.0; 18182 -7.3; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`NAD Viso HP70 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `NAD Viso HP70 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.8dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 22 Hz    | 1.8  | 6.0 dB  |
| Peaking | 90 Hz    | 1.56 | -3.2 dB |
| Peaking | 5760 Hz  | 1.8  | -2.8 dB |
| Peaking | 13836 Hz | 4.02 | -5.3 dB |
| Peaking | 18067 Hz | 2.18 | -0.7 dB |
| Peaking | 315 Hz   | 2.9  | 2.4 dB  |
| Peaking | 2227 Hz  | 2.26 | 3.1 dB  |
| Peaking | 4527 Hz  | 3.62 | -3.4 dB |
| Peaking | 6570 Hz  | 1.31 | 3.0 dB  |
| Peaking | 6897 Hz  | 4.07 | -4.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.9 dB  |
| Peaking | 62 Hz    | 1.41 | -2.6 dB |
| Peaking | 125 Hz   | 1.41 | -2.2 dB |
| Peaking | 250 Hz   | 1.41 | 1.6 dB  |
| Peaking | 500 Hz   | 1.41 | 0.6 dB  |
| Peaking | 1000 Hz  | 1.41 | -1.8 dB |
| Peaking | 2000 Hz  | 1.41 | 3.7 dB  |
| Peaking | 4000 Hz  | 1.41 | -2.3 dB |
| Peaking | 8000 Hz  | 1.41 | -1.2 dB |
| Peaking | 16000 Hz | 1.41 | -2.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/NAD%20Viso%20HP70/NAD%20Viso%20HP70.png)