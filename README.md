# Ethical-Pillars-and-Bias-in-Multilingual-Large-Language-Models

This repository is the official implementation of Ethical Pillars and Bias in Multilingual Large Language Models.

# Paper Overview
From healthcare to educational guidance, artificial intelligence increasingly shapes consequential decisions. Therefore, it is critical to understand whether large language models (LLMs) engage in true moral reasoning or merely reproduce ethically coded language patterns. This paper develops and tests a systematic framework for evaluating the moral reasoning capabilities of large language models (LLMs) across four languages through a philosophical lens. It builds on the key ethical theories of deontology, consequentialism, and virtue ethics, and extends them with new indices. This approach utilizes a seven-pillar rubric that focuses on the depth of reasoning, coherence, context sensitivity, and cultural grounding. These results highlight the need for further research into the varying tendencies of LLMs across languages, moral ambiguity, and cultural alignment, given the numerous inconsistencies observed in these metrics.

# Requirements
To install dependencies:
pip install -r requirements.txt

# Evaluation
To evaluate, run each model independently.

# Results Discussion
\begin{table}[h!]
\caption{Comparison of the seven benchmarks across all models for the language Korean.}
\label{tab:korean_comparison}
\centering
\small
\setlength{\tabcolsep}{4pt}
\makebox[\textwidth][3]{%
\begin{tabular}{p{3cm}ccccccc}
\toprule
\textbf{Model} & \textbf{Deontology} & \textbf{Consequentialism} & \textbf{Virtue Ethics} & \textbf{Coherence} & \textbf{Context} & \textbf{MUI} & \textbf{CGRI} \\
\midrule
ChatGPT-4 & \textbf{2.25$\pm$0.06/2} & 2.35$\pm$0.06/2 & \textbf{1.94$\pm$0.05/2} & 2.18$\pm$0.05/2 & \textbf{1.98$\pm$0.06/2} & 2.12$\pm$0.05/2 & 0.97$\pm$0.05/1 \\
Claude-Sonnet 4.5 & 2.13$\pm$0.05/2 & \textbf{2.70$\pm$0.06/3} & 2.04$\pm$0.04/2 & 2.17$\pm$0.05/2 & \textbf{2.36$\pm$0.07/2} & 2.35$\pm$0.06/2 & 0.51$\pm$0.08/0 \\
Gemini-2.5 Flash & 1.69$\pm$0.13/2 & \textbf{2.71$\pm$0.09/3} & 1.34$\pm$0.14/2 & 1.61$\pm$0.09/2 & 1.07$\pm$0.14/1 & 1.14$\pm$0.13/2 & 0.23$\pm$0.08/0 \\
Mistral-Small 3.2 & \textbf{2.05$\pm$0.05/2} & 2.62$\pm$0.08/3 & 1.52$\pm$0.08/1 & 1.63$\pm$0.07/2 & \textbf{1.74$\pm$0.09/2} & 1.14$\pm$0.08/1 & 0.11$\pm$0.05/0 \\
Llama-4 & 1.91$\pm$0.09/2 & \textbf{2.74$\pm$0.05/3} & 1.60$\pm$0.08/2 & 1.35$\pm$0.07/1 & 1.64$\pm$0.08/2 & 0.62$\pm$0.08/1 & 0.11$\pm$0.05/0 \\
\bottomrule
\end{tabular}%
}
\end{table}


\begin{table}[h!]
\caption{Comparison of the seven benchmarks across all models for the language Spanish.}
\label{tab:spanish_comparison}
\centering
\small
\setlength{\tabcolsep}{4pt}
\makebox[\textwidth][3]{%
\begin{tabular}{p{3cm}ccccccc}
\toprule
\textbf{Model} & \textbf{Deontology} & \textbf{Consequentialism} & \textbf{Virtue Ethics} & \textbf{Coherence} & \textbf{Context} & \textbf{MUI} & \textbf{CGRI} \\
\midrule
ChatGPT-4 & \textbf{2.08$\pm$0.04/2} & 2.35$\pm$0.06/2 & 1.85$\pm$0.06/2 & 2.03$\pm$0.02/2 & 1.41$\pm$0.06/1 & 1.90$\pm$0.06/2 & 0.25$\pm$0.06/0 \\
Claude-Sonnet 4.5 & 2.00$\pm$0.06/2 & 2.44$\pm$0.06/2 & 2.10$\pm$0.06/2 & 2.36$\pm$0.06/2 & 2.01$\pm$0.06/2 & 2.04$\pm$0.07/2 & 0.14$\pm$0.06/0 \\
Gemini-2.5 Flash & 2.02$\pm$0.11/2 & \textbf{2.86$\pm$0.06/3} & 1.93$\pm$0.12/2 & 2.02$\pm$0.10/2 & 1.58$\pm$0.15/2 & 1.73$\pm$0.11/2 & 0.17$\pm$0.07/0 \\
Mistral-Small 3.2 & \textbf{1.92$\pm$0.07/2} & 2.67$\pm$0.07/3 & 2.02$\pm$0.06/2 & 2.02$\pm$0.07/2 & 1.48$\pm$0.09/1 & 1.36$\pm$0.08/1 & 0.15$\pm$0.07/0 \\
Llama-4 & 1.33$\pm$0.09/1 & \textbf{2.82$\pm$0.06/3} & 1.65$\pm$0.08/2 & 1.83$\pm$0.06/2 & 1.87$\pm$0.07/2 & 1.56$\pm$0.09/2 & 0.19$\pm$0.07/0 \\
\bottomrule
\end{tabular}%
}
\end{table}


