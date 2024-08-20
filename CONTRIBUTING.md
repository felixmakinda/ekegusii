# Contributing to Ekegusii Language Documentation Project

Thank you for your interest in contributing to the Ekegusii Language Documentation Project! Your contributions will help preserve and promote the use of Ekegusii for future generations.

## How to Contribute

1. **Fork the Repository**: Start by forking this repository to your GitHub account.
2. **Clone the Repository**: Clone your forked repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/ekegusii-language-documentation.git

    Create a New Branch: Create a branch for your contribution.

    bash

git checkout -b new-feature

Add Your Contribution: Add new words, proverbs, or grammar rules using the provided templates.
Commit Your Changes: Commit your changes with a descriptive message.

bash

git commit -m "Added new Ekegusii words and proverbs"

Push to GitHub: Push your changes to your forked repository.

bash

    git push origin new-feature

    Submit a Pull Request: Submit a pull request to the original repository for review.

Guidelines for Contributions
Word Entries

Each word entry should follow this structure:

json

{
  "word": "Omoko",
  "definition": {
    "language": "Omonto onywomete omwana omino. Gose oyomwabo ase onywomete gose onywomire.",
    "english": "In-law. A sibling or cousin to your wife or husband."
  },
  "part_of_speech": "noun",
  "synonyms": [
    "Synonym1",
    "Synonym2"
  ],
  "example_sentence": "This is an example sentence using the word in Ekegusii.",
  "notes": "Any additional notes about the word."
}

    Word: The word in Ekegusii.
    Definition: An object containing the definition in both Ekegusii (optional) and English.
    Part of Speech: Indicate whether the word is a noun, verb, adjective, etc.
    Synonyms: A list of synonyms in Ekegusii (if any).
    Example Sentence: An example sentence using the word in context.
    Notes: Any additional notes, such as cultural context or usage.

Proverb Entries

Each proverb entry should follow this structure:

json

{
  "proverb": "EkegusiiProverb",
  "translation": "English translation of the proverb",
  "meaning": {
    "language": "Meaning in Ekegusii",
    "english": "Meaning in English"
  },
  "notes": "Any additional notes about the proverb."
}

    Proverb: The proverb in Ekegusii.
    Translation: The English translation of the proverb.
    Meaning: An object containing the meaning of the proverb in both Ekegusii and English.
    Notes: Any additional notes, such as regional variations or context.

Grammar Entries

Each grammar entry should follow this structure:

markdown

# Grammar Rule Example

## Rule Name
Description of the grammar rule.

### Examples
1. **Sentence Example 1:** Explanation of the example.
2. **Sentence Example 2:** Explanation of the example.

## Notes
Any additional notes about this grammar rule.

    Rule Name: The name of the grammar rule in English or Ekegusii.
    Description: A detailed description of the rule.
    Examples: Provide examples that illustrate the rule in use.
    Notes: Any additional notes or exceptions.

Testing Your Contributions

If you add or modify scripts, please test them to ensure they work as expected. If you're not sure how to do this, feel free to ask for help in your pull request.
Code of Conduct

Please note that this project is governed by a Code of Conduct. By participating, you are expected to adhere to this code. Please report unacceptable behavior to the project maintainers.
Getting Help

If you need help, feel free to open an issue on GitHub, and someone will assist you as soon as possible. Thank you for contributing to the preservation of the Ekegusii language!

yaml


---

This `CONTRIBUTING.md` file provides clear guidelines for contributors on how to add new wo
