# dojo_qiskit
Quantum Native Dojo (https://dojo.qulacs.org/ja/latest/index.html) の第2、4～8章のそれぞれから実装コードを1組ずつ選び(第5章からは2組)、それらをQiskitで実装しなおしてみました。
使う理論(数学)、基本的なコードの構造はDojoにあがっているものと同じで、Qulacsを使われている部分を全てQiskitに置き換えました。以下、各ipynbファイルの説明です。google colabであればそのまま実行可能になっています。ただし、その際は各コードの一番上の
```
!pip install qiskit
```
のような部分の実行が必要です。

## 2_3_QFT.ipynb
Quantum Native Dojo 第2章の「2.3. 量子フーリエ変換」のセクションをQiskitで実装したものです。このファイルでは、実機(IBM Q)も使ったのでIBM experienceのアカウントが必要となります。

## 4_2_trotter_dynamics.ipynb
Quantum Native Dojo 第4章の「4.2. トロッター分解を用いた量子シミュレーション」の「量子ダイナミクスの実装(3)：厳密解との比較」のセクションをQiskitで実装したものです。

## 5_2_QCL.ipynb
Quantum Native Dojo 第5章の「5.2. Quantum Circuit Learning」のセクションをQiskitで実装したものです。

## 5_3_QAOA.ipynb
Quantum Native Dojo 第5章の「5.2. Quantum Circuit Learning」のセクションをQiskitで実装したものです。このファイルでは、実機(IBM Q)も使ったのでIBM experienceのアカウントが必要となります。

## 6_2_VQE.ipynb
Quantum Native Dojo 第6章の「6.2. Qulacsを用いたvariational quantum eigensolver (VQE)の実装」のセクションをQiskitで実装したものです。

## 7_1_phase_estimation.ipynb
Quantum Native Dojo 第7章の「7-1. 量子位相推定アルゴリズム詳説：水素分子への応用を例として」のセクションをQiskitで実装したものです。

## 8_2_Grovers_algorithm.ipynb
Quantum Native Dojo 第8章の「8.2. グローバーのアルゴリズム」のセクションをQiskitで実装したものです。

## 参考文献
Quantum Native Dojo 
https://dojo.qulacs.org/ja/latest/index.html
