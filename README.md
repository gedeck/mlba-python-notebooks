<table>
<tr>
<td><img src="img/mlba-python-cover.png" width=275></td>
<td>
    <h3>Machine Learning for Business Analytics</h3>
    <p>by Galit Shmueli, Peter C. Bruce, <a href="https://www.amazon.com/Peter-Gedeck/e/B082BJZJKX/">Peter Gedeck</a>, Nitin R. Patel</p>
    <ul>
    <li>Publisher: Wiley; 2nd edition (2025)</li>
    <li>ISBN-13: 978-1-119-54984-0</li>
    <li>Buy from 
      <a href="https://www.amazon.com/Machine-Learning-Business-Analytics-Applications/dp/1394286791/">Amazon</a>,
      <a href="https://www.barnesandnoble.com/w/machine-learning-for-business-analytics-galit-shmueli/1146602430">Barnes & Noble</a>
    </li>
    <li>Book webpage: <a href="https://www.dataminingbook.com/editions/python-2nd-edition-june-2025">https://www.dataminingbook.com/editions/python-2nd-edition-june-2025</a></li>
    </ul>
</td>
</tr>
</table>

The [repository](https://github.com/gedeck/mlba-python-notebooks) contains Jupyter notebooks with the Python source code for each chapter in the book.


## Package dependencies
All required packages are listed in the file `requirements.txt`. You can install it using 
```
pip install -r requirements.txt
```
Most notebooks will work with latest versions of all required packages. However, the following packages require specific versions of `numpy`. The `requirements.txt` file reflects these limitations.

- `surprise` (chapter 15): `numpy<2`
- `pmdarima` (chapter 18, used by sktime for ARIMA): `numpy<2`