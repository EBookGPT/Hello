# Chapter 3: Different Ways to Say Hello

Greetings, dear readers! Welcome to the third chapter of our book about Hello. In the previous chapter, we explored the fascinating history of the word Hello. Today, we are going to delve into the various ways people greet each other around the world.

To help us in our investigation, we have a very special guest: a linguist, who has dedicated years of their life to the study of languages and their unique features. With their vast knowledge, our linguist friend will help us understand the nuances of various forms of Hello, and the cultural and social contexts in which they are used.

Let's start our journey by taking a look at some of the most common ways to say Hello in different languages:

## Common Ways to Say Hello

- Hola (Spanish)
- Bonjour (French)
- Hallo (German)
- Konnichiwa (Japanese)
- Ni hao (Mandarin)
- Ciao (Italian)
- As-salamu alaykum (Arabic)

Each of these words carries cultural and linguistic significance, and our linguist friend will help us unpack all of these as we go along. 

## Nonverbal Ways to Say Hello

In addition to spoken words, people also have many nonverbal ways of greeting each other. From a simple nod of the head to a full-blown hug or kiss on the cheek, there are many ways to communicate a friendly greeting without uttering a word. 

## Hello, World!

Of course, we cannot talk about different ways to say Hello without mentioning Hello, World! This is a staple of computer programming, used by programmers worldwide to test their code and communicate a basic greeting to users. Here is an example of a "Hello, World!" program in Python:

```python
print("Hello, World!")
```

In conclusion, the ways in which people say Hello reflect both their linguistic traditions and their cultural values. By exploring these differences, we can not only learn more about the ways in which people connect with each other but also gain a deeper appreciation for the richness of human language and culture.
# Chapter 3: Different Ways to Say Hello

It was a cool autumn day in London, and Sherlock Holmes was feeling restless. He had been working on a particularly difficult case for weeks, and his mind was in need of a break. Just then, a visitor arrived at his doorstep- it was our special guest for today, a linguist. 

"Good morning, Mr. Holmes," the linguist said. "I've come to talk to you about a matter of great urgency."

"Please, do sit down, and tell me more," Sherlock said with a nod.

The linguist began to explain the situation. "You see, Mr. Holmes, there have been a series of strange greetings that have been reported in the different sectors of London. They include gestures, sounds, and phrases that are unfamiliar to the local populations. It appears as if someone is deliberately trying to confuse and disorient the people by using these unfamiliar greetings."

Sherlock Holmes rubbed his chin thoughtfully. "Do you have any examples of these greetings?"

"Yes, I've collected several recordings of these greetings," the linguist said, producing a small recording device from their pocket. "Take a listen."

Sherlock put on the headphones and listened to the different greetings one by one. He recognized some, like "ni hao" and "as-salamu alaykum", but others were entirely unfamiliar.

"This is indeed a curious case," Sherlock said, handing back the headphones. "What do you suggest we do?"

The linguist presented their findings, "I've done some research and discovered that these unusual greetings are connected to the origins and culture of the speakers. My theory is that the perpetrator may be using these greetings to draw attention to their knowledge of different cultures."

Sherlock nodded in agreement. "Very well. The first step in solving this case is to identify the origins and meanings of each of these greetings. Then, we must connect them to members of the community who have knowledge of those cultures."

With the linguist's help, they compiled a list of known origins and found that each of the greetings belonged to a different language and culture. They then went on to interview different people in their corresponding neighborhoods who were proficient in these languages.

After hours of questioning and cross-referencing, they finally found their culprit- a young prankster who had studied languages for fun and had decided to play a harmless joke on the people of London.

"You're under arrest," Sherlock declared, flashing his famous grin as the police arrived to take the prankster away.

And with that, the case was closed, and Sherlock Holmes learned a great deal about the many ways to say Hello around the world.
During the course of their investigation, Sherlock Holmes and our guest, the linguist, used a variety of tools and techniques to help them identify the origins and meanings of the unusual greetings that had been reported around London. In particular, they relied on code to assist them in their analysis.

One of the most powerful tools in their arsenal was Python, a popular programming language that is widely used for data analysis, machine learning, and other tasks that require the manipulation of data. Python's extensive library of modules, which include everything from natural language processing tools to advanced statistical analysis packages, was invaluable in helping to crack this case.

One of the code snippets they used to help identify the origins of the unfamiliar greetings was a simple script that used the Google Cloud Translate API to automatically detect the language of each greeting based on a provided text. Here's an example of how that code might look:

```python
from google.cloud import translate_v2 as translate

def detect_language(text):
    translator = translate.Client()
    result = translator.detect_language(text)
    return result['language']

greetings = ["Konnichiwa", "Bonjour", "Ciao", "Ni hao", "As-salamu alaykum"]
for greeting in greetings:
    print(f"The detected language of '{greeting}' is '{detect_language(greeting)}'.")
```

In this script, the `detect_language()` function uses the `translate_v2` module from the Google Cloud libraries to detect the language of a given text. This function is called within a loop that iterates through a list of greetings and prints out the detected language of each greeting.

Another code snippet that proved useful was a set of regular expressions (regex) that the duo used to search through their recordings of the unfamiliar greetings for common patterns or markers that might provide clues to their origins. Here's an example of how that code might look:

```python
import re

recordings = ["file_1.wav", "file_2.wav", "file_3.wav"]
pattern = re.compile(r"\b(dau|schön|habanero)\b", re.IGNORECASE)

for recording in recordings:
    with open(recording, "rb") as f:
        data = f.read()
    
    matches = pattern.findall(data)
    
    if matches:
        print(f"Matches found in {recording}: {matches}")
    else:
        print(f"No matches found in {recording}.")
```

In this code, the `re` module is used to define a regular expression pattern that searches for specific words or phrases within the binary data of the recorded greetings. This pattern is then used within a loop that iterates through a list of recordings, reading in the binary data of each file and searching for any matches to the pattern. If there are any matches, the script prints out the name of the file and the specific matches found.

Overall, the use of code was critical in helping Sherlock Holmes and our linguist friend to identify the origins and meanings of the unusual greetings, and ultimately to solve the case. Without the powerful tools provided by Python and its libraries, they may never have been able to crack the code behind the prankster's elaborate scheme.


[Next Chapter](04_Chapter04.md)