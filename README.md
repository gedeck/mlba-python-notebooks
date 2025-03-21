# Machine Learning for Business Analytics
## Concepts, Techniques, and Applications in Python



## Package dependencies
All required packages are listed in the file `requirements.txt`. You can install it using 
```
pip install -r requirements.txt
```
Most notebooks will work with latest versions of all required packages. However, the following packages require specific versions of `numpy`. The `requirements.txt` file reflects these limitations.

- `surprise` (chapter 15): `numpy<2`
- `pmdarima` (chapter 18, used by sktime for ARIMA): `numpy<2`