# shophine-p0
## Word Count
   
### Sub-project 1:
Pick top 40 words across all documents with largest word count
* Drop words with total count less than 2 across all documents
* Words should be case-insensitive
* Store the output in sp1.json file

### Sub-project 2:
Do the same as Sub-project 1 and also filter out words that are provided in stopword.txt file
* Words in stopword.txt must be dropped
* Words should be case-insensitive
* Store the output in sp2.json file

### Sub-project 3:
Remove the trailing punctuations from the word such that first or last character of the word is not a punctuation.
* List of the punctuations .,:;'!?
* Discard word with one character and then trim the word
* Words in stopword.txt must be dropped
* Words should be case-insensitive
* Pick top 40 words
* Store the output in sp3.json file

### Sub-project 4:
Calcuate TF-IDF values for every word and pick top 5 words from each document
Remove the trailing punctuations from the word such that first or last character of the word is not in the punctuation list.
* Words should be case-insensitive
* Words in stopword.txt must be dropped
* Discard word with one character
* Strip out leading or trailing punctuation
* Compute TF-IDF values
* Output should have 5 * N entries where N is the no. of documents
* Store the output in sp4.json file

