# ๐๐ปโโ GitHub ์คํ์์ค ํ์ฉ ํ๋ก์ ํธ

๋นํธ์ฝ์ธ ์๋๋งค๋งค ํ๋ก๊ทธ๋จ ๋ฐ ํ๋ ๊ทธ๋จ ๋ด์ ์ด์ฉํ์ฌ ์ค์๊ฐ์ผ๋ก ํ๋ ๊ทธ๋จ์ผ๋ก ๋นํธ์ฝ์ธ ๋ฐ ์ฌ๋ฌ ์ฝ์ธ์ ๋ณ๋ ์ฌํญ์ ๋ณด๊ณ ๋ฐ์ ์ ์๋ค.

## ํ ๊ตฌ์ฑ
| **์ด๋ฆ** | **ํ๋ฒ** |
|----------|-----|
|๐ ์ฅ์คํ |21828668|
|๐ ์ดํ์ฒ  |21711173|
|๐ ์ ์๊ทผ |22029440|



### ์๋นํธ Open API

์ฐ์ ์ ์๋นํธ์์ ๋ก๊ทธ์ธ(ํ์๊ฐ์ ํ์) ํ ํ ๊ณ ๊ฐ์ผํฐ์์ Open API๋ฅผ ์ฌ์ฉํ์ฌ ACCESS KEY์ SECRET KEY๋ฅผ ๋ฐ์ต๋๋ค.

ACCESS KEY์ SECRETํค๋ ์์ด๋ฒ๋ฆฌ์ง ์๋๋ก ์ฃผ์ํฉ๋๋ค.

![test](https://user-images.githubusercontent.com/41141851/118991825-080e9e80-b9bf-11eb-9f74-8e9bb6584138.png)

#### ํ๋ ๊ทธ๋จ API

1) ํ๋ ๊ทธ๋ ์ฑ์ ์ค์น ํ ์ฑํ๊ฒ์ ์ฐฝ์์ "BotFather"๋ฅผ ๊ฒ์ํ๋ค.
2) "BotFather"์ Chat room์์ /newbot์ ์๋ ฅํ์ฌ Username๊ณผ Botname์ ๋ง๋ ๋ค.
3) HTTP API๋ฅผ ๋ฐ๊ธ๋ฐ๋๋ค. (์์ง ์๋๋ก ๋ณต์ฌํด๋์) ๋ค์ ๊ฒ์์ฐฝ์์ "userinfobot"์ ๊ฒ์ํ์ฌ /start์ ๊ฒ์, User number ID(์ด๊ฒ๋ํ ์์ง๋ง๊ณ  ๋ณต์ฌํด๋์)๋ฅผ ๊ตฌํ๋ค.

์ด๋ก์จ ์๋นํธ Open API์ ACCESS KEY์ SECRET KEY, ํ๋ ๊ทธ๋จ API์ HTTP API์ User number ID๋ฅผ ์ป์๋ค. ์ด์  ์๋๋งค๋งค ํ๋ก๊ทธ๋จ์ ์ด์ฉํด๋ณด์.

#### ๋ณธ๊ฒฉ์ ์ผ๋ก ์์ํด๋ณด์!

![test](https://user-images.githubusercontent.com/41141851/118992432-9aaf3d80-b9bf-11eb-8843-d3cca4b3673c.png)

ํ์ฌ ๋ณด์ด๋ ์ฝ๋์ upbit-api-key์์ access key์ secret key๋ฅผ ๋ฃ๊ณ , telegram-api-key์์ telegram token key์ telegram mc key๋ฅผ ๋ฃ์ต๋๋ค.

### ํ๋ก๊ทธ๋จ ์คํ ์  ํ์ ์ค์น

```sh
pip install pyupbit
pip install python-telegram-bot
pip install virtualenv
pip install python-dotenv
pip install requests
pip install BeautifulSoup
```

ํ๋ ๊ทธ๋จ ๋ด์ผ๋ก ์ต์ ์ ๋ด์ค ์๋ฐ์ดํธ

- requests (ํน์  url์ html ๋ฌธ์ ๋ฐ๊ธฐ)
- BeautifulSoup (html ๋ฌธ์์์ ์ํ๋ ์์ ์ ํ์  ์ถ์ถ)
- python-telegram-bot (๋ด์ค ๋งํฌ๋ฅผ ํ๋ ๊ทธ๋จ ๋ด์ผ๋ก ์ฑํ๋ฐฉ์ ์ ์ก)


ํฌ์ํ๊ณ  ์ถ์ ์ฝ์ธ์ ์ถ๊ฐํ๊ณ  ์ถ์ ๋

coin_list์ ํฌ์ํ  ์ฝ์ธ์ ์ ๋ณด ์๋ ฅ






