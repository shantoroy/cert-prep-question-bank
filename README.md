# Certification Preparation Question Bank
Central Repository of Question banks for Industry Certifications where everyone can contribute.
All questions are stored in JSON files.

## Resources

### Resources
- [Certification Preparation Portal (New)](https://shantoroy.com/certprep/)
- [Related Blog Post](https://shantoroy.com/certification/certification-preparation-practice-questions/)

### Useful Tool to add questions to a file:
- [Question Bank Helper](https://github.com/shantoroy/certprep-question-bank-helper)

Example entry for a collection (Question, Options, Answers, Explanation):

Example format for single choice answers
```json
{
        "id": 1,
        "text": "A company plans to develop an ML model using Amazon SageMaker and needs a solution to share and manage variables for model development across multiple teams. Which SageMaker feature fulfills these requirements?",
        "options": [
            {
                "id": "a",
                "text": "Amazon SageMaker Feature Store"
            },
            {
                "id": "b",
                "text": "Amazon SageMaker Clarify"
            },
            {
                "id": "c",
                "text": "Amazon SageMaker Model Cards"
            },
            {
                "id": "d",
                "text": "Amazon SageMaker Data Wrangler"
            }
        ],
        "correctAnswers": [
            "a"
        ],
        "explanation": "Amazon SageMaker Feature Store is designed to store, manage, and share features (variables) for machine learning models across teams.",
        "multipleSelect": false
    }
```

Example format for multi-select answers

```json
{
        "id": 21,
        "text": "Which of the following AWS AI services allow fine-tuning of foundation models (FMs) using proprietary or custom datasets? (Select all that apply)",
        "options": [
            { "id": "a", "text": "Amazon Bedrock" },
            { "id": "b", "text": "Amazon SageMaker" },
            { "id": "c", "text": "Amazon Comprehend" },
            { "id": "d", "text": "AWS DeepComposer" },
            { "id": "e", "text": "Amazon Rekognition" }
        ],
        "correctAnswers": ["a", "b"],
        "explanation": "Amazon Bedrock and Amazon SageMaker support fine-tuning foundation models with custom datasets. Amazon Comprehend is for NLP, DeepComposer is for AI-generated music, and Rekognition is for image/video analysis, none of which support FM fine-tuning.",
        "multipleSelect": true
    }
```


##  Contributing

* Fork the repository
* Create your feature branch (git checkout -b feature/amazing-feature)
* Commit your changes (git commit -m 'Add amazing feature')
* Push to the branch (git push origin feature/amazing-feature)
* Open a Pull Request