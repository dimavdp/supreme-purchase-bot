# supreme-purchase-bot

Automates purchases for newyorksupreme.com product drops.

# Usage:

#### STEP ONE
```
$ git clone https://github.com/dimavdp/supreme-purchase-bot
$ cd supreme-purchase-bot
$ virtualenv venv --python=python3.7
$ pip install -r requirements.txt
```

#### STEP TWO
Create a config.py file in the local directory that looks similar to this for each order you are placing.

```
keys = {
        "product_url": "https://www.supremenewyork.com/shop/sweatshirts/yw4mifo2y",
        "name": "Ky Nguen",
        "email": "test@gmail.com",
        "phone_number": "6789998212",
        "street_address": "Arbat St.",
        "city": "Moscow", 
        "zip_code": "91601",
        "card_cvv": "666",
        "card_number": "1524615272839913"
}
```

#### STEP THREE
You may have to download the correct chromedriver for you operating system (Linux/OSX/Windows), put the chromedriver the supreme-bot directory with the script.

chromdriver: http://chromedriver.chromium.org/downloads

#### STEP FOUR
```
$ python bot.py
```
