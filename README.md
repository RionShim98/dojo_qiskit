# dojo_qiskit
Quantum Native Dojo (https://dojo.qulacs.org/ja/latest/index.html) の第2、4～8章のそれぞれから実装コードを1組づつ選び、それらをQiskitで実装しなおしました。
使う理論(数学)、基本的なコードの構造はDojoにあがっているものと同じで、Qulacsを使われている部分を全てQiskitに置き換えました。以下、各ipynbファイルの説明です。google colabであればそのまま実行可能になっています。その際は各コードの一番上の
"""
!pip install qiskit
"""
のような部分の実行が必要です。

## 2_3_QFT.ipynb
Quantum Native Dojo 第2章の「2.3. 量子フーリエ変換」のセクションをQiskit実装したものです。このファイルのみ、実機(IBM Q)を使ったのでIBM experienceのアカウントが必要となります。

## 4_2_trotter_dynamics.ipynb
Quantum Native Dojo 第4章の「4.2. トロッター分解を用いた量子シミュレーション」の「量子ダイナミクスの実装(3)：厳密解との比較」のセクションをQiskit実装したものです。

## 5_2_QCL.ipynb
Quantum Native Dojo 第5章の「5.2. Quantum Circuit Learning」のセクションをQiskit実装したものです。

## 5_3_QAOA.ipynb
Quantum Native Dojo 第5章の「5.2. Quantum Circuit Learning」のセクションをQiskit実装したものです。

## 6_2_VQE.ipynb
Quantum Native Dojo 第6章の「6.2. Qulacsを用いたvariational quantum eigensolver (VQE)の実装」のセクションをQiskit実装したものです。

## 7_1_phase_estimation.ipynb
Quantum Native Dojo 第5章の「5.2. Quantum Circuit Learning」のセクションをQiskit実装したものです。
