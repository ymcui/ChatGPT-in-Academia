**[中文](./README_ZH.md) | [English](./README.md)** 

# ChatGPT in Academia

As the development of natural language processing (NLP) technologies advances, Large Language Models (LLMs) such as ChatGPT have gained significant attention for their potential to aid in scientific writing. However, concerns have also been raised regarding the ethical implications and reliability of using LLMs in scientific writing.

**This repository is created to demonstrate the policies of different publishers and conferences towards the use of LLMs in scientific writing. This will help authors quickly understand what should you not do with LLM in scientific writing.**

Through this repository, we hope to facilitate an open and transparent discussion on the role of LLMs in scientific writing, and to promote responsible and ethical use of these technologies. 

*Feel free to create a PR if you have additional news to share!*


## Policy at a Glance

| Publishing Group / Venue | Latest Updated | Polishing own text | Literature Search | New Idea | ChatGPT as Author |
| ------------------------ | :------------: | :----------------: | :---------------: | :------: | :---------------: |
| Nature Portfolio         |  Jan 24, 2023  |         ⚠️          |         ⚠️         |    ⚠️     |         ❌         |
| Science                  |  Jan 26, 2023  |         ❌          |         ❓         |    ❓     |         ❌         |
| arXiv preprint           |  Jan 31, 2023  |         ⚠️          |         ❓         |    ❓     |         ❌         |
| Elsevier                 |      n/a       |         ✅          |         ❓         |    ❓     |         ❌         |
| ICML 2023                |   Jan, 2023    |         ✅          |         ❓         |    ❓     |         ❌         |
| ACL 2023                 |   Jan, 2023    |         ✅          |         ⚠️         |    ⚠️     |         ❌         |


✅ Allow to use (with clear official regulations)

❌ Not allowed (with clear official regulations)

⚠️ Use with caution (without clear official regulations)

❓ Unknown



## Publishing Groups

### Nature

**[20 Feb 2023] [How Nature readers are using ChatGPT](https://www.nature.com/articles/d41586-023-00500-8)**

- TLDR: Eighty percent of respondents have used AI chatbots — and 57% say they use it for ‘creative fun’.

**[17 Feb 2023] [How will AI change mathematics? Rise of chatbots highlights discussion](https://www.nature.com/articles/d41586-023-00487-2)**

- TLDR: Machine learning tools already help mathematicians to formulate new theories and solve tough problems. But they’re set to shake up the field even more.

**[03 Feb 2023] [ChatGPT: Five priorities for research](https://www.nature.com/articles/d41586-023-00288-7)**

- TLDR: Conversational AI is a game-changer for science.

**[24 Jan 2023] [Tools such as ChatGPT threaten transparent science; here are our ground rules for their use](https://www.nature.com/articles/d41586-023-00191-1)**

- TLDR: Nature Portfolio has established their rules for the use of LLM (such as ChatGPT). 1) LLM can not be listed as an author; 2) the use of LLM should be clearly described.

### Science (AAAS)

**[26 Jan 2023] [ChatGPT is fun, but not an author](https://www.science.org/doi/10.1126/science.adg7879)**

- TLDR: Text generated from AI, machine learning, or similar algorithmic tools cannot be used in papers published in *Science* journals, nor can the accompanying figures, images, or graphics be the products of such tools, without explicit permission from the editors.

### arXiv

**[31 Jan 2023] [arXiv policy for authors’ use of generative AI language tools](https://blog.arxiv.org/2023/01/31/arxiv-announces-new-policy-on-chatgpt-and-similar-tools/)**

- TLDR: 1) LLM can not be listed as an author; 2) irrespective of how the contents were generated, the authors should take the responsibilities; 3) report in their paper if generative AI was used for paper creating.

### Elsevier

**[Editorial Policy: The use of AI and AI-assisted Technologies in Scientific Writing](https://www.elsevier.com/about/policies/publishing-ethics)**

- TLDR: Elsevier has issued a policy in response to the increasing use of generative AI and AI-assisted technologies in content creation. 1) authors should disclose the use of AI and AI-assisted technologies in their manuscript and only use them to improve readability and language, not to replace key researcher tasks; 2) The authors are ultimately responsible for the contents of the work and should carefully review and edit the result of AI-generated content. 3) Authors should not list AI and AI-assisted technologies as an author or co-author and should ensure the work is original and does not infringe third party rights. 

## Conferences

### ICML 2023 (International Conference on Machine Learning)

TLDR: 

- The Large Language Model (LLM) policy for ICML 2023 prohibits text produced entirely by LLMs (i.e., “generated”). This does not prohibit authors from using LLMs for editing or polishing author-written text. 
- The LLM policy is largely predicated on the principle of being conservative with respect to guarding against potential issues of using LLMs, including plagiarism.
- The LLM policy applies to ICML 2023. We expect this policy may evolve in future conferences as we understand LLMs and their impacts on scientific publishing better. 

Source URL: https://icml.cc/Conferences/2023/llm-policy

### ACL 2023 (Annual Meeting of the Association for Computational Linguistics)

TLDR: 

- Light editing and polishing for grammatical corrections are allowed without explicit declaration.
- For literature search, prompting with new ideas, please use with caution and should make sure that relevant literatures are properly cited.
- ACL does not encourage the authors to entirely rely on LLM for paper content generation.
- For AI-assisted coding, the author should explicitly demonstrate its scope.

Source URL: https://2023.aclweb.org/blog/ACL-2023-policy/



## Anti-ChatGPT Tools

In order to identify whether the text is from AI-assisted engine (such as ChatGPT) or human, several tools are released, which might help in identifying potential plagiarism and academic misconduct. 

**💡NOTE: These tools are not entirely reliable at the moment based on my own experience.** 

**⚠️ WARNING: Use with caution, beware of data collection, especially for those PRIVATE data.**

### [GPTZero](https://gptzero.me)

TLDR: API that detects whether text was generated by AI. Accept both files and text input, and return probabilities on the sentence, paragraph, and document level.

Features:

- a minimum of 250 characters are required
- support pdf, docx, txt formats
- support API requests
- detailed scoring of the input text

### [OpenAI AI Text Classifier](https://platform.openai.com/ai-text-classifier)

TLDR: This is an official AI classifier from OpenAI to distinguish between AI-written and human-written text. 

Blog: https://openai.com/blog/new-ai-classifier-for-indicating-ai-written-text/

Features: 

- Requires a minimum of 1,000 characters, which is approximately 150 - 250 words.
- Five levels of results: very unlikely, unlikely, unclear if it is, possibly, or likely AI-generated