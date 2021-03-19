### Install
- Ref: https://spacy.io/usage
- Open CMD
```
cd <some_path>\Spacy-Tutorial
python -m venv spacy-tut
spacy-tut\Scripts\activate
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
```
### Verify Setup
```
python -m spacy validate
```
