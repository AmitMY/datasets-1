# newsqa

References:

*   [Code](https://github.com/huggingface/datasets/blob/master/datasets/newsqa)
*   [Huggingface](https://huggingface.co/datasets/newsqa)


## combined-csv


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:newsqa/combined-csv')
```

*   **Description**:

```
NewsQA is a challenging machine comprehension dataset of over 100,000 human-generated question-answer pairs. Crowdworkers supply questions and answers based on a set of over 10,000 news articles from CNN, with answers consisting of spans of text from the corresponding articles.
```

*   **License**: NewsQA CodeCopyright (c) Microsoft CorporationAll rights reserved.MIT LicensePermission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.© 2020 GitHub, Inc.
*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 119633

*   **Features**:

```json
{
    "story_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "story_text": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "question": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "answer_char_ranges": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```



## combined-json


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:newsqa/combined-json')
```

*   **Description**:

```
NewsQA is a challenging machine comprehension dataset of over 100,000 human-generated question-answer pairs. Crowdworkers supply questions and answers based on a set of over 10,000 news articles from CNN, with answers consisting of spans of text from the corresponding articles.
```

*   **License**: NewsQA CodeCopyright (c) Microsoft CorporationAll rights reserved.MIT LicensePermission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.© 2020 GitHub, Inc.
*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 12744

*   **Features**:

```json
{
    "storyId": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "text": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "type": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "questions": {
        "feature": {
            "q": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "isAnswerAbsent": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            },
            "isQuestionBad": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            },
            "consensus": {
                "s": {
                    "dtype": "int32",
                    "id": null,
                    "_type": "Value"
                },
                "e": {
                    "dtype": "int32",
                    "id": null,
                    "_type": "Value"
                },
                "badQuestion": {
                    "dtype": "bool",
                    "id": null,
                    "_type": "Value"
                },
                "noAnswer": {
                    "dtype": "bool",
                    "id": null,
                    "_type": "Value"
                }
            },
            "answers": {
                "feature": {
                    "sourcerAnswers": {
                        "feature": {
                            "s": {
                                "dtype": "int32",
                                "id": null,
                                "_type": "Value"
                            },
                            "e": {
                                "dtype": "int32",
                                "id": null,
                                "_type": "Value"
                            },
                            "badQuestion": {
                                "dtype": "bool",
                                "id": null,
                                "_type": "Value"
                            },
                            "noAnswer": {
                                "dtype": "bool",
                                "id": null,
                                "_type": "Value"
                            }
                        },
                        "length": -1,
                        "id": null,
                        "_type": "Sequence"
                    }
                },
                "length": -1,
                "id": null,
                "_type": "Sequence"
            },
            "validated_answers": {
                "feature": {
                    "s": {
                        "dtype": "int32",
                        "id": null,
                        "_type": "Value"
                    },
                    "e": {
                        "dtype": "int32",
                        "id": null,
                        "_type": "Value"
                    },
                    "badQuestion": {
                        "dtype": "bool",
                        "id": null,
                        "_type": "Value"
                    },
                    "noAnswer": {
                        "dtype": "bool",
                        "id": null,
                        "_type": "Value"
                    },
                    "count": {
                        "dtype": "int32",
                        "id": null,
                        "_type": "Value"
                    }
                },
                "length": -1,
                "id": null,
                "_type": "Sequence"
            }
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    }
}
```



## split


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:newsqa/split')
```

*   **Description**:

```
NewsQA is a challenging machine comprehension dataset of over 100,000 human-generated question-answer pairs. Crowdworkers supply questions and answers based on a set of over 10,000 news articles from CNN, with answers consisting of spans of text from the corresponding articles.
```

*   **License**: NewsQA CodeCopyright (c) Microsoft CorporationAll rights reserved.MIT LicensePermission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.© 2020 GitHub, Inc.
*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'test'` | 5126
`'train'` | 92549
`'validation'` | 5166

*   **Features**:

```json
{
    "story_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "story_text": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "question": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "answer_token_ranges": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```


