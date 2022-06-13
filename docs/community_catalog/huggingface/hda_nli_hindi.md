# hda_nli_hindi

References:

*   [Code](https://github.com/huggingface/datasets/blob/master/datasets/hda_nli_hindi)
*   [Huggingface](https://huggingface.co/datasets/hda_nli_hindi)


## HDA hindi nli


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:hda_nli_hindi/HDA hindi nli')
```

*   **Description**:

```
This dataset is a recasted version of the Hindi Discourse Analysis Dataset used to train models for Natural Language Inference Tasks in Low-Resource Languages like Hindi.
```

*   **License**: 
MIT License

Copyright (c) 2019 MIDAS, IIIT Delhi

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

*   **Version**: 1.1.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'test'` | 9970
`'train'` | 31892
`'validation'` | 9460

*   **Features**:

```json
{
    "premise": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "hypothesis": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "label": {
        "num_classes": 2,
        "names": [
            "not-entailment",
            "entailment"
        ],
        "names_file": null,
        "id": null,
        "_type": "ClassLabel"
    },
    "topic": {
        "num_classes": 5,
        "names": [
            "Argumentative",
            "Descriptive",
            "Dialogic",
            "Informative",
            "Narrative"
        ],
        "names_file": null,
        "id": null,
        "_type": "ClassLabel"
    }
}
```



## hda nli hindi


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:hda_nli_hindi/hda nli hindi')
```

*   **Description**:

```
This dataset is a recasted version of the Hindi Discourse Analysis Dataset used to train models for Natural Language Inference Tasks in Low-Resource Languages like Hindi.
```

*   **License**: 
MIT License

Copyright (c) 2019 MIDAS, IIIT Delhi

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

*   **Version**: 1.1.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'test'` | 9970
`'train'` | 31892
`'validation'` | 9460

*   **Features**:

```json
{
    "premise": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "hypothesis": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "label": {
        "num_classes": 2,
        "names": [
            "not-entailment",
            "entailment"
        ],
        "names_file": null,
        "id": null,
        "_type": "ClassLabel"
    },
    "topic": {
        "num_classes": 5,
        "names": [
            "Argumentative",
            "Descriptive",
            "Dialogic",
            "Informative",
            "Narrative"
        ],
        "names_file": null,
        "id": null,
        "_type": "ClassLabel"
    }
}
```


