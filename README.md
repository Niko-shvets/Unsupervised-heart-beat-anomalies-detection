# Unsupervised-heart-beat-anomalies-detection

This Repositiry consist from 2 main part, Heart beat anomalies detection(Arrhythmia) and blood pressure estimation

## 1) Heart Beat Anomalies Detection

We propose    a    new    unsupervised    and    non-parametric  method  to  detect  change  points  in electrocardiography.  The detection relies on  optimal  transport  theory  combined  with  topological analysis and the bootstrap procedure.  The algorithm is designed to detect changes in virtually any harmonic or a partially harmonic signal and is verified on ECG data streams.  We successfully find abnormal or irregular cardiac cycles in the waveforms for the six of the most frequent types of clinical arrhythmias using a single algorithm. Our unsupervised approach reaches the level of performance of the supervised state-of-the-art techniques.  We provide conceptual justification for  the efficiency of the method.


\begin{figure}[h]
     \centering
     \includegraphics[width=\columnwidth]{Fig1-pipeline.pdf} 
     \caption{Pipeline of the proposed algorithm. Here, $\tau$ is the center of the second sliding window, $2h$ is the size of the second sliding window, $W_p^p$ -- Wasserstein distance, $\big\{\mu_l^b(t)$, $\mu_r^b(t)\big\}$ are the bootstrap measures in the left and the right parts of the second sliding window.}
     \label{fig:pipeline}
     \end{figure}
