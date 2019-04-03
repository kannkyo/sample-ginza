# sample-ginza

Sample for GiNZA

# install

```bash
python3 -m venv venv
source venv/bin/activate
pip install "https://github.com/megagonlabs/ginza/releases/download/v1.0.1/ja_ginza_nopn-1.0.1.tgz"
```

# try

```bash
(venv) sample-ginza$ python -m spacy.lang.ja_ginza.cli
Loading model 'ja_ginza_nopn'
mode is C
disabling sentence separator
次の元号は令和ですね。
# text = 次の元号は令和ですね。
1       次      次      NOUN    名詞-普通名詞-一般      _       3       nmod    _       SpaceAfter=No|NP_B
2       の      の      ADP     助詞-格助詞     _       1       case    _       SpaceAfter=No
3       元号    元号    NOUN    名詞-普通名詞-一般      _       5       nsubj   _       SpaceAfter=No|NP_B
4       は      は      ADP     助詞-係助詞     _       3       case    _       SpaceAfter=No
5       令和    令和    PROPN   名詞-固有名詞-一般      _       5       root    _       SpaceAfter=No|NP_B
6       です    です    AUX     助動詞  _       5       cop     _       SpaceAfter=No
7       ね      ね      PART    助詞-終助詞     _       5       aux     _       SpaceAfter=No
8       。      。      PUNCT   補助記号-句点   _       5       punct   _       SpaceAfter=No
```

# LICENSE

[MIT](LICENSE)
