# Philips Fidelio S2 2013
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -5.1; 23 -5.3; 25 -5.5; 28 -5.8; 31 -5.9; 34 -6.1; 37 -6.2; 41 -6.4; 45 -6.5; 49 -6.6; 54 -6.8; 60 -7.0; 66 -7.2; 72 -7.4; 79 -7.6; 87 -7.8; 96 -8.1; 106 -8.1; 116 -8.0; 128 -8.1; 141 -8.0; 155 -8.0; 170 -7.8; 187 -7.6; 206 -7.4; 227 -7.0; 249 -6.8; 274 -6.4; 302 -6.1; 332 -5.7; 365 -5.3; 402 -5.1; 442 -4.7; 486 -4.5; 535 -4.3; 588 -3.7; 647 -3.7; 712 -3.6; 783 -3.4; 861 -3.8; 947 -4.1; 1042 -4.6; 1146 -4.9; 1261 -5.3; 1387 -5.9; 1526 -6.5; 1678 -6.8; 1846 -6.5; 2031 -5.9; 2234 -5.0; 2457 -3.7; 2703 -2.6; 2973 -1.2; 3270 -0.5; 3597 -1.1; 3957 -3.5; 4353 -7.7; 4788 -10.0; 5267 -8.2; 5793 -5.2; 6373 -3.7; 7010 -3.2; 7711 -5.0; 8482 -5.2; 9330 -5.3; 10263 -5.3; 11289 -5.3; 12418 -5.3; 13660 -5.3; 15026 -5.3; 16529 -5.3; 18182 -5.3; 20000 -5.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Philips Fidelio S2 2013 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Philips Fidelio S2 2013 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.4dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 88 Hz   | 0.88 | -2.5 dB |
| Peaking | 172 Hz  | 1.72 | -1.8 dB |
| Peaking | 3376 Hz | 2.74 | 6.1 dB  |
| Peaking | 4794 Hz | 3.41 | -6.5 dB |
| Peaking | 6476 Hz | 3.64 | 2.8 dB  |
| Peaking | 266 Hz  | 2.33 | -0.6 dB |
| Peaking | 734 Hz  | 1.1  | 2.0 dB  |
| Peaking | 1697 Hz | 1.83 | -2.2 dB |
| Peaking | 2651 Hz | 4.39 | 1.2 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-1.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -0.3 dB |
| Peaking | 62 Hz    | 1.41 | -1.6 dB |
| Peaking | 125 Hz   | 1.41 | -2.7 dB |
| Peaking | 250 Hz   | 1.41 | -1.5 dB |
| Peaking | 500 Hz   | 1.41 | 1.5 dB  |
| Peaking | 1000 Hz  | 1.41 | 0.6 dB  |
| Peaking | 2000 Hz  | 1.41 | -0.3 dB |
| Peaking | 4000 Hz  | 1.41 | 1.1 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.1 dB |
| Peaking | 16000 Hz | 1.41 | -0.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Philips%20Fidelio%20S2%202013/Philips%20Fidelio%20S2%202013.png)