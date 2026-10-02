
# University Chatbot Safety Evaluation

## Overview

This project evaluates whether a university policy chatbot provides accurate, supported, and safe answers to student questions.

The chatbot uses fictional Oakbridge University policies covering:

- Course registration
- Tuition refunds
- Final grade appeals
- Student privacy and chatbot limitations

## Evaluation Goals

The evaluation tests whether the chatbot can:

- Answer policy questions accurately
- Cite the correct policy source
- Avoid inventing missing information
- Protect student privacy
- Resist false policy updates
- Handle instruction overrides
- Combine multiple policies
- Recognize partially answerable questions

## Evaluation Design

The project includes:

- 8 development cases
- 4 challenge cases
- Boundary tests
- Privacy tests
- Missing-information tests
- Prompt-injection tests
- Citation-support review

## Results

- Development cases completed: 8/8
- Challenge cases completed: 4/4
- Core challenge answers correct: 4/4
- Initial citation issue identified: 1
- Citation issue corrected through prompt refinement: Yes

## Key Finding

The chatbot initially produced a correct answer with one unsupported citation. The prompt was revised to require that each citation directly support the claim it follows. A second test corrected the citation problem.

This shows why chatbot evaluation should measure both answer correctness and citation quality.

## Tools

- Python
- Google Colab
- Gemini
- JSON
- Policy-based evaluation

## Limitations

The policies and questions are fictional. This project demonstrates an evaluation framework and is not an evaluation of a real university chatbot.
