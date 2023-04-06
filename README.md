# applied-ml
Curated papers, articles, and blogs on **data science & machine learning in production**. ⚙️

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](./CONTRIBUTING.md) [![Summaries](https://img.shields.io/badge/summaries-in%20tweets-%2300acee.svg?style=flat)](https://twitter.com/eugeneyan/status/1350509546133811200) ![HitCount](http://hits.dwyl.com/eugeneyan/applied-ml.svg)

Figuring out how to implement your ML project? Learn how other organizations did it:

- **How** the problem is framed 🔎(e.g., personalization as recsys vs. search vs. sequences)
- **What** machine learning techniques worked ✅ (and sometimes, what didn't ❌)
- **Why** it works, the science behind it with research, literature, and references 📂
- **What** real-world results were achieved (so you can better assess ROI ⏰💰📈)

P.S., Want a summary of ML advancements? 👉[`ml-surveys`](https://github.com/eugeneyan/ml-surveys)

P.P.S, Looking for guides and interviews on applying ML? 👉[`applyingML`](https://applyingml.com)

**Table of Contents**

1. [Data Quality](#data-quality)
2. [Data Engineering](#data-engineering)
3. [Data Discovery](#data-discovery)
4. [Feature Stores](#feature-stores)
5. [Classification](#classification)
6. [Regression](#regression)
7. [Forecasting](#forecasting)
8. [Recommendation](#recommendation)
9. [Search & Ranking](#search--ranking)
10. [Embeddings](#embeddings)
11. [Natural Language Processing](#natural-language-processing)
12. [Sequence Modelling](#sequence-modelling)
13. [Computer Vision](#computer-vision)
14. [Reinforcement Learning](#reinforcement-learning)
15. [Anomaly Detection](#anomaly-detection)
16. [Graph](#graph)
17. [Optimization](#optimization)
18. [Information Extraction](#information-extraction)
19. [Weak Supervision](#weak-supervision)
20. [Generation](#generation)
21. [Audio](#audio)
22. [Validation and A/B Testing](#validation-and-ab-testing)
23. [Model Management](#model-management)
24. [Efficiency](#efficiency)
25. [Ethics](#ethics)
26. [Infra](#infra)
27. [MLOps Platforms](#mlops-platforms)
28. [Practices](#practices)
29. [Team Structure](#team-structure)
30. [Fails](#fails)




## Anomaly Detection
1. [Detecting Performance Anomalies in External Firmware Deployments](https://netflixtechblog.com/detecting-performance-anomalies-in-external-firmware-deployments-ed41b1bfcf46) `Netflix` `2019`
2. [Detecting and Preventing Abuse on LinkedIn using Isolation Forests](https://engineering.linkedin.com/blog/2019/isolation-forest) ([Code](https://github.com/linkedin/isolation-forest)) `LinkedIn` `2019`
3. [Deep Anomaly Detection with Spark and Tensorflow](https://databricks.com/session_eu19/deep-anomaly-detection-from-research-to-production-leveraging-spark-and-tensorflow) [(Hopsworks Video](https://www.youtube.com/watch?v=TgXVU8DSyCQ)) `Swedbank`, `Hopsworks` `2019`
4. [Preventing Abuse Using Unsupervised Learning](https://databricks.com/session_na20/preventing-abuse-using-unsupervised-learning) `LinkedIn` `2020`
5. [The Technology Behind Fighting Harassment on LinkedIn](https://engineering.linkedin.com/blog/2020/fighting-harassment) `LinkedIn` `2020`
6. [Uncovering Insurance Fraud Conspiracy with Network Learning](https://arxiv.org/abs/2002.12789) ([Paper](https://arxiv.org/pdf/2002.12789.pdf)) `Ant Financial` `2020`
7. [How Does Spam Protection Work on Stack Exchange?](https://stackoverflow.blog/2020/06/25/how-does-spam-protection-work-on-stack-exchange/) `Stack Exchange` `2020`
8. [Auto Content Moderation in C2C e-Commerce](https://www.usenix.org/conference/opml20/presentation/ueta) `Mercari` `2020`
9. [Blocking Slack Invite Spam With Machine Learning](https://slack.engineering/blocking-slack-invite-spam-with-machine-learning/) `Slack` `2020`
10. [Cloudflare Bot Management: Machine Learning and More](https://blog.cloudflare.com/cloudflare-bot-management-machine-learning-and-more/) `Cloudflare` `2020`
11. [Anomalies in Oil Temperature Variations in a Tunnel Boring Machine](https://www.youtube.com/watch?v=YV_uLLhPRAk) `SENER` `2020`
12. [Using Anomaly Detection to Monitor Low-Risk Bank Customers](https://www.youtube.com/watch?v=MExokMM_Bp4&t=3s) `Rabobank` `2020`
13. [Fighting fraud with Triplet Loss](https://tech.olx.com/fighting-fraud-with-triplet-loss-86e5f79c7a3e) `OLX Group` `2020`
14. [Facebook is Now Using AI to Sort Content for Quicker Moderation](https://www.theverge.com/2020/11/13/21562596/facebook-ai-moderation) ([Alternative](https://venturebeat.com/2020/11/13/facebooks-redoubled-ai-efforts-wont-stop-the-spread-of-harmful-content/)) `Facebook` `2020`
15. How AI is getting better at detecting hate speech [Part 1](https://ai.facebook.com/blog/how-ai-is-getting-better-at-detecting-hate-speech/), [Part 2](https://ai.facebook.com/blog/heres-how-were-using-ai-to-help-detect-misinformation/), [Part 3](https://ai.facebook.com/blog/training-ai-to-detect-hate-speech-in-the-real-world/), [Part 4](https://ai.facebook.com/blog/how-facebook-uses-super-efficient-ai-models-to-detect-hate-speech/) `Facebook` `2020`
16. [Using deep learning to detect abusive sequences of member activity](https://engineering.linkedin.com/blog/2021/using-deep-learning-to-detect-abusive-sequences-of-member-activi) ([Video](https://exchange.scale.com/public/videos/using-deep-learning-to-detect-abusive-sequences-of-member-activity-on-linkedin)) `LinkedIn` `2021`
17. [Project RADAR: Intelligent Early Fraud Detection System with Humans in the Loop](https://eng.uber.com/project-radar-intelligent-early-fraud-detection/) `Uber` `2022`
18. [Graph for Fraud Detection](https://engineering.grab.com/graph-for-fraud-detection) `Grab` `2022`
19. [Bandits for Online Calibration: An Application to Content Moderation on Social Media Platforms](https://arxiv.org/abs/2211.06516) `Meta` `2022`
20. [Evolving our machine learning to stop mobile bots](https://blog.cloudflare.com/machine-learning-mobile-traffic-bots/) `Cloudflare` `2022`
21. [Improving the accuracy of our machine learning WAF using data augmentation and sampling](https://blog.cloudflare.com/data-generation-and-sampling-strategies/) `Cloudflare` `2022`
22. [Machine Learning for Fraud Detection in Streaming Services](https://netflixtechblog.com/machine-learning-for-fraud-detection-in-streaming-services-b0b4ef3be3f6) `Netflix` `2022`
23. [Pricing at Lyft](https://eng.lyft.com/pricing-at-lyft-8a4022065f8b) `Lyft` `2022`



## Validation and A/B Testing
1. [Overlapping Experiment Infrastructure: More, Better, Faster Experimentation](https://research.google/pubs/pub36500/) ([Paper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36500.pdf)) `Google` `2010`
2. [The Reusable Holdout: Preserving Validity in Adaptive Data Analysis](https://ai.googleblog.com/2015/08/the-reusable-holdout-preserving.html) ([Paper](https://science.sciencemag.org/content/sci/349/6248/636.full.pdf)) `Google` `2015`
3. [Twitter Experimentation: Technical Overview](https://blog.twitter.com/engineering/en_us/a/2015/twitter-experimentation-technical-overview.html) `Twitter` `2015`
4. [It’s All A/Bout Testing: The Netflix Experimentation Platform](https://netflixtechblog.com/its-all-a-bout-testing-the-netflix-experimentation-platform-4e1ca458c15) `Netflix` `2016`
5. [Building Pinterest’s A/B Testing Platform](https://medium.com/pinterest-engineering/building-pinterests-a-b-testing-platform-ab4934ace9f4) `Pinterest` `2016` 
6. [Experimenting to Solve Cramming](https://blog.twitter.com/engineering/en_us/topics/insights/2017/Experimenting-To-Solve-Cramming.html) `Twitter` `2017`
7. [Building an Intelligent Experimentation Platform with Uber Engineering](https://eng.uber.com/experimentation-platform/) `Uber` `2017`
8. [Scaling Airbnb’s Experimentation Platform](https://medium.com/airbnb-engineering/https-medium-com-jonathan-parks-scaling-erf-23fd17c91166) `Airbnb` `2017`
9. [Meet Wasabi, an Open Source A/B Testing Platform](https://www.intuit.com/blog/technology/engineering/meet-wasabi-an-open-source-ab-testing-platform/) ([Code](https://github.com/intuit/wasabi)) `Intuit` `2017` 
10. [Analyzing Experiment Outcomes: Beyond Average Treatment Effects](https://eng.uber.com/analyzing-experiment-outcomes/) `Uber` `2018`
11. [Under the Hood of Uber’s Experimentation Platform](https://eng.uber.com/xp/) `Uber` `2018`
12. [Constrained Bayesian Optimization with Noisy Experiments](https://research.fb.com/publications/constrained-bayesian-optimization-with-noisy-experiments/) ([Paper](https://arxiv.org/pdf/1706.07094.pdf)) `Facebook` `2018`
13. [Reliable and Scalable Feature Toggles and A/B Testing SDK at Grab](https://engineering.grab.com/feature-toggles-ab-testing) `Grab` `2018`
14. [Modeling Conversion Rates and Saving Millions Using Kaplan-Meier and Gamma Distributions](https://better.engineering/modeling-conversion-rates-and-saving-millions-of-dollars-using-kaplan-meier-and-gamma-distributions/) ([Code](https://github.com/better/convoys)) `Better` `2019`
15. [Detecting Interference: An A/B Test of A/B Tests](https://engineering.linkedin.com/blog/2019/06/detecting-interference--an-a-b-test-of-a-b-tests) `LinkedIn` `2019`
16. [Announcing a New Framework for Designing Optimal Experiments with Pyro](https://eng.uber.com/oed-pyro-release/) ([Paper](https://papers.nips.cc/paper/9553-variational-bayesian-optimal-experimental-design.pdf)) ([Paper](https://arxiv.org/pdf/1911.00294.pdf)) `Uber` `2020`
17. [Enabling 10x More Experiments with Traveloka Experiment Platform](https://medium.com/traveloka-engineering/enabling-10x-more-experiments-with-traveloka-experiment-platform-8cea13e952c) `Traveloka` `2020`
18. [Large Scale Experimentation at Stitch Fix](https://multithreaded.stitchfix.com/blog/2020/07/07/large-scale-experimentation/) ([Paper](http://proceedings.mlr.press/v89/schmit19a/schmit19a.pdf)) `Stitch Fix` `2020`
19. [Multi-Armed Bandits and the Stitch Fix Experimentation Platform](https://multithreaded.stitchfix.com/blog/2020/08/05/bandits/) `Stitch Fix` `2020`
20. [Experimentation with Resource Constraints](https://multithreaded.stitchfix.com/blog/2020/11/18/virtual-warehouse/) `Stitch Fix` `2020`
21. [Computational Causal Inference at Netflix](https://netflixtechblog.com/computational-causal-inference-at-netflix-293591691c62) ([Paper](https://arxiv.org/pdf/2007.10979.pdf)) `Netflix` `2020`
22. [Key Challenges with Quasi Experiments at Netflix](https://netflixtechblog.com/key-challenges-with-quasi-experiments-at-netflix-89b4f234b852) `Netflix` `2020`
23. [Making the LinkedIn experimentation engine 20x faster](https://engineering.linkedin.com/blog/2020/making-the-linkedin-experimentation-engine-20x-faster) `LinkedIn` `2020`
24. [Our Evolution Towards T-REX: The Prehistory of Experimentation Infrastructure at LinkedIn](https://engineering.linkedin.com/blog/2020/our-evolution-towards-t-rex--the-prehistory-of-experimentation-i) `LinkedIn` `2020`
25. [How to Use Quasi-experiments and Counterfactuals to Build Great Products](https://engineering.shopify.com/blogs/engineering/using-quasi-experiments-counterfactuals) `Shopify` `2020`
26. [Improving Experimental Power through Control Using Predictions as Covariate](https://doordash.engineering/2020/06/08/improving-experimental-power-through-control-using-predictions-as-covariate-cupac/) `DoorDash` `2020`
27. [Supporting Rapid Product Iteration with an Experimentation Analysis Platform](https://doordash.engineering/2020/09/09/experimentation-analysis-platform-mvp/) `DoorDash` `2020`
28. [Improving Online Experiment Capacity by 4X with Parallelization and Increased Sensitivity](https://doordash.engineering/2020/10/07/improving-experiment-capacity-by-4x/) `DoorDash` `2020`
29. [Leveraging Causal Modeling to Get More Value from Flat Experiment Results](https://doordash.engineering/2020/09/18/causal-modeling-to-get-more-value-from-flat-experiment-results/) `DoorDash` `2020`
30. [Iterating Real-time Assignment Algorithms Through Experimentation](https://doordash.engineering/2020/12/08/optimizing-real-time-algorithms-experimentation/) `DoorDash` `2020`
31. [Spotify’s New Experimentation Platform (Part 1)](https://engineering.atspotify.com/2020/10/29/spotifys-new-experimentation-platform-part-1/) [(Part 2)](https://engineering.atspotify.com/2020/11/02/spotifys-new-experimentation-platform-part-2/) `Spotify` `2020`
32. [Interpreting A/B Test Results: False Positives and Statistical Significance](https://netflixtechblog.com/interpreting-a-b-test-results-false-positives-and-statistical-significance-c1522d0db27a) `Netflix` `2021`
33. [Interpreting A/B Test Results: False Negatives and Power](https://netflixtechblog.com/interpreting-a-b-test-results-false-negatives-and-power-6943995cf3a8) `Netflix` `2021`
34. [Running Experiments with Google Adwords for Campaign Optimization](https://doordash.engineering/2021/02/05/google-adwords-campaign-optimization/) `DoorDash` `2021`
35. [The 4 Principles DoorDash Used to Increase Its Logistics Experiment Capacity by 1000%](https://doordash.engineering/2021/09/21/the-4-principles-doordash-used-to-increase-its-logistics-experiment-capacity-by-1000/) `DoorDash` `2021`
36. [Experimentation Platform at Zalando: Part 1 - Evolution](https://engineering.zalando.com/posts/2021/01/experimentation-platform-part1.html) `Zalando` `2021`
37. [Designing Experimentation Guardrails](https://medium.com/airbnb-engineering/designing-experimentation-guardrails-ed6a976ec669) `Airbnb` `2021`
38. [How Airbnb Measures Future Value to Standardize Tradeoffs](https://medium.com/airbnb-engineering/how-airbnb-measures-future-value-to-standardize-tradeoffs-3aa99a941ba5) `Airbnb` `2021`
38. [Network Experimentation at Scale](https://research.fb.com/publications/network-experimentation-at-scale/)([Paper](https://arxiv.org/abs/2012.08591)] `Facebook` `2021`
39. [Universal Holdout Groups at Disney Streaming](https://medium.com/disney-streaming/universal-holdout-groups-at-disney-streaming-2043360def4f) `Disney` `2021`
40. [Experimentation is a major focus of Data Science across Netflix](https://netflixtechblog.com/experimentation-is-a-major-focus-of-data-science-across-netflix-f67923f8e985) `Netflix` `2022`
41. [Search Journey Towards Better Experimentation Practices](https://engineering.atspotify.com/2022/02/search-journey-towards-better-experimentation-practices/) `Spotify` `2022`
42. [Artificial Counterfactual Estimation: Machine Learning-Based Causal Inference at Airbnb](https://medium.com/airbnb-engineering/artificial-counterfactual-estimation-ace-machine-learning-based-causal-inference-at-airbnb-ee32ee4d0512) `Airbnb` `2022`
43. [Beyond A/B Test : Speeding up Airbnb Search Ranking Experimentation through Interleaving](https://medium.com/airbnb-engineering/beyond-a-b-test-speeding-up-airbnb-search-ranking-experimentation-through-interleaving-7087afa09c8e) `Airbnb` `2022`
44. [Challenges in Experimentation](https://eng.lyft.com/challenges-in-experimentation-be9ab98a7ef4) `Lyft` `2022`
45. [Overtracking and Trigger Analysis: Reducing sample sizes while INCREASING sensitivity](https://booking.ai/overtracking-and-trigger-analysis-how-to-reduce-sample-sizes-and-increase-the-sensitivity-of-71755bad0e5f) `Booking` `2022`
46. [Meet Dash-AB — The Statistics Engine of Experimentation at DoorDash](https://doordash.engineering/2022/05/24/meet-dash-ab-the-statistics-engine-of-experimentation-at-doordash/) `DoorDash` `2022`
47. [Comparing quantiles at scale in online A/B-testing](https://engineering.atspotify.com/2022/03/comparing-quantiles-at-scale-in-online-a-b-testing) `Spotify` `2022`
48. [Accelerating our A/B experiments with machine learning](https://dropbox.tech/machine-learning/accelerating-our-a-b-experiments-with-machine-learning-xr) `Dropbox` `2023`
49. [Supercharging A/B Testing at Uber](https://www.uber.com/blog/supercharging-a-b-testing-at-uber/) `Uber` 


## Ethics
1. [Building Inclusive Products Through A/B Testing](https://engineering.linkedin.com/blog/2020/building-inclusive-products-through-a-b-testing) ([Paper](https://arxiv.org/pdf/2002.05819.pdf)) `LinkedIn` `2020`
2. [LiFT: A Scalable Framework for Measuring Fairness in ML Applications](https://engineering.linkedin.com/blog/2020/lift-addressing-bias-in-large-scale-ai-applications) ([Paper](https://arxiv.org/pdf/2008.07433.pdf)) `LinkedIn` `2020`
3. [Introducing Twitter’s first algorithmic bias bounty challenge](https://blog.twitter.com/engineering/en_us/topics/insights/2021/algorithmic-bias-bounty-challenge) `Twitter` `2021`
4. [Examining algorithmic amplification of political content on Twitter](https://blog.twitter.com/en_us/topics/company/2021/rml-politicalcontent) `Twitter` `2021`
5. [A closer look at how LinkedIn integrates fairness into its AI products](https://engineering.linkedin.com/blog/2022/a-closer-look-at-how-linkedin-integrates-fairness-into-its-ai-pr) `LinkedIn` `2022`



## Fails
1. [When It Comes to Gorillas, Google Photos Remains Blind](https://www.wired.com/story/when-it-comes-to-gorillas-google-photos-remains-blind/) `Google` `2018`
2. [160k+ High School Students Will Graduate Only If a Model Allows Them to](http://positivelysemidefinite.com/2020/06/160k-students.html) `International Baccalaureate` `2020`
3. [An Algorithm That ‘Predicts’ Criminality Based on a Face Sparks a Furor](https://www.wired.com/story/algorithm-predicts-criminality-based-face-sparks-furor/) `Harrisburg University` `2020`
4. [It's Hard to Generate Neural Text From GPT-3 About Muslims](https://twitter.com/abidlabs/status/1291165311329341440) `OpenAI` `2020`
5. [A British AI Tool to Predict Violent Crime Is Too Flawed to Use](https://www.wired.co.uk/article/police-violence-prediction-ndas) `United Kingdom` `2020`
6. More in [awful-ai](https://github.com/daviddao/awful-ai)
7. [AI Incident Database](https://incidentdatabase.ai/) `Partnership on AI` `2022`

<br>

**P.S., Want a summary of ML advancements?** Get up to speed with survey papers 👉[`ml-surveys`](https://github.com/eugeneyan/ml-surveys)
