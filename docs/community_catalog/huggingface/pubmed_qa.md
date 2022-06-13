# pubmed_qa

References:

*   [Code](https://github.com/huggingface/datasets/blob/master/datasets/pubmed_qa)
*   [Huggingface](https://huggingface.co/datasets/pubmed_qa)


## pqa_labeled


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:pubmed_qa/pqa_labeled')
```

*   **Description**:

```
PubMedQA is a novel biomedical question answering (QA) dataset collected from PubMed abstracts.
The task of PubMedQA is to answer research questions with yes/no/maybe (e.g.: Do preoperative
statins reduce atrial fibrillation after coronary artery bypass grafting?) using the corresponding abstracts.
PubMedQA has 1k expert-annotated, 61.2k unlabeled and 211.3k artificially generated QA instances.
Each PubMedQA instance is composed of (1) a question which is either an existing research article
title or derived from one, (2) a context which is the corresponding abstract without its conclusion,
(3) a long answer, which is the conclusion of the abstract and, presumably, answers the research question,
and (4) a yes/no/maybe answer which summarizes the conclusion.
PubMedQA is the first QA dataset where reasoning over biomedical research texts, especially their
quantitative contents, is required to answer the questions.
```

*   **License**: MIT License
Copyright (c) 2019 pubmedqa
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 1000

*   **Features**:

```json
{
    "pubid": {
        "dtype": "int32",
        "id": null,
        "_type": "Value"
    },
    "question": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "context": {
        "feature": {
            "contexts": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "labels": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "meshes": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "reasoning_required_pred": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "reasoning_free_pred": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            }
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    },
    "long_answer": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "final_decision": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```



## pqa_unlabeled


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:pubmed_qa/pqa_unlabeled')
```

*   **Description**:

```
PubMedQA is a novel biomedical question answering (QA) dataset collected from PubMed abstracts.
The task of PubMedQA is to answer research questions with yes/no/maybe (e.g.: Do preoperative
statins reduce atrial fibrillation after coronary artery bypass grafting?) using the corresponding abstracts.
PubMedQA has 1k expert-annotated, 61.2k unlabeled and 211.3k artificially generated QA instances.
Each PubMedQA instance is composed of (1) a question which is either an existing research article
title or derived from one, (2) a context which is the corresponding abstract without its conclusion,
(3) a long answer, which is the conclusion of the abstract and, presumably, answers the research question,
and (4) a yes/no/maybe answer which summarizes the conclusion.
PubMedQA is the first QA dataset where reasoning over biomedical research texts, especially their
quantitative contents, is required to answer the questions.
```

*   **License**: MIT License
Copyright (c) 2019 pubmedqa
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 61249

*   **Features**:

```json
{
    "pubid": {
        "dtype": "int32",
        "id": null,
        "_type": "Value"
    },
    "question": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "context": {
        "feature": {
            "contexts": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "labels": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "meshes": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            }
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    },
    "long_answer": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```



## pqa_artificial


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:pubmed_qa/pqa_artificial')
```

*   **Description**:

```
PubMedQA is a novel biomedical question answering (QA) dataset collected from PubMed abstracts.
The task of PubMedQA is to answer research questions with yes/no/maybe (e.g.: Do preoperative
statins reduce atrial fibrillation after coronary artery bypass grafting?) using the corresponding abstracts.
PubMedQA has 1k expert-annotated, 61.2k unlabeled and 211.3k artificially generated QA instances.
Each PubMedQA instance is composed of (1) a question which is either an existing research article
title or derived from one, (2) a context which is the corresponding abstract without its conclusion,
(3) a long answer, which is the conclusion of the abstract and, presumably, answers the research question,
and (4) a yes/no/maybe answer which summarizes the conclusion.
PubMedQA is the first QA dataset where reasoning over biomedical research texts, especially their
quantitative contents, is required to answer the questions.
```

*   **License**: MIT License
Copyright (c) 2019 pubmedqa
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 211269

*   **Features**:

```json
{
    "pubid": {
        "dtype": "int32",
        "id": null,
        "_type": "Value"
    },
    "question": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "context": {
        "feature": {
            "contexts": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "labels": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "meshes": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            }
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    },
    "long_answer": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "final_decision": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```


