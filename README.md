# Arabic-Dialects-Dataset
Arabic tweets, posts and comments in 5 Arabic dialects represent as follows :
4834 Tunisian
4834 MGH
4832 GLF
4832 LEV
4830 EGY
The dataset have 2 columns "Sentence" and "Dialect"

These data are presented in these 2 .xlsx files the first "CleanedDataset.xlsx" file contains the following pre-processing :
-Rmove "arabic" Stop Words
-Remove hashtag
-Remove punctuation
-Normalize
-Remove repeating char
-Stemming
-Replace @username with empty string
-Remove Links
-Balance dialect numbers
-Tokenize the Sentences


and the second "CleanedWithoutTokenizer.xlsx"
contains the same cleaning and preprocessing procedure without removing stop words and without tokenize
