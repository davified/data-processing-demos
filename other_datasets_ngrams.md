# N grams dataset

Data source: http://storage.googleapis.com/books/ngrams/books/datasetsv2.html

**What is an n-gram?**: an n-gram is a contiguous sequence of n items from a given sample of text or speech. The items can be phonemes, syllables, letters, words or base pairs according to the application. Example: 
- 1-gram of "Lorem ipsum dolor sit amet" => (Lorem) (ipsum) (dolor) (sit) (amet)
- 2-gram of "Lorem ipsum dolor sit amet" => (Lorem ipsum) (ipsum dolor) (dolor sit) (sit amet)
**What does the dataset look like?**: 
```
| Word         | Year of Publication  | Total number of times   | Total number of books  | 
|              |                      | the word was seen       | containing the word    |
| ------------ | ---------------------| ------------------------| -----------------------|     
| A'Aang_NOUN  | 1879                 | 45                      | 5                      |     
| A'Aang_NOUN  | 1882                 | 5                       | 5                      |
...
| A'Aang_NOUN  | 1879                 | 45                      | 5                      |     
| A'Aang_NOUN  | 1882                 | 5                       | 5                      |
...
| bearer_NOUN  | 2007                 | 51220                   | 23061                  |
| bearer_NOUN  | 2008                 | 78088                   | 36658                  |
...
| bearers.2    | 1842                 | 1                       | 1                      |
| bearers.2    | 1875                 | 3                       | 3                      |
```
**


