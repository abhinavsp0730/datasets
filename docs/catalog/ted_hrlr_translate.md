<div itemscope itemtype="http://schema.org/Dataset">
  <div itemscope itemprop="includedInDataCatalog" itemtype="http://schema.org/DataCatalog">
    <meta itemprop="name" content="TensorFlow Datasets" />
  </div>
  <meta itemprop="name" content="ted_hrlr_translate" />
  <meta itemprop="description" content="Data sets derived from TED talk transcripts for comparing similar language pairs&#10;where one is high resource and the other is low resource.&#10;&#10;&#10;To use this dataset:&#10;&#10;```python&#10;import tensorflow_datasets as tfds&#10;&#10;ds = tfds.load(&#x27;ted_hrlr_translate&#x27;, split=&#x27;train&#x27;)&#10;for ex in ds.take(4):&#10;  print(ex)&#10;```&#10;&#10;See [the guide](https://www.tensorflow.org/datasets/overview) for more&#10;informations on [tensorflow_datasets](https://www.tensorflow.org/datasets).&#10;&#10;" />
  <meta itemprop="url" content="https://www.tensorflow.org/datasets/catalog/ted_hrlr_translate" />
  <meta itemprop="sameAs" content="https://github.com/neulab/word-embeddings-for-nmt" />
  <meta itemprop="citation" content="@inproceedings{Ye2018WordEmbeddings,&#10;  author  = {Ye, Qi and Devendra, Sachan and Matthieu, Felix and Sarguna, Padmanabhan and Graham, Neubig},&#10;  title   = {When and Why are pre-trained word embeddings useful for Neural Machine Translation},&#10;  booktitle = {HLT-NAACL},&#10;  year    = {2018},&#10;  }&#10;" />
</div>
# `ted_hrlr_translate`

*   **Description**:

Data sets derived from TED talk transcripts for comparing similar language pairs
where one is high resource and the other is low resource.

*   **Homepage**:
    [https://github.com/neulab/word-embeddings-for-nmt](https://github.com/neulab/word-embeddings-for-nmt)
*   **Source code**:
    [`tfds.translate.ted_hrlr.TedHrlrTranslate`](https://github.com/tensorflow/datasets/tree/master/tensorflow_datasets/translate/ted_hrlr.py)
*   **Versions**:
    *   **`1.0.0`** (default): New split API
        (https://tensorflow.org/datasets/splits)
    *   `0.0.1`: No release notes.
*   **Download size**: `124.94 MiB`
*   **Dataset size**: `Unknown size`
*   **Auto-cached**
    ([documentation](https://www.tensorflow.org/datasets/performances#auto-caching)):
    No
*   **Features**:

```python
Translation({
    'az': Text(shape=(), dtype=tf.string),
    'en': Text(shape=(), dtype=tf.string),
})
```
*   **Supervised keys** (See
    [`as_supervised` doc](https://www.tensorflow.org/datasets/api_docs/python/tfds/load)):
    `('az', 'en')`
*   **Citation**:

```
@inproceedings{Ye2018WordEmbeddings,
  author  = {Ye, Qi and Devendra, Sachan and Matthieu, Felix and Sarguna, Padmanabhan and Graham, Neubig},
  title   = {When and Why are pre-trained word embeddings useful for Neural Machine Translation},
  booktitle = {HLT-NAACL},
  year    = {2018},
  }
```

## ted_hrlr_translate/az_to_en (default config)

*   **Config description**: Translation dataset from az to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 903
'train'      | 5,946
'validation' | 671

## ted_hrlr_translate/aztr_to_en

*   **Config description**: Translation dataset from az_tr to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 903
'train'      | 188,396
'validation' | 671

## ted_hrlr_translate/be_to_en

*   **Config description**: Translation dataset from be to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 664
'train'      | 4,509
'validation' | 248

## ted_hrlr_translate/beru_to_en

*   **Config description**: Translation dataset from be_ru to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 664
'train'      | 212,614
'validation' | 248

## ted_hrlr_translate/es_to_pt

*   **Config description**: Translation dataset from es to pt in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,763
'train'      | 44,938
'validation' | 1,016

## ted_hrlr_translate/fr_to_pt

*   **Config description**: Translation dataset from fr to pt in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,494
'train'      | 43,873
'validation' | 1,131

## ted_hrlr_translate/gl_to_en

*   **Config description**: Translation dataset from gl to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,007
'train'      | 10,017
'validation' | 682

## ted_hrlr_translate/glpt_to_en

*   **Config description**: Translation dataset from gl_pt to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,007
'train'      | 61,802
'validation' | 682

## ted_hrlr_translate/he_to_pt

*   **Config description**: Translation dataset from he to pt in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,623
'train'      | 48,511
'validation' | 1,145

## ted_hrlr_translate/it_to_pt

*   **Config description**: Translation dataset from it to pt in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,669
'train'      | 46,259
'validation' | 1,162

## ted_hrlr_translate/pt_to_en

*   **Config description**: Translation dataset from pt to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,803
'train'      | 51,785
'validation' | 1,193

## ted_hrlr_translate/ru_to_en

*   **Config description**: Translation dataset from ru to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 5,476
'train'      | 208,106
'validation' | 4,805

## ted_hrlr_translate/ru_to_pt

*   **Config description**: Translation dataset from ru to pt in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 1,588
'train'      | 47,278
'validation' | 1,184

## ted_hrlr_translate/tr_to_en

*   **Config description**: Translation dataset from tr to en in plain text.
*   **Splits**:

Split        | Examples
:----------- | -------:
'test'       | 5,029
'train'      | 182,450
'validation' | 4,045
