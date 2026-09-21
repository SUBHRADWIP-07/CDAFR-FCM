PROJECT TITLE: CDAFR-FCM (Consensus-Driven Adaptive Fuzzifier with Robustness-Enhanced Fuzzy C-Means)

1. OVERVIEW

CDAFR-FCM is an enhanced fuzzy clustering framework that extends the traditional Fuzzy C-Means (FCM) algorithm through a consensus-driven adaptive fuzzifier. The proposed method estimates the fuzzifier parameter by combining four metaheuristic optimization techniques: Particle Swarm Optimization (PSO), Grey Wolf Optimizer (GWO), Whale Optimization Algorithm (WOA), and Genetic Algorithm (GA). The framework is designed to improve clustering quality, membership stability, and robustness against noisy and complex real-world data.

The project provides the complete implementation, experimental notebooks, datasets, evaluation results, and visualization outputs required to reproduce the clustering experiments. The adaptive fuzzifier is determined according to dataset characteristics, while multiple clustering validity measures are used to assess cluster compactness, separation, and membership quality. The framework is structured to support further research, comparative studies, and practical clustering applications.

2. KEY FEATURES

		• Consensus-driven adaptive fuzzifier optimization
		• Multi-metaheuristic integration (PSO + GWO + WOA + GA)
		• Robust clustering for noisy and complex datasets
		• Improved cluster compactness and separation
		• Comprehensive evaluation using multiple clustering validity metrics
		• Repeated-run experimental analysis for stability assessment
		• Statistical comparison and ablation analysis
		• 3D and interactive clustering visualization support

3. FILES

DATASET
		→ Contains all datasets used for clustering experiments, comparative evaluation, and performance analysis.

CDAFR-FCM new update CODE.ipynb
		→ Main implementation notebook containing the CDAFR-FCM algorithm, experimental procedures, clustering evaluation, and visualization code. The notebook can be executed using Jupyter Notebook or Google Colab.

Kolkata_Pro_NEW_DEMO.html
		→ Interactive real-time clustering visualization based on Kolkata air-pollution data. The HTML file provides an interactive map for visualizing pollution-related clustering results.

IMPORTANT:
	Open the HTML file **only in a web browser** such as Chrome or Microsoft Edge.
		Do not open the HTML file in Microsoft Word (.docx).
