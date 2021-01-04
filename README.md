# Gemastik13/Twitter Sentiment Analysis

Analisis sentimen tweet dari twitter yang mempunyai hashtag #RUUPKS atau sejenisnya. Langkah-langkah dalam analisis sentimen pada kode ini adalah:
1. Data mining dari twitter menggunakan tweepy
2. Data cleaning yang terdiri dari:
- Preprocessing tweet untuk menghapus kata yang tidak dibutuhkan seperti kata yang mengandung hashtag,tanggal,usernames dan emoji.
- Mengganti beberapa kata tidak baku dengan kata bakunya
- Lemmatize 
3. Menggunakan bag of words dan TFIDF untuk mendapatkan dataframe baru sebelum dimasukkan kepada model machine learning
4. Menggunakan model: Naive bayes,random forest, SGD, dan word2vec untuk memprediksi sentimen dari sebuah tweet
5. Menilai performa model dengan ROC AUC dan confusion matrix
