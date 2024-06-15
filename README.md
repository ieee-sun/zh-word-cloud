# Chinese Word-Cloud rendering 
# 繪製文字雲
- Segmentated (thanks to [github.com/fxsjy/jieba](https://github.com/fxsjy/jieba))
- Normalized / Tokenized Walk-through + Demo
- (optional) - Project-specific keywords (e.g. `程子`,`知本`, `強地動觀測計畫`) fetching
- Revised cycle for unwanted jargon (e.g. `子曰`, `者也`) - *while free online UI is not good at*
- Graphic customization

![Python :: 3.10 ::](https://img.shields.io/badge/Python-3.10-blue)
![Chinese Segmentation](https://img.shields.io/badge/中文-Chinese%20Segmentation-darkgreen)
![Cultural Open Access](https://img.shields.io/badge/Cultural%20OPEN%20ACCESS-F68212)
> <img src="https://github.com/ieee-sun/zh-word-cloud/assets/172009644/271cc6cb-28c6-45dd-ba29-759a6c304918" title="大學 文字雲 wordcloud" width=800>
>
> 禮記·大學 文字雲

>
> <img src="https://github.com/ieee-sun/zh-word-cloud/assets/172009644/971da225-e6e8-4c12-a2b5-5517c1bc9370" title="As You Like It, William Shakespeare" width=800>
>
> *As You Like It* by William Shakespeare - Wordcloud

One of our demo is using `jieba-tw`  as zh-Hant environment:
```
# ZH ENVIRONMENT CONSTANT

    # Download the traditional chinese dictionary from jieba-tw
    ### 繁體字較完整詞庫
    ### [ https://raw.githubusercontent.com/ldkrsi/jieba-zh_TW/master/jieba/dict.txt ]
zh_DICT_FILEPATH = '/content/jieba/dict_jieba_tw_Dec2023.txt'
zh_DICT2_FILEPATH = '/content/jieba/dict_jeiba_tc_big.txt'
zh_STOPWORD_FILEPATH = '/content/jieba/sun-chinese-stopwords2023.txt'

# INIT traditional Chinese dictionary
jieba.set_dictionary(zh_DICT2_FILEPATH)
```
### Walk-through with our Tutorial in [this Jupyter Notebook `.ipynb` ](https://github.com/ieee-sun/zh-word-cloud/blob/3336cc77a529cd57d76b46f3cd2db69eea3f3f44/zh_vocab_clould.ipynb)

---
> ###### Prepared & Published by:
> ##### Sun CHUNG, *SMIEEE* M.Sc. HKU - *colab w/ MIT-IDSS*
---
