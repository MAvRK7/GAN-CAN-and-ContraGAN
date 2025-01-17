# Adversarial Networks for Synthetic Data Generation: A Comparative Study of GANs, Conditional Adversarial Networks, and Contrastive Adversarial Networks in Predicting Astronomical B-V Indices

This study evaluates the performance of three adversarial frameworks—Generative Adversarial Networks (GANs), Conditional GANs, and Contrastive GANs—in generating synthetic data to predict the B-V (colour index) value in astronomical datasets. The models were assessed using predictive accuracy metrics (Mean Squared Error and R²), clustering quality scores (Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score), and statistical alignment measures (Wasserstein Distance and Kolmogorov-Smirnov Statistic).
The Contrastive GAN achieved the best results, with an MSE of 0.1250, R² of 0.7320, Silhouette Score of 0.3723, Calinski-Harabasz Score of 272.0709, and Davies-Bouldin Score of 1.0491, significantly outperforming the GAN and Conditional GAN. Conditional GANs also demonstrated robust performance, benefiting from conditioning on input features. In comparison, standard GANs exhibited the weakest results, with lower predictive accuracy and clustering quality. The findings highlight the advantages of incorporating contrastive learning and conditional generation into adversarial frameworks, paving the way for improved synthetic data generation in scientific and industrial applications
