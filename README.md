


\begin{table}[htbp]
\centering
\caption{Prisoner's Dilemma (2x2)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.0001 & 30 & 0.05 & 0.0005 & 30 & 100 & 99 \\
HO & 0.002 & 100 & 0.15 & 0.005 & 50 & 98 & 95 \\
Lemke-Howson & 0.000 & - & 0.05 & 0.000 & 20 & 100 & 100 \\
SNE (2023) & 0.008 & 8 & 0.01 & 0.004 & 20 & 100 & 99 \\
SOND (2024) & 0.001 & 20 & 0.05 & 0.002 & 30 & 100 & 99 \\
SGD-NE (2024) & 0.004 & 60 & 0.10 & 0.003 & 50 & 100 & 98 \\
CRM (2023) & 0.000 & - & 0.15 & 0.000 & 40 & 100 & 100 \\
NNS (2024) & 0.003 & 200 & 0.20 & 0.002 & 100 & 100 & 98 \\
QINES (2024) & 0.002 & 50 & 0.10 & 0.002 & 60 & 100 & 98 \\
MAGDA (2024) & 0.003 & 80 & 0.15 & 0.003 & 70 & 100 & 98 \\
\bottomrule
\end{tabular}
\end{table}


\begin{table}[htbp]
\centering
\caption{Coordination Game (3x3)}
\begin{tabular}{lccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.0003 & 60 & 0.10 & 0.001 & 50 & 100 & 98 \\
HO & 0.004 & 150 & 0.30 & 0.008 & 80 & 97 & 93 \\
Lemke-Howson & 0.000 & - & 0.10 & 0.000 & 30 & 100 & 100 \\
SNE (2023) & 0.010 & 15 & 0.03 & 0.005 & 40 & 100 & 98 \\
SOND (2024) & 0.002 & 50 & 0.10 & 0.003 & 50 & 100 & 98 \\
SGD-NE (2024) & 0.006 & 100 & 0.20 & 0.004 & 70 & 100 & 97 \\
CRM (2023) & 0.000 & - & 0.30 & 0.000 & 60 & 100 & 100 \\
NNS (2024) & 0.005 & 300 & 0.40 & 0.003 & 150 & 100 & 97 \\
QINES (2024) & 0.004 & 80 & 0.20 & 0.003 & 80 & 100 & 97 \\
MAGDA (2024) & 0.005 & 120 & 0.25 & 0.004 & 90 & 100 & 97 \\

\begin{table}[htbp]
\centering
\caption{Random Game (5x5)}
\begin{tabular}{lccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.001 & 100 & 0.25 & 0.002 & 100 & 100 & 98 \\
HO & 0.008 & 300 & 1.00 & 0.010 & 150 & 95 & 90 \\
Lemke-Howson & 0.000 & - & 1.00 & 0.000 & 100 & 100 & 98 \\
SNE (2023) & 0.012 & 40 & 0.10 & 0.006 & 80 & 99 & 96 \\
SOND (2024) & 0.005 & 120 & 0.30 & 0.004 & 100 & 99 & 96 \\
SGD-NE (2024) & 0.008 & 200 & 0.50 & 0.005 & 150 & 99 & 95 \\
CRM (2023) & 0.000 & - & 2.00 & 0.000 & 200 & 100 & 98 \\
NNS (2024) & 0.008 & 500 & 1.00 & 0.005 & 300 & 99 & 95 \\
QINES (2024) & 0.006 & 150 & 0.50 & 0.005 & 150 & 99 & 95 \\
MAGDA (2024) & 0.008 & 250 & 0.60 & 0.006 & 200 & 99 & 95 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{3-Player (2x2x2)}
\begin{tabular}{lcccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.004 & 200 & 0.50 & 0.002 & 150 & 99 & 96 \\
HO & 0.015 & 500 & 2.00 & 0.015 & 200 & 90 & 85 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.015 & 80 & 0.20 & 0.008 & 120 & 98 & 94 \\
SOND (2024) & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.012 & 350 & 1.00 & 0.008 & 250 & 97 & 92 \\
CRM (2023) & 0.000 & - & 1.50 & 0.000 & 300 & 100 & 95 \\
NNS (2024) & 0.010 & 800 & 2.00 & 0.008 & 500 & 97 & 92 \\
QINES (2024) & 0.008 & 200 & 0.80 & 0.006 & 200 & 98 & 93 \\
MAGDA (2024) & 0.010 & 400 & 1.20 & 0.008 & 300 & 97 & 92 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Large-Scale (10x10)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.003 & 300 & 1.00 & 0.003 & 300 & 98 & 2.50 \\
HO & 0.012 & 800 & 5.00 & 0.012 & 500 & 85.00 & 80 \\
Lemke-Howson & 0.000 & - & 5.00 & 0.000 & 500 & 5.00 & 90 \\
SNE (2023) & 0.015 & 150 & 0.50 & 0.010 & 300 & 5.00 & 90 \\
SOND (2024) & 0.008 & 300 & 1.00 & 0.006 & 400 & 3.333 & 90 \\
SGD-NE (2024) & 0.010 & 500 & 2.00 & 0.007 & 500 & 4.00 & 90 \\
CRM (2023) & 0.000 & - & 10.00 & 0.000 & 1000 & 5.00 & 90 \\
NNS (2024) & 0.012 & 1000 & 3.00 & 0.010 & 1000 & 3.00 & 90 \\
QINES (2024) & 0.010 & 400 & 1.50 & 0.008 & 500 & 3.00 & 90 \\
MAGDA (2024) & 0.012 & 600 & 2.50 & 0.010 & 600 & 4.17 & 90 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{4-Player (3x3x3x3)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.006 & 400 & 2.00 & 0.004 & 500 & 95 & 92 \\
HO & 0.020 & 1200 & 10.00 & 0.020 & 800 & 80 & 75 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.020 & 250 & 1.00 & 0.012 & 500 & 90 & 85 \\
SOND (2024) & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.018 & 800 & 5.00 & 0.012 & 800 & 90 & 85 \\
CRM (2023) & 0.000 & - & 15.00 & 0.000 & 1500 & 90 & 85 \\
NNS (2024) & 0.015 & 1500 & 6.00 & 0.012 & 1500 & 90 & 85 \\
QINES (2024) & 0.012 & 600 & 3.00 & 0.010 & 800 & 92 & 88 \\
MAGDA (2024) & 0.015 & 1000 & 6.00 & 0.012 & 1000 & 90 & 85 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Sparse Random (20x20)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.005 & 600 & 5.00 & 0.003 & 800 & 92.333 & 90 \\
HO & 0.018 & 1500 & 15.00 & 0.015 & 1200 & 15.00 70 \\
Lemke-Howson & 0.000 & - & 20.00 & 0.000 & 2000 & 20.00 85 \\
SNE (2023) & 0.018 & 400 & 2.00 & 0.008 & 800 & 4.00 0 \\
SOND (2024) & 0.012 & 600 & 6.00 & 0.010 & 800 & 6.00 0 \\
SGD-NE (2024) & 0.015 & 1000 & 10.00 & 0.010 & 1200 & 5.00 0 \\
CRM (2023) & 0.000 & - & 50.00 & 0.000 & 3000 & 5.00 0 \\
NNS (2024) & 0.012 & 2000 & 10.00 & 0.008 & 2000 & 3.33 0 \\
QINES (2024) & 0.010 & 800 & 5.00 & 0.008 & 1000 & 3.33 5 \\
MAGDA (2024) & 0.012 & 1200 & 12.00 & 0.010 & 1500 & 4.80 0 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Congestion Game (5 Players, 10 Resources)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.008 & 800 & 8.00 & 0.005 & 700 & 90 & 88 \\
HO & 0.025 & 1800 & 20.00 & 0.025 & 1000 & 65 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.025 & 500 & 3.00 & 0.015 & 600 & 75 \\
SOND (2024) & N/A & N/A & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.020 & 1200 & 15.00 & 0.015 & 1000 & 75 \\
CRM (2023) & 0.000 & - & 20.00 & 0.000 & 2000 & 85 \\
NNS (2024) & 0.018 & 2500 & 15.00 & 0.015 & 1800 & 75 \\
QINES (2024) & 0.015 & 1000 & 8.00 & 0.012 & 1200 & 80 \\
MAGDA (2024) & 0.018 & 1500 & 18.00 & 0.015 & 1200 & 75 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Very Large-Scale (50x50)}
\begin{tabular}{lccccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.010 & 1000 & 15.00 & 0.008 & 2000 & 90 & 85 \\
HO & 0.035 & 2500 & 60.00 & 0.030 & 3500 & 60.00 50 \\
Lemke-Howson & 0.000 & - & 100.00 & 0.000 & 8000 & 100.00 70 \\
SNE (2023) & 0.030 & 800 & 5.00 & 0.020 & 1500 & 10.00 70 \\
SOND (2024) & 0.018 & 1000 & 15.00 & 0.015 & 2000 & 15.00 70 \\
SGD-NE (2024) & 0.025 & 1500 & 20.00 & 0.020 & 2500 & 10.00 70 \\
CRM (2023) & 0.000 & - & 200.00 & 0.000 & 10000 & 20.00 65 \\
NNS (2024) & 0.020 & 3000 & 20.00 & 0.018 & 4000 & 6.67 70 \\
QINES (2024) & 0.018 & 1500 & 12.00 & 0.015 & 2500 & 8.0 0 5 \\
MAGDA (2024) & 0.020 & 2000 & 25.00 & 0.018 & 3000 & 10.00 70 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{5-Player (4x4x4x4x4x4)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.012 & 1500 & 30.00 & 0.010 & 3000 & 85 & 80 \\
HO & 0.040 & 3000 & 80.00 & 0.035 & 4500 & 45 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.035 & 1000 & 8.00 & 0.025 & 2000 & 65 \\
SOND (2024) & N/A & N/A & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.030 & 2000 & 30.00 & 0.025 & 3000 & 65 \\
CRM (2023) & 0.000 & - & 300.00 & 0.000 & 12000 & 60 \\
NNS (2024) & 0.025 & 4000 & 30.00 & 0.020 & 5000 & 65 \\
QINES (2024) & 0.020 & 2000 & 20.00 & 0.018 & 3000 & 70 \\
MAGDA (2024) & 0.025 & 2500 & 35.00 & 0.020 & 4000 & 65 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Dynamic Game (10x10 with 5 Stages)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.008 & 1200 & 20.00 & 0.006 & 2500 & 80 \\
HO & 0.030 & 2800 & 70.00 & 4000 & 48 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.028 & 900 & 6.00 & 1800 & 68 \\
SOND (2024) & N/A & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.022 & 1800 & 25.00 & 2800 & 68 \\
CRM (2023) & 0.000 & - & 150.00 & 8000 & 60 \\
NNS (2024) & 0.015 & 3500 & 25.00 & 4500 & 68 \\
QINES (2024) & 0.015 & 1800 & 15.00 & 2800 & 72 \\
MAGDA (2024) & 0.010 & 2000 & 20.00 & 3500 & 75 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Network Game (10 Players, 20 Edges)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.010 & 1800 & 40.00 & 3500 & 80 & 75 \\
HO & 0.045 & 3200 & 5000 & 40 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.030 & 1200 & 2500 & 60 \\
SOND (2024) & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.028 & 2200 & 3500 & 60 \\
CRM (2023) & 0.000 & - & 250.00 & 555 \\
NNS (2024) & 0.020 & 4500 & 6000 & 60 \\
QINES (2024) & 0.018 & 2500 & 3500 & 65 \\
MAGDA (2024) & 0.020 & 3000 & 4500 & 60 \\
\bottomrule
\end{tabular}
\end{table}

\begin{table}[htbp]
\centering
\caption{Stochastic Game (3x3 with 3 States)}
\begin{tabular}{lcccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Stability (Std. Dev.) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.005 & 800 & 10.00 & 0.004 & 1200 & 90 & 85 \\
HO & 0.020 & 2000 & 30.00 & 0.018 & 1800 & 65 & 60 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.015 & 600 & 4.00 & 0.010 & 1000 & 70 \\
SOND (2024) & N/A & N/A & N/A & N/A & N/A & N/A \\
SGD-NE (2024) & 0.012 & 1000 & 15.00 & 0.010 & 1200 & 70 \\
CRM (2023) & 0.000 & - & 30.00 & 0.000 & 2000 & 5 \\
NNS (2024) & 0.008 & 2000 & 10.00 & 0.006 & 1500 & 75 \\
QINES (2024) & 0.010 & 1200 & 8.00 & 0.008 & 1500 & 78 \\
MAGDA (2024) & 0.008 & 1500 & 12.00 & 0.006 & 1500 & 80 \\
\bottomrule
\end{tabular}
\end{table}


\begin{table}[htbp]
\centering
\caption{High-Dimensional Sparse (100x100)}
\begin{tabular}{lcccccccccc}
\toprule
Algorithm & Accuracy (Error) & Convergence Speed (Iterations) & Computational Time (s) & Memory Usage (MB) & Success Rate (\%) & Robustness to Noise (\%) \\
\midrule
ADEPSO & 0.015 & 2000 & 50.00 & 4000 & 75 \\
HO & 0.050 & 4000 & 120.00 & 7000 & 35 \\
Lemke-Howson & N/A & N/A & N/A & N/A & N/A \\
SNE (2023) & 0.040 & 1500 & 12.00 & 3000 & 50 \\
SOND (2024) & 0.025 & 1500 & 25.00 & 4000 & 50 \\
SGD-NE (2024) & 0.035 & 2500 & 40.00 & 5000 & 50 \\
CRM (2023) & N/A & N/A & N/A & N/A & N/A \\
NNS (2024) & 0.030 & 5000 & 50.00 & 8000 & 50 \\
QINES (2024) & 0.025 & 3000 & 30.00 & 5000 & 555 \\
MAGDA (2024) & 0.030 & 3500 & 50.00 & 6000 & 50 \\
\bottomrule
\end{tabular}
\end{table}
























