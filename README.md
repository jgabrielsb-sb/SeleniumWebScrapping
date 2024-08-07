# SeleniumWebScrapping
Application using Selenium, Pandas and Python to Automatize Web Scrapping

* How to use it
  
  First, you need to install Selenium and the necessary webdrivers. Additionally, you need to install Pandas library to deal with Dataframes.
  Then, if you just want to webscrappe a product in 'Mercado Livre', you must use the following script

```python
CONST_ML_URL = "https://www.mercadolivre.com.br/"
driver = #define your driver
product_name = #define the product you want to search for
number_to_collect = #define how much announcements you want to collect

products_df = get_products(CONST_ML_URL, driver, product_name, number_to_collect)
```

* More details about this Script, see my Medium post: https://medium.com/@jgabrielsb2002/automating-product-searches-on-mercado-livre-with-selenium-and-python-5012864f52b1
  