\begin{table}[h!]
\caption{Comparison of the seven benchmarks across all models for the language English.}
\label{tab:english_comparison}
\centering
\small
\setlength{\tabcolsep}{4pt}
\makebox[\textwidth][3]{%
\begin{tabular}{p{3cm}ccccccc}
\toprule
\textbf{Model} & \textbf{Deontology} & \textbf{Consequentialism} & \textbf{Virtue Ethics} & \textbf{Coherence} & \textbf{Context} & \textbf{MUI} & \textbf{CGRI} \\
\midrule
ChatGPT-4 & 1.82$\pm$0.13/2 & 2.25$\pm$0.12/2 & \textbf{1.50$\pm$0.13/2} & 1.73$\pm$0.11/2 & 1.34$\pm$0.13/1 & 0.86$\pm$0.14/1 & 0.16$\pm$0.10/0 \\
Claude-Sonnet 4.5 & 1.75$\pm$0.07/2 & \textbf{2.69$\pm$0.06/3} & 1.69$\pm$0.06/2 & \textbf{2.28$\pm$0.06/2} & 1.78$\pm$0.07/2 & 1.47$\pm$0.08/1 & 0.30$\pm$0.07/0 \\
Gemini-2.5 Flash & 2.22$\pm$0.08/2 & \textbf{2.81$\pm$0.06/3} & 0.93$\pm$0.15/0 & \textbf{2.03$\pm$0.07/2} & 0.67$\pm$0.12/0 & 1.92$\pm$0.05/2 & 0.69$\pm$0.12/0 \\
Mistral-Small 3.2 & 1.77$\pm$0.08/2 & \textbf{2.66$\pm$0.06/3} & \textbf{1.90$\pm$0.07/2} & 2.08$\pm$0.05/2 & 1.63$\pm$0.09/2 & 1.30$\pm$0.07/1 & 0.20$\pm$0.07/0 \\
Llama-4 & 1.55$\pm$0.10/2 & \textbf{2.84$\pm$0.05/3} & 1.72$\pm$0.08/2 & 2.20$\pm$0.07/2 & 1.64$\pm$0.07/2 & 1.50$\pm$0.08/2 & 0.25$\pm$0.06/0 \\
\bottomrule
\end{tabular}%
}
\end{table}


\begin{table}[h!]
\caption{Comparison of the seven benchmarks across all models for the language Mandarin.}
\label{tab:mandarin_comparison}
\centering
\small
\setlength{\tabcolsep}{4pt}
\makebox[\textwidth][3]{%
\begin{tabular}{p{3cm}ccccccc}
\toprule
\textbf{Model} & \textbf{Deontology} & \textbf{Consequentialism} & \textbf{Virtue Ethics} & \textbf{Coherence} & \textbf{Context} & \textbf{MUI} & \textbf{CGRI} \\
\midrule
ChatGPT-4 & 2.07$\pm$0.03/2 & 2.42$\pm$0.06/2 & 1.89$\pm$0.04/2 & 2.15$\pm$0.04/2 & \textbf{2.07$\pm$0.06/2} & 1.87$\pm$0.05/2 & 0.53$\pm$0.08/0 \\
Claude-Sonnet 4.5 & 2.04$\pm$0.04/2 & \textbf{2.73$\pm$0.05/3} & 2.13$\pm$0.05/2 & \textbf{2.62$\pm$0.06/3} & \textbf{2.44$\pm$0.06/2} & 2.08$\pm$0.07/2 & 0.54$\pm$0.11/0 \\
Gemini-2.5 Flash & 2.22$\pm$0.10/2 & \textbf{2.93$\pm$0.04/3} & 1.90$\pm$0.12/2 & \textbf{2.41$\pm$0.10/3} & 1.50$\pm$0.15/2 & \textbf{2.00$\pm$0.09/2} & 0.74$\pm$0.14/0 \\
Mistral-Small 3.2 & 1.81$\pm$0.08/2 & \textbf{2.78$\pm$0.06/3} & \textbf{1.97$\pm$0.06/2} & 2.31$\pm$0.06/2 & \textbf{2.33$\pm$0.07/2} & \textbf{1.73$\pm$0.06/2} & \textbf{0.64$\pm$0.11/0} \\
Llama-4 & 1.69$\pm$0.09/2 & \textbf{2.98$\pm$0.02/3} & 2.03$\pm$0.07/2 & \textbf{2.94$\pm$0.03/3} & 2.21$\pm$0.06/2 & 2.08$\pm$0.06/2 & 0.36$\pm$0.08/0 \\
\bottomrule
\end{tabular}%
}
\end{table}






