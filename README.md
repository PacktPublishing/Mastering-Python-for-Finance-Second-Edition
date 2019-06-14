# Mastering Python for Finance - Second Edition

<a href="https://www.packtpub.com/big-data-and-business-intelligence/mastering-python-finance-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789346466"><img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/1/b11165.png" alt="Mastering Python for Finance - Second Edition" height="256px" align="right"></a>

This is the code repository for [Mastering Python for Finance - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/mastering-python-finance-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789346466), published by Packt.

**Implement advanced state-of-the-art financial statistical applications using Python**

## What is this book about?
The second edition of Mastering Python for Finance will guide you through carrying out complex financial calculations practiced in the industry of finance by using next-generation methodologies. You will master the Python ecosystem by leveraging publicly available tools to successfully perform research studies and modeling, and learn to manage risks with the help of advanced examples.

This book covers the following exciting features: 
* Solve linear and nonlinear models representing various financial problems
* Perform principal component analysis on the DOW index and its components
* Analyze, predict, and forecast stationary and non-stationary time series processes
* Create an event-driven backtesting tool and measure your strategies
* Build a high-frequency algorithmic trading platform with Python

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1789346460) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example,

The code will look like the following:
```
In [ ]:
%matplotlib inline
import quandl
quandl.ApiConfig.api_key = QUANDL_API_KEY
df = quandl.get('EURONEXT/ABN.4')
daily_changes = df.pct_change(periods=1)
daily_changes.plot();
```

**Following is what you need for this book:**
If you are a financial or data analyst or a software developer in the financial industry who is interested in using advanced Python techniques for quantitative methods in finance, this is the book you need! You will also find this book useful if you want to extend the functionalities of your existing financial applications by using smart machine learning techniques. Prior experience in Python is required.

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-10     | Python 3.7                          | Windows, Mac OS X, and Linux (Any) |
| 11       | Python 3.6                          | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://www.packtpub.com/sites/default/files/downloads/9781789346466_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Hands-On Python for Finance [[Packt]](https://www.packtpub.com/big-data-and-business-intelligence/hands-python-finance?utm_source=github&utm_medium=repository&utm_campaign=9781789346374) [[Amazon]](https://www.amazon.com/dp/1789346371)

* Hands-On Machine Learning for Algorithmic Trading [[Packt]](https://www.packtpub.com/big-data-and-business-intelligence/hands-machine-learning-algorithmic-trading?utm_source=github&utm_medium=repository&utm_campaign=9781789346411) [[Amazon]](https://www.amazon.com/dp/178934641X)

## Get to Know the Author
**James Ma Weiming**
is a software engineer based in Singapore. His studies and research are
focused on financial technology, machine learning, data sciences, and computational
finance. James started his career in financial services working with treasury fixed income
and foreign exchange products, and fund distribution. His interests in derivatives led him
to Chicago, where he worked with veteran traders of the Chicago Board of Trade to devise
high-frequency, low-latency strategies to game the market. He holds an MS degree in
finance from Illinois Tech's Stuart School of Business in the United States and a bachelor's
degree in computer engineering from Nanyang Technological University.


## Other books by the authors
* [Mastering Python for Finance](https://prod.packtpub.com/in/big-data-and-business-intelligence/mastering-python-finance?utm_source=github&utm_medium=repository&utm_campaign=9781784394516)


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
