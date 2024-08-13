# Navigating Real-World Data through Advanced Probability and Statistics

## Business Problem Statement
The research project aims to apply probabilistic and statistical techniques acquired during the course to address specific questions of interest across various domains such as finance, business, psychology, sociology, natural science, medicine, public policy, sports, and law. The goal is to cultivate creative thinking and foster independent analytical skills through the exploration of personally intriguing questions using real-world data.

## Methodology
The methodology employed in this project involves several key steps:

1. **Simulation**: Continuous and discrete random variables are simulated using techniques like inverse transform sampling and acceptance-rejection sampling.
2. **Statistical Analysis**: Measures such as mean, variance, standard deviation, quantiles, skewness, and kurtosis are calculated to understand the characteristics of the distributions.
3. **Visualization**: Histograms, density plots, and box plots are used to visualize the distributions and identify outliers.
4. **Central Limit Theorem Verification**: The Central Limit Theorem is verified for both continuous and discrete distributions by examining the distribution of sample means.
5. **Outlier Detection**: The Interquartile Range (IQR) method and Z-Score method are employed to identify potential outliers in the datasets.
6. **Probability Calculations**: Probabilities related to specific ranges or thresholds are calculated using the cumulative distribution function (CDF) of the distributions.
7. **Markov Chains**: Markov Chains are simulated to model transitions between states and recurrent events. Ergodicity is explored by comparing time-averaged behavior with state probabilities.
8. **Variance Reduction Techniques**: Importance sampling and control variates are investigated to enhance simulation efficiency.
9. **Combinatorial Analysis**: Practical simulations are conducted to address combinatorial problems and provide tangible applications of probability principles.
10. **Comparative Analysis**: Various simulation methods are compared to assess their strengths and limitations.

## Key Findings from EDA
During the exploratory data analysis (EDA), several key findings were observed:

- The continuous random variable (gamma distribution) exhibited right-skewness and the presence of outliers.
- The discrete random variable (negative binomial distribution) showed peaks and deviated from a normal distribution.
- The Central Limit Theorem was verified for both continuous and discrete distributions, with the distribution of sample means approximating a normal distribution as the sample size increased.
- Outlier detection methods, such as the IQR method and Z-Score method, identified potential outliers in the datasets.
- Markov Chain simulations demonstrated the randomness of transitions between states and the convergence of time-averaged behavior to steady-state probabilities.
- Variance reduction techniques, such as importance sampling and control variates, were explored to improve simulation efficiency.
- Combinatorial analysis provided insights into the probabilities of specific events in practical scenarios.

## Model Implementation and Results
Various models and techniques were implemented throughout the project to address different aspects of the data analysis:

1. **Markov Chain Simulation**: Markov Chains were simulated to model transitions between states and recurrent events. The simulation results were visualized using state transition diagrams, probability heatmaps, and time series plots.

                            
     ![image](https://github.com/user-attachments/assets/5f2abc9a-625f-4798-8d9c-2fa9a0eb77b3)
   
     ![image](https://github.com/user-attachments/assets/e7f90004-1639-461f-a9df-114963f3256d)

     ![image](https://github.com/user-attachments/assets/e030dd20-a271-42c2-8a6e-e6c1f4c5e1c2)


3. **Variance Reduction Techniques**: Importance sampling and control variates were employed to reduce variance in the simulations. The effectiveness of these techniques was assessed by comparing the estimated expectation and variance with the original distribution.
   
     ![image](https://github.com/user-attachments/assets/2ee62f1d-9fd1-4d99-9f22-c0d936b4a7f0)

     ![image](https://github.com/user-attachments/assets/bf117d5f-d826-4225-b8cc-cdc2d29b9e7c)

     ![image](https://github.com/user-attachments/assets/b6533a8b-c4c7-4050-9433-cbb0e40240de)


4. **Comparative Analysis**: Different simulation methods, including the original gamma distribution, MCMC sampling, log transformation, and importance sampling, were compared to assess their impact on reducing variance and improving the model. MCMC sampling and log transformation demonstrated significant variance reduction compared to the original distribution.

## Conclusion
The research project successfully applied a wide range of probabilistic and statistical techniques to explore real-world data and address specific questions of interest. The simulation and analysis of continuous and discrete random variables provided insights into their characteristics and the impact of normalization on data distribution. The Central Limit Theorem was verified, and outlier detection methods were employed to identify potential anomalies in the datasets.

Markov Chains played a crucial role in understanding the randomness of transition states and the convergence of time-averaged behavior to steady-state probabilities. Variance reduction techniques, such as importance sampling and control variates, were explored to enhance simulation efficiency.

The project also delved into combinatorial analysis, providing tangible applications of probability principles in practical scenarios. The comparative analysis of different simulation methods highlighted the effectiveness of MCMC sampling and log transformation in reducing variance and improving model performance.

Throughout the research, a concerted effort was made to synthesize theoretical knowledge with practical applications, solidifying the understanding of probabilistic and statistical methods. The project demonstrates the power of applying advanced probability and statistics techniques to navigate and extract meaningful insights from real-world data.
