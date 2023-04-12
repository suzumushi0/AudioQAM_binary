# AudioQAM binary distribution.

![capture](https://user-images.githubusercontent.com/67182469/231406873-6dfc29a4-e58f-4209-bbd2-dc255718c289.png)

AudioQAM simultaneously modulates phase and amplitude of audio input, and as a result, creates unexpected sound.

Quadrature Amplitude Modulation (QAM) is widely used in digital communications. AudioQAM is derived from digital quadrature amplitude modulators and refined for audio processing. AudioQAM supports sine as well as triangle, square, and sawtooth waveforms for carrier waves.

In the case of the sine waveform carrier, AudioQAM is essentially equivalent to the phase shift network and thus works as the well-known Bode frequency shifter. In the other waveform cases, the output spectrum is the convolution of the carrier wave and audio input spectrums, therefore creating unknown sound.

AudioQAM is provided as a VST 3 plug-in for digital audio workstations and supports any sampling rates. OS environment is 64bit Windows 10 and later. Refer to the following document for details.

https://suzumushi0.hatenablog.com/entry/AQ/AQ_EN

AudioQAM はオーディオ入力の位相と振幅を同時に変調し，想定外のサウンドを生成する．

直交振幅変調 (Quadrature Amplitude Modulation: QAM) はディジタル通信において広く使用されている．AudioQAM はディジタル直交振幅変調器から派生したもので，オーディオ処理用にリファインされている．AudioQAM は搬送波として正弦波だけでなく，三角波，矩形波，鋸歯状波をサポートしている．

搬送波が正弦波の場合，AudioQAM は位相シフトネットワーク (phase shift network) と本質的に等価となり，既存のボード周波数シフタ (Bode frequency shifter) として動作する．その他の搬送波の場合，出力の周波数スペクトルは，搬送波とオーディオ入力のスペクトルの畳み込みとなり，未知のサウンドを生成する．

AudioQAM はディジタルオーディオワークステーションの VST 3 plug-in として提供され，全てのサンプリングレートをサポートしている．また，OS 環境は 64 bit の Windows 10 以降となる．詳細は以下のドキュメントを参照．

https://suzumushi0.hatenablog.com/entry/AQ/AQ_JP

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a> at no charge.

<img width="100" src="https://user-images.githubusercontent.com/67182469/130337395-b8ab38cd-e66e-4056-b441-49d33337410e.png">
VST is a registered trademark of Steinberg Media Technologies GmbH.
