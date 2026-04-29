# 📊 Optimal FICO Score Quantization

## Objective
To support a categorical machine learning architecture by algorithmically converting continuous FICO credit scores into optimal, discrete risk "buckets."

## The Quantitative Approach
Rather than arbitrarily splitting FICO scores into even chunks, this project relies on mathematical optimization to isolate distinct behavioral risk profiles.

1. **Object-Oriented Design:** Engineered an `OptimalRiskQuantizer` class that can seamlessly integrate into standard `scikit-learn` pipelines.
2. **Dynamic Programming:** Deployed a sophisticated Dynamic Programming (DP) algorithm to efficiently search thousands of boundary combinations across the continuous FICO spectrum.
3. **Log-Likelihood Optimization:** The algorithm selects the exact cutoff boundaries that maximize the Log-Likelihood of default densities, ensuring that borrowers inside the same bucket have nearly identical default behaviors.
4. **Constraint Management:** Included a `min_bucket_size` constraint to ensure statistical significance and prevent the model from overfitting on small data anomalies.

## Results
The quantization algorithm successfully maps continuous FICO scores into distinct, mathematically proven risk categories (e.g., automatically separating a 72% default rate bucket from a 33% default rate bucket with exact precision). It also automatically generates an auditable Risk Profile Summary DataFrame for internal model validation and stakeholder review.
