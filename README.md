# English_to_Hinglish_translation_model

Task : Create a Hinglish translation from English text. The text should sound natural and also
convert all the difficult words and phrases in English to Hinglish. This converted text should
be easy to understand for even a non-native Hindi speaker

## Project Aim:
 Develop a translation model capable of generating Hinglish text that closely resembles spoken Hindi language patterns.

Retain certain English words to improve clarity, especially for non-native Hindi speakers.

Ensure that the Hinglish translations accurately convey the meaning of the original English sentences.

## Code Component
Translation Model: This core component utilizes NLTK for text processing and leverages the Google Translate API to convert English sentences into Hinglish.

Noun Extraction: We have included a function that identifies and extracts nouns from input sentences using NLTK.

Translation Function: Another function makes use of the Google Translate API to translate English sentences into Hindi.

Replacement Logic: The project includes a function for replacing nouns in the Hindi translation with their English counterparts, while still retaining certain words in English for clarity

## How to use Code
Clone the Repository: Clone this repository to your local machine using the following command:


Install Dependencies: 

!pip install nltk
!pip install googletrans==4.0.0-rc1
Run the Code: Execute the code to translate English text into Hinglish. 

## Sample Output
