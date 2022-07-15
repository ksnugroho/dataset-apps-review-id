# Dataset apps reviews of Indonesian.

The dataset was taken using scrapping on the ten best applications in 2020 in Google Play (monthly active user Jan - Oct 2020). 

## Data Format
The dataset consists of 10,854 rows and 12 columns. Columns consist of review id, username, user image, content, score, thumbs up count, review version, review date, reply content, replied at, sort order, and app id. The content column contains user reviews, while the app id column shows the application.

## Apps list
- Facebook (com.facebook.katana)
- WhatsApp (com.whatsapp)
- Messenger (com.facebook.orca)
- Instagram (com.instagram.android)
- Amazon (com.amazon.windowshop)
- Twitter (com.twitter.android)
- Netflix (com.netflix.mediaclient)
- Tiktok (com.ss.android.ugc.trill)
- Spotify (com.spotify.music)
- Snapchat (com.snapchat.android)

## Citation
If you want to publish a paper using this dataset, please cite our publication: <br/>
@inbook{10.1145/3479645.3479679,
author = {Nugroho, Kuncahyo Setyo and Sukmadewa, Anantha Yullian and Wuswilahaken DW, Haftittah and Bachtiar, Fitra A. and Yudistira, Novanto},
title = {BERT Fine-Tuning for Sentiment Analysis on Indonesian Mobile Apps Reviews},
year = {2021},
isbn = {9781450384070},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3479645.3479679},
abstract = {User reviews have an essential role in the success of the developed mobile apps. User reviews in the textual form are unstructured data, creating a very high complexity when processed for sentiment analysis. Previous approaches that have been used often ignore the context of reviews. In addition, the relatively small data makes the model overfitting. A new approach, BERT, has been introduced as a transfer learning model with a pre-trained model that has previously been trained to have a better context representation. This study examines the effectiveness of fine-tuning BERT for sentiment analysis using two different pre-trained models. Besides the multilingual pre-trained model, we use the pre-trained model that only has been trained in Indonesian. The dataset used is Indonesian user reviews of the ten best apps in 2020 in Google Play sites. We also perform hyper-parameter tuning to find the optimum trained model. Two training data labeling approaches were also tested to determine the effectiveness of the model, which is score-based and lexicon-based. The experimental results show that pre-trained models trained in Indonesian have better average accuracy on lexicon-based data. The specific Indonesian pre-trained model achieved the highest accuracy of 84%, with 25 epochs and 24 minutes of training time.},
booktitle = {6th International Conference on Sustainable Information Engineering and Technology 2021},
pages = {258–264},
numpages = {7}
}

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
