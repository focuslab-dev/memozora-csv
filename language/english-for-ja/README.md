# English Vocabulary Builder 8000 (for Japanese Speakers)

## Description

This repository contains a TSV (Tab-Separated Values) file for efficiently learning the 8,000 most frequently used English words. The dataset is designed to be imported into [Memozora](https://memozora.com), a flashcard application for effective learning and memorization.

To learn how to import the data into Memozora, please check out [README.md](/README.md).

## Features

- Words are ordered from easiest to most difficult.
- Each entry includes a pair of English example sentences with English translations.
- Each example sentence introduces a new word, ensuring gradual vocabulary building.
- This set of quizzes adopts science-backed techniques such as *chunking and *comprehensible input.

\*Chunking: Learn phrases and collocations rather than isolated words to improve natural language use and memory retention.

\*Comprehensible input: Expose yourself to language content that's slightly above your current level, as proposed by linguist Stephen Krashen. This challenges you without overwhelming you.

## Data Source

The dataset is made from the "[BNC/COCA lists](https://www.eapfoundation.com/vocab/general/bnccoca/)" available on [eapfoundation.com](https://www.eapfoundation.com/).

## File Format

The TSV file is structured as follows:

1. English example sentence
2. English translation
3. Break-up of each words

Data Example:

```
She found the book.	彼女はその本を見つけた。	She (彼女) / found (見つけた) / the (その) / book (本)
Be kind to everyone.	みんなに親切にしてください。	Be (Be) / kind (親切な) / to (へ) / everyone (みんな)
Part of the team.	チームの一員	Part (部分) / of (の) / the (その) / team (チーム)Part of the team.
Tom and Jerry play.	トムとジェリーは遊ぶ。	Tom (トム) / and (そして) / Jerry (ジェリー) / play (遊び),
Let's go to school.	学校に行きましょう。	Let's (レッツ) / go (行こう) / to (へ) / school (学校)
```
