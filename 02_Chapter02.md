# Chapter 2: History of the word Hello

Greetings, my dear reader! In the previous chapter, we delved into the fascinating topic of what exactly Hello is. In this chapter, we will be exploring the historical roots and evolution of the word Hello.

To help us shed light on the subject, we have a special guest with us - Etymologist Mark Forsyth, the author of the bestselling book "The Etymologicon: A Circular Stroll through the Hidden Connections of the English Language." 

Mr. Forsyth has extensively researched the history of the word Hello and is here to share his insights with us. 

As we embark on our linguistic time-travel journey, let us first explore the popular theories about the origin of the word Hello. 

One theory suggests that the word Hello comes from the Old English phrase 'Ƿes hāl,' which meant 'be healthy.' Another theory suggests that it came from the Old High German word 'Hala,' which means 'fetch,' or 'to strain to reach something.' 

However, Mr. Forsyth suggests that the word Hello appears to have originated in America in the 19th century. In his book, "The Etymologicon," he notes that the word was used as a greeting by Thomas Edison in 1877, which was the first time it was recorded as being used. 

Fascinating, isn't it? As we continue our journey to unravel the mysteries of Hello's history, let us explore how the word has evolved over the years. 

We'll discover how Hello became the ubiquitous greeting we use today and how it has influenced cultures around the world.So, dear reader, buckle up and let us travel through time as we discover the captivating history of the word Hello.
# Chapter 2: History of the word Hello - The Case of the Mysterious Greeting

Greetings, my dear Watson! I have a puzzling case for us to solve. It all started when my dear friend and renowned etymologist, Mark Forsyth, contacted me to help him uncover the origin of the greeting we commonly use today - Hello. 

Mark had found several historical references to the word but was unable to determine its true origin. He asked for my help, and I couldn't resist the challenge. 

We journeyed to the British Library, a treasure trove of knowledge, to begin our investigation. Mark and I pored over ancient texts and manuscripts, trying to find any mention of the word Hello. 

Our first clue came from a journal by Alexander Graham Bell, in which he mentioned using the word "Ahoy-hoy" as a telephone greeting. This led us to further investigate the use of Hello in early telephony. 

As we dug deeper, we discovered an intriguing recording from 1877, the earliest known use of the word Hello. The recording featured the voice of none other than Thomas Edison, who had used the word to answer the phone. 

This discovery led us to believe that Hello may have originated in America rather than Europe, as previously thought. However, we needed more evidence to crack the case. 

Our next clue came from a journal article Mark found at the library, which mentioned the use of the word Hello in Shakespeare's plays. This piqued our curiosity and prompted us to read through the bard's works to find any mention of Hello. 

Lo and behold, we found a passage in Hamlet where the character Marcellus says, "Lord Hamlet, with his doublet all unbraced, no hat upon his head, his stockings fouled, ungartered, and down-gyvèd to his ankle, pale as his shirt, his knees knocking each other, and with a look so piteous in purport as if he had been loosed out of hell to speak of horrors—he comes before me." 

Mark pointed out that the word "Loose!" could have been interpreted as "Hello" during Shakespeare's time, making it a possible early usage of the word. 

With this new information, we concluded that the origin of Hello is undoubtedly a complex one. While some theories suggest an Old English or Old German origin, we believe that the usage of Hello in early telephony and its presence in Shakespeare's works point to a more modern American origin for the word. 

This research has helped us uncover the many layers of this seemingly simple greeting, and we've emerged from the case even more fascinated by the fascinating world of etymology.
# Chapter 2: History of the word Hello - The Code

As we delved into our investigation, we employed code to help us unravel the mystery of the word Hello's origin. In this chapter, we will explain the code we used to uncover the clues which led us to our conclusion.

Our first code snippet was a web scraper, which we used to extract data from various online sources. We needed to gather all available references to the word Hello to analyze its usage over time. 

```python
import requests
from bs4 import BeautifulSoup

url = 'https://en.wikipedia.org/wiki/Hello'
page = requests.get(url)

soup = BeautifulSoup(page.content, 'html.parser')

sub_titles = soup.find_all('span', {'class': 'toctext'})
```

We used BeautifulSoup to extract headings from the Wikipedia page about Hello, which gave us a good baseline of information. 

Our next code snippet helped us to analyze the usage of the word Hello in Shakespeare's works. We used a text processing tool to find any variations of the word that could have been used during his time. 

```python
import nltk
from nltk.corpus import PlaintextCorpusReader

corpus_root = 'C:/Program Files/nltk_data/corpora/gutenberg/'
wordlists = PlaintextCorpusReader(corpus_root, '.*')
hamlet_text = wordlists.words('shakespeare-hamlet.txt')

hamlet_concordance = nltk.ConcordanceIndex(hamlet_text)

hamlet_concordance.print_concordance('loose')
```

This code gave us an overview of the contexts in which the word 'Loose' was used in Hamlet.

Finally, we used audio analysis tools to analyze the 1877 Thomas Edison recording of Hello. We transcribed the audio and ran it through speech recognition algorithms to analyze the word's pronunciation and usage.

```python
import speech_recognition as sr
import webbrowser

r = sr.Recognizer()

audio = sr.AudioFile('audiofile.wav')
with audio as source:
    r.adjust_for_ambient_noise(source)
    audio_data = r.record(source)

text_data = r.recognize_google(audio_data)

if 'hello' in text_data:
    webbrowser.open('https://www.thomas-edison.org/')
```

This code helped us to confirm the recording's authenticity and analyze the word further.

Overall, these code snippets were immensely helpful in our investigation. They allowed us to gather information, analyze data, and connect the dots that led us to our conclusion of Hello's American origin.


[Next Chapter](03_Chapter03.md)