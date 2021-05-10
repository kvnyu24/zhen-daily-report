## 真格日报 Automated!

### Introduction
- An automation tool developed with Python and JS that helps automate the process of creating 真格日报, a highly .
- Primary data sources used are:
    - 企名片 （融资新闻）
    - 36kr（大公司新闻、深度分享）

### Usage
- Installation
  - Clone this repo by running `git clone `
  - Install the respective Python dependencies by running `pip install -r requirements.txt` 
- Execution
  - Change the `UNION_ID` field in `rongzi_news.py` to the current session union id for 企名片, as shown in the following image:
    ![image](images/example1.png)
  - Run `python rongzi_news.py`