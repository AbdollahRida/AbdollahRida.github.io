---
title: "Machine and Deep Learning for Credit Scoring: A compliant approach (EN)"
excerpt: "My Master Thesis written after my research internship at the BNP Paribas offices in New York City."
collection: portfolio
---

<b><a style="line-height: 1.5;" href="https://www.researchgate.net/publication/336617810_Machine_and_Deep_Learning_for_Credit_Scoring_A_compliant_Approach"><span style="color: #333333;"><span style="font-size: medium;">You can find the thesis here.</span></span></a></b>

*Quick Description*
---------
This memoir has the particularity to present a full Machine Learning project compliant with a stringent (US) risk management regulation. It is a full transposition of a strong ML theoretical framework (Boosting) to a major concern for commercial banks (managing on a daily basis the credit risk of large portfolios).
In the perspective of challenging models in production relying on classical (linear or logistic) regression approaches, XGBoost has been selected because of its following particularities:
 
* It deals with non linearities
* Optimized to run fast on massive datasets, allowing to consider it as a potential model in production
* Handles missing values [cf. p. 12]
* Interpretable with Shapley values [cf. p.19, §5.2.1]

The resulting model shows better performances than the one in production and can be easily integrated in the Model Management framework of the Bank. It also opens promising perspectives on an in-depth systematic and standardized model challenging approach.
It can be noted that the approach deals with concerns very usual in credit risk such as imbalanced classes and uses solutions applicable to any ML approach (resampling and loss function reweighting) [cf. Annex B.1]

*Abstract*
----------

Credit Scoring is one of the problems banks and financial institutions have to solve on a daily basis. If the state-of-the-art research in Machine and Deep Learning for finance has reached interesting results about Credit Scoring models, usage of such models in a heavily regulated context ([5], [1], [3], [4]) such as the one in banks has never been done so far.
Our work is thus a tentative to challenge the current regulatory status-quo and introduce new BASEL 2 and 3 compliant techniques, while still answering the Federal Reserve Bank and the European Central Bank requirements.
With the help of Gradient Boosting Machines (mainly XGBoost [9]) we challenge an actual model used by BANK A for scoring through the door Auto Loan applicants. We prove that the usage of such algorithms for Credit Scoring models drastically improves performance and default capture rate.
Furthermore, we leverage the power of Shapley Values [16] to prove that these relatively simple models are not as black-box as the current regulatory system thinks they are, and we attempt to explain the model outputs and Credit Scores within the BANK A Model Design and Validation framework.

*References*
------------

[1] Federal reserve supervisory assessment of capital planning and positions for large and noncomplex firms.

[2] https://github.com/ckmarkoh/gan-tensorflow.

[3] Occ 2000–16.

[4] Occ bulletin 1997-24.

[5] Sr 11-7: Guidance on model risk management.

[6] Sunil Bhatia, Pratik Sharma, Rohit Burman, Santosh Hazari, and Rupali Hande. Credit Scoring using Machine Learning Techniques. International Journal of Computer Applications, 161(11):1–4, March 2017.

[7] Kevin W. Bowyer, Nitesh V. Chawla, Lawrence O. Hall, and W. Philip Kegelmeyer. SMOTE: synthetic minority over-sampling technique. CoRR, abs/1106.1813, 2011.

[8] Sebastien Bubeck. Convex Optimization: Algorithms and Complexity (Foundations and Trends in Machine Learning). Now Publishers Inc, oct 2015.

[9] Tianqi Chen and Carlos Guestrin. Xgboost: A scalable tree boosting system. CoRR, abs/1603.02754, 2016.

[10] Christophe Giraud. Introduction to High-Dimensional Statistics (Chapman & Hall/CRC Monographs on Statistics and Applied Probability). Chapman and Hall/CRC, dec 2014.

[11] Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, and Yoshua Bengio. Generative adversarial networks, 2014.

[12] Aur ́elien G ́eron. Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems. O’Reilly Media, apr 2017.

[13] Trevor Hastie, Robert Tibshirani, and Jerome Friedman. The Elements of Statistical Learning. Springer Series in Statistics. Springer New York Inc., New York, NY, USA, 2001.

[14] Sepp Hochreiter and Ju ̈rgen Schmidhuber. Long short-term memory. Neural Comput., 9(8):1735–1780, November 1997.

[15] Amir E. Khandani, Adlar J. Kim, and Andrew W. Lo. Consumer Credit-Risk Models Via Machine- Learning Algorithms. Lo, June 2010.

[16] Scott Lundberg and Su-In Lee. A unified approach to interpreting model predictions. CoRR, abs/1705.07874, 2017.

[17] Cuicui Luo, Desheng Wu, and Dexiang Wu. A deep learning approach for credit scoring using credit default swaps. Engineering Applications of Artificial Intelligence, 65:465–470, October 2017.

[18] Mehdi Mirza and Simon Osindero. Conditional generative adversarial nets, 2014.

[19] Mehryar Mohri. Foundations of Machine Learning (Adaptive Computation and Machine Learning series). The MIT Press, aug
2012.

[20] M. Saberi, M. S. Mirtalaie, F. K. Hussain, A. Azadeh, O. K. Hussain, and B. Ashjari. A granular computing-based approach to credit scoring modeling. December 2013.

[21] H. P. Young. Monotonic solutions of cooperative games. International Journal of Game Theory, 14(2):65–72, June 1985.
