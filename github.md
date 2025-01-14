## Подсказки по гитхабу \([вернуться](README.md)\)

Я не буду пока делать акцент на работу с гитом в коммандной строке, пока больше через графический интерфейс.
И работу не в команде, а как соло контрибьютор в какой-то репозитория. Описанное ниже можно применять не только тут, но
и если вы захотите поучавстовать в каком-нибудь open source проекта.

### Форк репозитории к себе

Для форка к себе нужно нажать, сюприз!, Fork в правом верхнем углу:

![image](https://user-images.githubusercontent.com/142793/121194810-c19eb800-c877-11eb-8b4d-4d09b5eb2e1c.png)

И не забывайте ставить ~~лайки~~ звездочки! А если вы нажмете Watch, то к вам на почту будут приходить все изменения, но в этом потоке можно утонуть.

Если вы состоите в какой-то организации, то вам предложат куда форкнуть, форкать понятно дело нужно к себе.

![image](https://user-images.githubusercontent.com/142793/121195350-31ad3e00-c878-11eb-8940-43f7644d5635.png)

### Создание бранча

После того, как вы сделали форк к себе. Вы работаете уже из него. Чтобы не запутаться, мы для каждой недели будем делать свою ветку (бранч, branch),
в мире тру программистов это принято делать через командную строку, но это же можно сделать и через веб интерфейс:

![image](https://user-images.githubusercontent.com/142793/121195870-a97b6880-c878-11eb-9f6b-3b368dc0272c.png)

После того как вы жамкнули создать, вы можете выбрать этот бранч и работать уже в нем. Называние бранча написано будет в левом уголке.
Не забывайте проверять в каком именно бранче вы работаете.

![image](https://user-images.githubusercontent.com/142793/121196056-d4fe5300-c878-11eb-8ccc-12b01f8d355b.png)

Справа под зеленой кнопкой находятся два ключевых инструмента для работы: **Contribure** и **Fetch upstream**.

### **Fetch upstream**: забирание изменений из оригинального репозитория

Если что-то изменилось в оригинально, то жамкаете эту кнопу и забираете изменения.

![image](https://user-images.githubusercontent.com/142793/121197125-b9477c80-c879-11eb-8334-62dfe64d6602.png)

Вы можете просто сравнить, или забрать и смерджить со своим форком репозитория. Обратите внимание, что мердж происходит в тот бранч, который у вас указан.
Пока лучше не использовать **Compare**, а отдельные ветки и условие, что вы работает в **своей папке** в папке **students** спасет вас от конфликтов.
В общем, смело жамкаем **Fetch and merge**.

### Создание своей папки

Тут совсем все просто:

![image](https://user-images.githubusercontent.com/142793/121198216-a3868700-c87a-11eb-9857-5f46fd7c83c9.png)

Пишите путь

![image](https://user-images.githubusercontent.com/142793/121198359-bef19200-c87a-11eb-877c-bef5347150f8.png)

Там должен быть ваше имя пользователя!

Внизу пишите имя коммита, мы про это будем еще много говорить почему так, имя коммита должно быть **feat/глагол в повилительном наклонение и что сделано**, feat от feature, еще может быть fix - для исправления ошибок.

Вот так:

![image](https://user-images.githubusercontent.com/142793/121198693-037d2d80-c87b-11eb-8dca-0ba18f275653.png)

И жамкаем **Commit new file**.

### Страшный pull request

И теперь ваша репозитория отличается от родительской. И теперь вы можете послать изменения в родительскую на ревью и объединение (слияние, merge).

Для этого вам нужно нажать **Contribute** и в нем **Open pull request**:

![image](https://user-images.githubusercontent.com/142793/121199442-99b15380-c87b-11eb-816a-8e4a8ee4581d.png)

Это будет выглядить вот так:

![image](https://user-images.githubusercontent.com/142793/121199841-edbc3800-c87b-11eb-9636-62502589c94e.png)

Первая панелька позволяет выбрать откуда и куда, нужно проверить, что вы засылаете в родительскую репозиторию, а не куда-то еще. 
Кроме этого вы можете заслать и в другие форки.

![image](https://user-images.githubusercontent.com/142793/121200213-3c69d200-c87c-11eb-8867-255a7129e80b.png)

Сейчас для упрощения, мы будем засылать из вашей week1 в aglabx/main.

В поле **Comments** вы пишите, что именно вы засылаете. Для разных репозитория правила о офрмление сильно отличаются и обычно есть даже отдельная дока про эта.

![image](https://user-images.githubusercontent.com/142793/121200625-8f438980-c87c-11eb-883d-aa260b38d117.png)

И финально вы нажимаете **Create pull request**.

Вы справились.

### Как выполнять задания

Первое задание заключается в том, что нужно зарегистрироваться на всех платформах, где мы будем тренироваться,
и заполить файл about.md ссылочками на эти платформы.

Для этого:

1) проверяем, что мы в ветке week1
2) открываем файл **students/\<name\>/about.md** 
3) нажимаем в нем знак редактировать

![image](https://user-images.githubusercontent.com/142793/121203482-23452f00-c844-11eb-8d5c-9a8c13c34b6a.png)

4) заполняем его, должно быть что-то вот такое в результате

![image](https://user-images.githubusercontent.com/142793/121203918-7c14c780-c844-11eb-9abb-cc2e26b6f4e5.png)

Вы можете посмотреть как это выглядит во вкладке **Preview**, чтобы всё было красивенько.

5) Заполняем информация о коммите, это должно быть **feat/add my accounts**
6) Нажимаем кнопку **Commit changes**

Если вы до этого уже сделали пулреквест, то он обновится автоматически, это поведение по умолчанию, его можно где-то поменять, наверное.

В результате должно быть что-то вот такое:

![image](https://user-images.githubusercontent.com/142793/121204478-e9285d00-c844-11eb-858a-bf3ad9943f48.png)

