 ## seller.py
 
 Скрипт собирает данные о часах с маркетплейса `ozon` и сайта casio. Затем формирует общий прайс листы с обновлёнными 
остатками и ценами, и загружает их на `ozon`.

## market.py

 Данный скрипт собирает данные с маркетплейса `yandex market`. Так же он собирает данные о часах casio, которые 
получает от файла `seller.py`. Затем эти данные собираются в прайс листы и отправляются на yandex market.
