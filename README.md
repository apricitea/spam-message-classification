# Spam Message Classification 

## Data Source

The dataset consists of 1.143 text obtained from SMS (Short Message Service) in Indonesian language. The dataset has 574(50.22%) normal messages and 569 (49.78%) spam messages.

[The dataset can be accessed here!](https://gist.github.com/agtbaskara/a1a7017027cc1df9d35cf06e1e5575b7)

## Text Preprocessing 

- Convert to lowercases
- Remove punctuations
- Text normalization (replacing slang words)
- Stemming (reducing inflected words to their word stem, base or root form
- Remove stopwords
- Remove numbers
- Remove whitespace

## Classification Model

The classification model used in this project are Singular Value Decomposition (SVM), Logistic Regression, and Extreme Gradient Boosting (XGB). Hyperparameter tuning will also be performed to improve the model accuracy using Grid Search with 10 folds. Model will be validated using the test dataset and several metrics like Confusion Matrix, Classification Report, and AUC/ROC Score & Curve available in Metrics from the Scikit Learn library. 

## Result

<img src="https://i.imgur.com/CIrxWnP.png"/>

<img src="https://i.imgur.com/Y2rKw8T.png"/>

## Reference

Agrawal R, Srikant R.1995. Mining Sequential Pattern.International Conference on Data 	Engineering; 1995 Mar; Taipei, Taiwan (TW).hlm 3-14

Athaillah M, Azhar Y, Munarko Y. 2020. Perbandingan metode klasifikasi berita hoaks berbahasa indonesia berbasis mesin. Jurnal Repositor. 2(5): 675-682. doi:  10.22219/repositor.v2i5.692.Tersedia pada: http://repositor.umm.ac.id/index.php/repositor/article/view/692/92. 

Ahola J. 2001. Mining Sequential Pattern (version 1.0) [Internet].[diunduh 2013 Okt 31]; 14-15:Espoo(FI). Tersedia pada:http://www.vtt.fi/inf/julkaisut/muut /2001.

Constantin Y, Darusakam U, Nathasia N D. 2019. Aplikasi personal assistance berbasis voice command pada sistem operasi android dengan nlp. Journal of Information Technology and Computer Sciense. doi: 10.31328/jointecs.v5i2.1246. Tersedia pada: http://publishing-widyagama.ac.id/ejournal-v2/index.php/jointecs/article/view/1246.

Ghawi R, Pfeffer J. 2019. Efficient Hyperparameter Tuning with Grid Search for Text Categorization using kNN Approach with BM25 Similarity. Open Computer Science. 9(1): 160-180. Tersedia pada: https://doi.org/10.1515/comp-2019-0011. 

Han J, Kamber M. 2006. Data Mining Concepts and Techniques Second Edition. San 	Fransisco (US): Morgan Kaufmann Publisher.

Herwijayanti B, Ratnawati D E, Muflikhah L. 2018. Klasifikasi berita online dengan menggunakan pembobotan tf-idf dan consine similarity. Jurnal Pengembangan Teknologi Informasi dan Ilmu Komputer. 2(1): 306-312. Tersedia pada: https://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/796/309. 

Hosmer DW, Lemeshow S. 2000. Applied Logistic Regression. 2nd Edition. New York (US): John Willey and Sons.

Jumeilah F S. 2017. Penerapan support machine machine (svm) untuk pengkategorian penelitian. Jurnal Rekayasa Sistem dan Teknologi Informasi. 1(1): 19–25. doi: 10.29207/resti.v1i1.11. Tersedia pada: http://www.jurnal.iaii.or.id/index.php/RESTI/article/view/11 

Karo I M K. 2020. Implementasi metode xgboost dan feature importance untuk klasifikasi pada kebakaran hutan dan lahan. Journal of SOftware Engineering, Information adn Communication Technology. 1(1): 10–16. doi: 10.17509/seict.v1i1.29347. Tersedia pada: https://ejournal.upi.edu/index.php/SEICT/article/view/29347.

Na'am J. 2015. Pembobotan kata sms spam. Jurnal Ilmiah Media Sisfo. 9(2):321-328. Tersedia pada: http://ejournal.stikom-db.ac.id/index.php/mediasisfo/article/view/206.

Normawati D, Prayogi SA. 2021. Implementasi naive bayes classifier dan confusion matrix pada analisis sentimen berbasis teks pada twitter. Jurnal Sains Komputer dan Informatika. 5(2): 697-711. Tersedia pada: http://ejurnal.tunasbangsa.ac.id/index.php/jsakti/article/view/369.

Pei J et al. 2004. Mining Sequential patterns by pattern-growth: The prefixspan approach [Internet].[diunduh 2013 Okt 31];16:1424-1440. Tersedia pada: http://ieeexplore.ieee.org

Pramudita HR. 2014. Penerapan algoritma stemming Nazief & Adriani dan similarity pada penerimaan judul thesis. Jurnal Ilmiah DASI. 15(2):15–19. Tersedia pada: https://ojs.amikom.ac.id/index.php/dasi/article/view/213. 

Wahid D H, Azhari S N. 2016. Peringkasan sentimen esktratif di twitter menggunakan hybrid tf-idf dan cosine similarity.  Indonesian Journal of Computing and Cybernetics Systems.10(2): 207-218. doi: 10.22146/ijccs.16625. Tersedia pada: https://journal.ugm.ac.id/ijccs/article/view/16625/11694. 
