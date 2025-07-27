# Best-Fit Distribution--Human Body Temperature

[Dataset](https://github.com/DiAg-2025/Python--Best-Fit-Distribution--Human-Body-Temperature/blob/main/human_body_temperature.csv) - This is a synthetically generated human body temperature data from OpenAI

The objective is to find the best-fit distribution for the dataset and validate it.

![Python](https://img.shields.io/badge/Py_Libraries-numpy,_matplotlib.pyplot,_pandas,_scipy.stats,_fitter,_seaborn-beige.svg)

---

[Analysis](https://github.com/DiAg-2025/Python--Best-Fit-Distribution--Human-Body-Temperature/blob/main/Analysis.ipynb)

Using the fitter, it is found that the gamma distribution fits the data most accurately.
```
gamma( a=312.67776317591745, loc=86.49938822098503, scale=0.03874322247561911 )
```

Sample and gamma conditional probabilities come close to each other, which validates the accuracy.
