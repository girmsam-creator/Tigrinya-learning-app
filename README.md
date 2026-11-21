# Arkitigrinya

A free mobile-friendly web app for practising everyday Tigrinya: vocabulary cards, quizzes, sentence building, reading and listening comprehension, tables of all words and sentences, and Fidel (Ge'ez script) practice.

**Open the app:** https://girmsam-creator.github.io/Tigrinya-learning-app/

The interface is in Finnish. The content is Tigrinya (phonetic spelling and Ge'ez script) with Finnish translations.

## What is inside

- Flashcards with a spaced repetition system (cards you miss come back more often)
- Quiz mode
- Mixed test (Koe tab): first choose one or more handouts (Handout 1 to 7, Class 4 conversations, your own additions), then one or more question types (words, sentences, conversations). 10 to 60 multiple choice questions (no typing), with a score by category and a retry for mistakes. In content.txt you can tag your own conversations with a handout, for example `#CONVERSATION Title | H3`, and sentences with `ph | fi | H3`
- Conversation practice (Puhu tab): the app asks and you answer, you ask and check the model, or read whole dialogues
- Sentence builder using patterns from the course handouts
- Reading comprehension texts
- Listening practice (read aloud by a partner or your own recording, since no audio is included)
- Tables tab (Taulukot): every word, sentence and conversation listed by handout like in the handouts (Finnish, pronunciation, Ge'ez), with search, filters by type, and a Hide option for self-testing (tap a row to reveal it). The Fidel table (26 letter families) and Fidel quiz are under the chip Fidel-kirjaimet

Your progress is saved only in your own browser on your own device. Nothing is sent anywhere.

## Add to your iPhone or Android home screen

- **iPhone (Safari):** Share, then Add to Home Screen
- **Android (Chrome):** Menu, then Add to Home screen

## Adding your own content

All content lives in `content.txt`. Edit it on GitHub (pencil icon), save with Commit changes, and the app picks up the new words and sentences after a few minutes. Reload the page to see them.

```
## My group | My list name
phonetic | ge'ez (can be empty) | meaning
Kubaya | ኩባያ | cup

#SENTENCES
Kubaya habini | give me a cup |

#READING Title
Text on one or more lines.
? question | answer

#LISTENING Title
Text to be read aloud.
? question | answer

#CONVERSATION Title
A: question | meaning
B: answer | meaning
```

Lines starting with `//` are comments. Do not use the `|` character inside a word or sentence, because it separates the fields.

## Files

- `index.html`: the app
- `content.txt`: all words, sentences, texts and Fidel data
- `README.md`: this file
- `SUPPORT.md`: help and how to support the project

## Source and rights

The vocabulary and phrases are based on Handouts 1 to 7 and the Class 4 conversation sheet of the course "Exploring with Selam & Senai, Tigrinya 101". Spellings are copied from the handouts, and spelling varies between handouts. The app is for personal study and is not an official product of the course. If you are a rights holder and have concerns, please contact the maintainer (see SUPPORT.md).

## Author

Made by Samuel Girmay, university teacher at Aalto University, as a personal learning project.

Mistakes in the Tigrinya are possible. Please report them (see SUPPORT.md) so they can be corrected.
