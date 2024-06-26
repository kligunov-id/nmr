# NMR spectrum analysis with NMRGlue

This is our team's (Gladysh/Kligunov/Zhiganov) repo with source code and reports for the spectrum analysis task.

## File contents

### 1. [main_spectrum.ipynb](main_spectrum.ipynb)

This file contains all code regarding spectrum analysis. If you want to use it, you can just download this file (and optionally put a data folder [1H](1H) next to it). 

### 2. [main_spectrum.html](main_spectrum.html) and [main_spectrum.pdf](main_spectrum.pdf)

These are reports autogenerated from `.ipynb` notebook. The `.html` one is needed for me as an intermidiate step to build a `.pdf` one, but it is still fine.

Unfortunately, both reports cannot capture neither Jypyter widgets, nor the `ipympl` backend graphs (interactive matplotlib ones). Otherwise these reports could be turned in pretty much unchanged.

### 3. [pyproject.toml](pyproject.toml) and [poetry.lock](poetry.lock)

These `poetry` files describe dependencies. If you have `poetry` installed, than you can first execute `poetry install` and then `poetry run jupyter lab` to run the notebook and not worry about managing unusual dependencies such as `nmrglue`, `ipympl` and `ipywidgets` yourself.

If you look for `requrements.txt`, see contents of `pyproject.toml` instead.

### 4. [1H/](1H)

This folder contains the data we were given to analyse. Each folder inside it corresponds to a spectrum of one of a chemicals which epirical formulas are desribed in [Брутоформулы.txt](/1H/Брутоформулы.txt). Ours is chemical number 2.

### 5. [videos/](videos)

This folder primarily contains videos describing how to work with the main notebook.

### 6. [images/](images)

This folder contains various illustrations or spectrums related to project

## License

The software and resources are provided "AS IS", with no warranty of any kind. I am not responsible for a low grade, missed deadline or brain damage resulted from the use of this repository's content.

Use it as you wish.

