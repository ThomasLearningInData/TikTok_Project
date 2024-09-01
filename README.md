# TikTok Project
Find the correlation between variables and apply hypothesis test to answer questions.

![image](https://github.com/user-attachments/assets/d54eff35-a9e8-4dd4-b34c-71c80d411912)

High correlations (close to 1.0) are observed between several variables, such as:
- video_view_count and video_like_count (0.94)
- video_like_count and video_share_count (0.95)
- video_share_count and video_download_count (0.90)

The video_duration_sec has very low correlations with other metrics, suggesting that video duration might not significantly influence other metrics like views, likes, or comments after the transformation.

### Other variables impact on share count
<img width="671" alt="螢幕截圖 2024-09-01 下午3 06 30" src="https://github.com/user-attachments/assets/f4db6bac-7f3f-44e4-8cb7-c059a4156727">
This is a good model that explain about 90% of the variance. The regression results indicate that video engagement metrics, such as view count, like count, and comment count, significantly influence the number of shares a video receives. Specifically, the like count is the most critical factor, with a high coefficient (0.9418) and strong statistical significance (p < 0.001), suggesting that videos with more likes are more likely to be shared. Meanwhile, video duration and download count do not significantly affect shares.

For businesses, this insight suggests focusing on strategies that increase likes and comments to boost video shares, such as engaging content or call-to-action prompts, rather than emphasizing video length.
__________
𝐻0
 : There is no difference in number of views between TikTok videos posted by verified accounts and TikTok videos posted by unverified accounts (any observed difference in the sample data is due to chance or sampling variability).

𝐻𝐴
: There is a difference in number of views between TikTok videos posted by verified accounts and TikTok videos posted by unverified accounts (any observed difference in the sample data is due to an actual difference in the corresponding population means).

<img width="748" alt="螢幕截圖 2024-09-01 下午3 07 44" src="https://github.com/user-attachments/assets/ec8b157a-24b9-4c3e-8f83-7ddf5dcb9dab">

Since the p-value is less than 0.05, we can conclude that there is a statistically significant difference in the mean video view count between verified and unverified accounts on TikTok.

The analysis shows that there is a statistically significant difference in the average view counts between videos from verified accounts and videos from unverified accounts. This suggests there might be fundamental behavioral differences between these two groups of accounts.


