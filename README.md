# leetcode_cn_generate Usage
![](demo/leetcode.gif)

## Preparements:
Install essential packages: `requests`, `pyquery`
```cmd
$ pip3 install -r requorements.txt
```

## Config:

Edit your own username, password, language and repo in the **config.cfg.example** file and then rename it to **config.cfg**.

driverpath - Set the path of chromedriver. For Windows users, please include **chromedriver.exe** in path.

```
[leetcode]

username = username
password = password
language = python
repo = https://github.com/bonfy/leetcode
```

## Run

### Fully Download
```cmd
python3 leetcode_cn_generate.py
```
Usually you can always run fully download

### Download by id
```
python3 leetcode_cn_generate.py 1
python3 leetcode_cn_generate.py 1 10 100
```
You can only download the solution you want.
Just add the id arguments behind (seperate by space)


## Attention
Python 3 have tested

Python 2 maybe

## Changelog
- 2020-03-07: fork from [bonfy](https://github.com/bonfy/leetcode), drop chromedriver requirement, change to www.leetcode-cn.com.
