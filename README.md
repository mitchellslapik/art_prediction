# art_prediction
If Monet, Picasso, Van Gogh lived another 100 years, what would they have painted? In order to do study this, I train a GAN on art, and then find the corresponding image codes for the artist's paintings over many years of their career. Using a linear regression, I find trends in these image codes over time. Finally, by extrapolating out to image codes for future paintings, I am able to feed those future codes back into the GAN to predict what their future painting would look like.

Download Van Gogh dataset here: https://www.kaggle.com/datasets/pointblanc/colors-of-van-gogh
