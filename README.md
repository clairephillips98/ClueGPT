Using the GPT API, myself and a partner created an LLM based crosword clue generator.

The ClueGPT model takes in a crossword clue, the length of the answer and known letters in the answer and outputs several additional clues.

The ClueGPT model implements forced chain of thought prompting along uses hard coded rules to validate the LLM chain of thought before outputing an answer.
