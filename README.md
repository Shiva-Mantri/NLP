## Install
### Spacy
- Ref: https://spacy.io/usage
- Open Anaconda CMD prompt
```
cd <some_path>\Spacy-Tutorial
python -m venv spacy-tut
spacy-tut\Scripts\activate
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
```
#### Verify Setup
```
python -m spacy validate
```

### Prodigy
- You would need to buy Prodigy (It is not a free product). It is worth it (Let's try and see)
- You will get a .whl (python wheel file). Install it in the env that was created
- pip install "C:\<path_to_whl_file>\SpacyProdigy\prodigy-1.10.8-cp36.cp37.cp38-cp36m.cp37m.cp38-win_amd64.whl"

#### Verify Setup
```
# Start Prodigy
python -m prodigy

# User home directory should .prodigy
dir %userprofile%
```

## Spacy Basics
