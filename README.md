# Analysis of Instagram Post Engagement through Topic Modeling


## 1. Introduction
This report presents an analysis of Instagram post engagement through topic modeling of labels derived from images using Google Vision. The analysis is based on a sample of 296 posts containing a total of 1522 images. The goal is to identify which topics are associated with higher engagement, defined as the number of comments. This information can guide content strategy to increase engagement on the platform.

## 2. Methodology
Labels were first obtained for each image using Google Vision API, the dataset was then subjected to topic modeling to extract prevalent themes from the labels obtained via Google Vision on each image. Latent Dirichlet Allocation (LDA) was employed to categorize the captions into eight distinct topics. Each image was assigned a distribution across these topics. For efficiency, not all images were analyzed. Instead, a representative sample was chosen to expedite the computation and ensure manageability.

## 3. Topic Descriptions
Below are the topics extracted from the analysis, with key words representing each topic:
- **Formal Events and Fashion:** Smile, Sleeve, Flash photography, Formal wear.
- **Outdoor Leisure and Vision:** Eyewear, Sunglasses, People in nature, Vision care.
- **Casual Wear and Happy Moments:** Gesture, Happy, Smile, T-shirt.
- **Musical Events and Performance:** Event, Font, Black-and-white, Microphone.
- **Sports and Athletic Wear:** Sports uniform, Jersey, Gesture, Player.
- **Digital Content and Branding:** Font, Event, Electric blue, Brand.
- **Nature and Outdoors:** Plant, Happy, Sky, Tree.
- **Food and Cuisine:** Food, Ingredient, Recipe, Cuisine.

## 4. Engagement Analysis
The following table shows the average topic weights for posts with high and low engagement. High engagement posts are those in the top 25% of comments, while low engagement posts fall in the bottom 25%.

| Topic                            | High Engagement Avg Weights | Low Engagement Avg Weights |
|----------------------------------|-----------------------------|----------------------------|
| Formal Events and Fashion        | 0.152796                    | 0.130055                   |
| Outdoor Leisure and Vision       | 0.135640                    | 0.123097                   |
| Casual Wear and Happy Moments    | 0.112544                    | 0.153359                   |
| Musical Events and Performance   | 0.097433                    | 0.099123                   |
| Sports and Athletic Wear         | 0.182938                    | 0.127017                   |
| Digital Content and Branding     | 0.092226                    | 0.162322                   |
| Nature and Outdoors              | 0.129024                    | 0.096579                   |
| Food and Cuisine                 | 0.097399                    | 0.108449                   |

## 5. Recommendations
Based on the analysis, the following strategies are recommended to increase engagement:
- Increase the frequency of posts related to **Sports and Athletic Wear** and **Formal Events and Fashions**, as these topics are strongly associated with high engagement.
- Consider diversifying content to include more topics related to **Nature and Outdoors** and **Outdoor Leisure and Vision** which also show potential for high engagement.
- Review the content strategy for **Nature and Outdoor**, **Musical Events and Performance**, and **Food and Cuisine** as these topics show higher weights in low engagement posts.

## 6. Conclusion
This analysis provides a clear indication of which topics are most likely to engage an Instagram audience. By strategically focusing on these topics, it is possible to enhance overall engagement on the platform.
