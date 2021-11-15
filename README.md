#A1QA LAB
1 Задание

## 1 https://ru.wikipedia.org/ ##

Элемент: **Заголовок**

//span[@class='mw-headline'][1], 

//*[@id="Добро_пожаловать_в_Википедию,"]

//span[@class='mw-headline']/ancestor::h1[@class='main-top-header']

Элемент: **Ссылка на скачивание файла в формате pdf**

//*[@id="coll-download-as-rl"]/a 

Элемент: **Картинка (Федор Самохин)**

//*[@id="main-tga"]/div[2]/a/img

/html/body/div[3]/div[3]/div[5]/div[1]/div[2]/div[1]/div[2]/div[2]/a/img

## 2 https://ru.wikipedia.org/wiki/Шпаргалка ##


Элемент: **Пример из колонки ввода обычного текста**

/html/body/div[3]/div[3]/div[5]/div[1]/table/tbody/tr[4]/td[2]/p/tt

//*[@id="mw-content-text"]/div[1]/table/tbody/tr[4]/td[2]/p/tt

//div[@class='mw-parser-output']/table/tbody/tr[4]/td[2]/p/tt\

Элемент: **Кнопка для настройки языка**

//button[@class='uls-settings-trigger']


## 3 https://ru.wikipedia.org/login ##

Элемент: **Лейбл названия поля для ввода имени учетной записи**
//*[@id="userloginForm"]/form/div/div[1]/label

//div/div[@class='mw-htmlform-field-HTMLTextField loginText mw-ui-vform-field']/label

Элемент: **Поле для ввода имени учетной записи**

//*[@id="wpName1"]

//div/div[@class='mw-htmlform-field-HTMLTextField loginText mw-ui-vform-field']/div[@class='mw-input']/input

Элемент: **Лейбл названия поля для ввода пароля**

//*[@id="userloginForm"]/form/div/div[2]/label 

//div/div[@class='mw-htmlform-field-HTMLTextField loginPassword mw-ui-vform-field']/label

Элемент: **Поле для ввода пароля**

//*[@id="wpPassword1"]

//div/div[@class='mw-htmlform-field-HTMLTextField loginPassword mw-ui-vform-field']/div[@class='mw-input']/input

Элемент: **Чекбокс оставаться в системе**

//*[@id="wpRemember"]

 //div[@class='mw-ui-checkbox']/input

Элемент: **Кнопка для входа**

//*[@id="wpLoginAttempt"]

//div[@class='mw-input mw-htmlform-nolabel']

Элемент: **Ссылка для помощи по входу**

//*[@id="userloginForm"]/form/div/div[5]/div/a

//div[@class='mw-htmlform-field-HTMLInfoField mw-form-related-link-container mw-userlogin-help mw-ui-vform-field']/div/a

Элемент: **Ссылка для сброса пароля**


//*[@id="userloginForm"]/form/div/div[6]/div/a

//div/div[@class = 'mw-htmlform-field-HTMLInfoField mw-form-related-link-container mw-ui-vform-field']/div/a


Элемент: **Кнопка для присоединения к проекту**

//*[@id="mw-createaccount-join"]

 //div/div[@class='mw-htmlform-field-HTMLInfoField mw-ui-vform-field']/div/div/a

