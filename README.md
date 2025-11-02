# Assignment-4
NAME : Uzair Ahmed Khan
STUDENR ID : 700774419
#  NLP Text Processing 
  
The code demonstrates how to:
- Break a sentence into **tokens** (individual words)
- Remove **stopwords** (like "is", "the", "in")
- Apply **lemmatization** to get the base form of words
- Keep only **nouns** and **verbs** using part-of-speech (POS) tags  

It’s a small but essential example of how modern Natural Language Processing (NLP) works behind the scenes.

---

##  Example Used

Here’s the input sentence used in the script:

> “John enjoys playing football while Mary loves reading books in the library.”

After processing, the program gives us clean and meaningful words that represent the core actions and objects in the sentence.

---

##  What the Script Does (Step-by-Step)

1. **Tokenization:**  
   Splits the text into smaller pieces (tokens).  
   Example → `["John", "enjoys", "playing", "football", ...]`

2. **Stopword Removal:**  
   Removes common words that don’t add much meaning.  
   Example → removes “in”, “the”, “while”, etc.

3. **Lemmatization:**  
   Converts words to their base form.  
   Example → `"enjoys"` → `"enjoy"`, `"playing"` → `"play"`

4. **POS Filtering:**  
   Keeps only **verbs** (actions) and **nouns** (people, places, things).  
   Example → `"John"`, `"enjoy"`, `"football"`, `"Mary"`, `"love"`, `"book"`, `"library"`





