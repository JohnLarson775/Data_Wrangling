# Data_Wrangling

### Description

The goal of this project is to wrangle [WeRateDogs](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning of data was needed.

> **The Data:**
> 
> *Enhanced Twitter Archive*:<br>Tweet data that was extracted from the tweet's text. This includes rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Filtered 5000+ tweets for ones with ratings only (2356).
> 
> *Additional Data via the Twitter API*:<br>Retweet count and favorite count are two of the notable column omissions from the "Enhanced Twitter Archive." This data can be gathered by anyone from Twitter's API in conjunction with the unique tweet IDs within the archive.
> 
> *Image Predictions File*:<br>Every image in the WeRateDogs Twitter archive was passed through a neural network that can classify breeds of dogs. The results are a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

### To Do
* Improce README to describe different files.
