# App-Store-Data-Analysis
In this project, I find the importance of considering non-linear relationships and visual patterns, rather than relying solely on correlation coefficients, when evaluating app success.

I Use the 10k app dataset from Kaggle, giving 7197 apps to analyze. Dataset gives App price, ratings, new version ratings, genre, bytes, etc.

App success on the App Store is influenced by multiple factors. From my analysis, the strongest patterns in user ratings are associated with app price, size, genre, and number of languages supported. Other features, such as app age, number of supported devices, and total number of ratings, show weaker correlations or more complex patterns.

#### 1. Price
Paid apps tend to have slightly higher ratings than free apps, but the relationship is non-linear. Apps in a moderate price range appear to achieve the highest average ratings, while very cheap or very expensive apps show slightly lower ratings. This suggests that user satisfaction may peak when the price balances perceived value and cost.

#### 2. Size of an App
Larger apps generally have higher ratings, likely due to more features or functionality. However, this trend plateaus beyond a certain size, indicating that adding more features does not continue to increase user satisfaction indefinitely.

#### 3. Genre of App
The type of app also influences user ratings. Productivity and music apps tend to receive higher ratings, likely due to their focused functionality and niche audiences. In contrast, games dominate the App Store in quantity, which results in a wider range of reviews and a lower average rating. This suggests that market saturation can affect user satisfaction, with highly crowded categories experiencing greater variability in ratings.

#### 4. Languages Offered by App
Apps supporting more languages generally achieve higher ratings, reflecting the value of localization and global accessibility. While there are some outliers with a large number of languages and low ratings, the overall trend shows that investing in multi-language support is associated with better user feedback.

#### 5. Age of App Audience
Although the overall correlation between app age requirements and user ratings is very low (-0.04), further visual analysis shows a more nuanced pattern. Most age categories have little effect on ratings, but apps targeted at older audiences exhibit a wider spread of ratings, which lowers their average. While this effect is not statistically strong, it suggests that certain age-targeted apps may face greater variability in user satisfaction.

#### 6. Take-Away
Overall, price, size, and language support emerge as the most influential factors on user ratings, with app age showing a subtler, more context-dependent effect. This analysis highlights the importance of considering non-linear relationships and visual patterns, rather than relying solely on correlation coefficients, when evaluating app success.
