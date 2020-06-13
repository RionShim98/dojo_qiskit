# dojo_qiskit
Quantum Native Dojo (https://dojo.qulacs.org/ja/latest/index.html) の第2、4～8章のそれぞれから実装コードを選び、それらをQiskitで再現

Qiskitでは
\begin{align}
&R_X(\theta)=e^{-i(\theta/2)X}=\cos(\theta/2)I-i\sin(\theta/2)X=
\left[
\begin{array}{cc}
\cos(\theta/2) &-i\sin(\theta/2)  \\
-i\sin(\theta/2) & \cos(\theta/2)
\end{array}
\right]\notag\\
&R_Y(\theta)=e^{-i(\theta/2)Y}=\cos(\theta/2)I-i\sin(\theta/2)Y=
\left[
\begin{array}{cc}
\cos(\theta/2) &-\sin(\theta/2)  \\
\sin(\theta/2) & \cos(\theta/2)
\end{array}
\right]\notag\\
\end{align}
である。$R_z(\theta)$に関しては理論上は
\begin{align}
&R_Z(\theta)=e^{-i(\theta/2)Z}=\cos(\theta/2)I-i\sin(\theta/2)Z=\left[
\begin{array}{cc}
e^{-i\theta/2} &0  \\
0 & e^{i\theta/2}
\end{array}
\right]=
e^{-i\theta/2}\left[
\begin{array}{cc}
1 &0  \\
0 & e^{i\theta}
\end{array}
\right]
\end{align}
であるが、Qiskitでは絶対位相を無視して
\begin{equation}
R_z(\theta)=\left[
\begin{array}{cc}
1 &0  \\
0 & e^{i\theta}
\end{array}
\right]
\end{equation}
としている。
