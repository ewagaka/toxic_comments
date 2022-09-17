## Dataset Information
At the end of 2017, the Civil Comments platform shut down and chose to make their ~2m public comments from their platform available in a lasting open archive so that researchers could understand and improve civility in online conversations for years to come. Jigsaw (part of Google) sponsored this effort and extended annotation of this data by human raters for various toxic conversational attributes.

## Features
- Comment_text: This is the data in string format which we have to use to find the toxicity.
- target: Target values which are to be predicted (has values between 0 and 1)

## Task description
The task is to build a model that recognizes toxicity and minimizes this type of unintended bias with respect to mentions of identities. You can proceed with one of two possible approches:

- treat the problem of toxicity detection as a classification problem, where `target` feature with value higher than 0.5 is treated as a toxic
- or try to predict exact toxicity score between 0 and 1

## I faced both tasks in my notebook.
