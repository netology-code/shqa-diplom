# Дипломная работа по курсу «Инженер по ручному тестированию»

## Цели дипломной работы

Дипломная работа позволит закрепить знания и навыки по тестированию мобильных приложений, работе с документацией и требованиями. Вы примените реальные рабочие  инструменты, которые с очень большой вероятностью встретите при трудоустройстве.

В результате выполнения дипломной работы вы:
- поработаете с макетами приложения и картой состояний, а также оцените и проанализируете требования;
- создадите основную тестовую документацию (оформите тест план, составите тест-кейсы);
- выполните тестовый прогон по описанным кейсами в TMS сервисе Qase;
- закрепите на практике применение функций сниффера для прохождения тестовых сценариев;
- потренируетесь находить и фиксировать ошибки приложения.
  
## Инструкция к выполнению

1. Сделайте копию [Шаблона дипломной работы](https://u.netology.ru/backend/uploads/lms/content_assets/file/1328/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F_%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0._%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD.xlsx) на свой Google Disk. 
2. В названии файла введите свои фамилию, имя и группу вместо Name, Surname, Group.
3. Зайдите в “Настройки доступа” и выберите доступ “Просматривать могут все в Интернете, у кого есть ссылка”.
 Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. Выполните все задания дипломной работы, запишите ответы и приложите необходимые скриншоты в свой Google Doc (в столбце "Комментарий" указано, что следует предоставить в качестве решения).
5. Приступив к написанию тест-кейсов, при необходимости вы можете обратиться за предварительной консультацией к дипломному руководителю,чтобы утвердить охват, вид и оформление тест-кейсов. 
6. Для проверки дипломной работы преподавателем прикрепите ссылку на ваш документ в личном кабинете.

## Подготовка к выполнению заданий

В рамках дипломной работы вам необходимо организовать процесс тестирования мобильного приложения Нетологии. Сборки приложения настроены на тестовую среду и работают с тестовой базой данных,  поэтому контент в них ограничен. Вы можете без опасений отправлять заявки на курсы, совершать необходимые для теста сценарии, не опасаясь, что вам позвонит менеджер.

**Ваши шаги:**

1. Выберите платформу, на которой вы хотите выполнять дипломную работу и установите на девайс (девайсы) тестовое приложение.
   
2. Скачайте выбранную вами сборку приложения (Android или iOS):
- тестовая сборка Android ([apk-файл](https://github.com/netology-code/shqa-diplom/releases/download/apk/netology_android_qa.apk)) ;
- тестовая сборка iOS ([ipa-файл](https://github.com/netology-code/shqa-diplom/blob/main/ipa/netology_ios_qa_b1698666915.ipa)) и [инструкция по установке](https://github.com/netology-code/shqa-diplom/blob/main/ipa/ipa-instruction.md).

3. Изучите внимательно макеты тестового приложения  в [Figma](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1-2&mode=design), посмотрите наглядные кликабельные [прототипы экранов](https://www.figma.com/proto/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=2957-42492&t=KU6kNTlpAvP5TO0W-1&scaling=scale-down&page-id=2957%3A31579&starting-point-node-id=2957%3A41366&show-proto-sidebar=1).

## Этапы выполнения

Дипломная работа включает в себя следующие этапы:

1. Оценка работ и составление тест-плана.   
2. Выполнение работы (составление тест кейсов в Qase).   
3. Предварительное согласование тест-плана и оформленных тестовых сценариев с дипломным руководителем.   
4. Тестовый прогон кейсов в QASE с созданием TestRun.   
5. Оформление багрепортов.   
6. Моделирование тестовых сценариев возникновения экранов ошибок.
7. Сдача работы на проверку.   

### Этап 1. Оценка работ и составление тест-плана.

**Основная задача:**  
Необходимо ознакомиться с предоставленной документацией и приложением. И на основе первичных  данных написать  свой тест-план, оценить работу и время на ее выполнение.  Оцените в тест-плане весь функционал, который представлен на макетах.

Рекомендуем оформить тест-план как одностраничный документ. Скопируйте и используйте [готовый шаблон](https://u.netology.ru/backend/uploads/lms/content_assets/file/1329/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_%D1%82%D0%B5%D1%81%D1%82-%D0%BF%D0%BB%D0%B0%D0%BD%D0%B0.xlsx) или можете создать свой вариант отображения тест-плана.

Тест-план должен содержать следующую информацию:
- общая информация о приложении,
- функционал, который необходимо проверить,
- цели тестирования, принципы тестирования,
- даты старта и окончания работ,
- что будет сделано и что сделано не будет;
- риски;
- инструменты;  
- окружение (список устройств, которые планируется использовать);
- план работы, включающий оценку времени на каждый этап (можно отобразить в виде диаграммы Ганта);
- результаты тестирования.

<details close>
  
  <summary>Пример оформления </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/e56b6493-2202-4ca2-9855-f98c2912cdb0)

</details>

### Этап 2. Выполнение работы (составление тест кейсов в Qase)

**Основная задача:**   
Необходимо провести анализ функционала раздела [«Профиль»](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1309-48877&mode=design), выделить блоки проверок и составить по ним тест-кейсы, максимально охватывающие разные сценарии. Активно применяйте техники тест-дизайна при составлении кейсов. 

**Ваши шаги:**  
1. Зарегистрируйте свой собственный проект в  [Qase](https://qase.io/).

Qase – это популярная TMS система, которая активно используется многими компаниями при работе с тестовой документацией. При регистрации выберите тариф Free, он бесплатный и его будет достаточно для выполнения задания и практики работы в системе. Более детальная информация о работе Qase есть в видеотуториалы на Youtube.

2. В поле Project name укажите Netology, сохраните в описании имеющиеся ссылки на тестовую документацию, чтобы они были всегда под рукой.

<details close>
  <summary>Скрин к шагу 2 </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/183e794a-b29d-4ee7-adb3-425cd28a1e36)

</details>

3. Создайте Тест сьют для тестируемого раздела приложения.
   
Сценарии для тестирования работы одного компонента продукта, модуля или его функционала называется тестовый набор (по англ. test suite). Далее мы будем выполнять кейсы с описанием результатов (passed или failed) – такие тесты для запуска называют  тестовые прогоны (англ. test run).

<details close>
  <summary>Скрин к шагу 3 </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/4934dcb1-7420-4265-bb44-dad9d9ec9dbc)

</details>

4. Внутри тест сьюита  создаем наши тест кейсы.
   
<details close>
  
  <summary>Скрин к шагу 4 </summary>
  
   ![image](https://github.com/netology-code/shqa-diplom/assets/77622076/58206c4d-acc2-4a71-9768-eae669eb0603)
</details>

Для удобства вы можете группировать проверки, например: установка пароля, загрузка фото профиля и т.п.

Составленные тест-кейсы обязательно должны иметь следующие поля:
- серьезность и приоритет;
- описанные шаги;
- ожидаемый результат;
- предусловие, если необходимо; 
- прикладывайте примеры скриншотов для основных экранов, чтобы документация была максимально наглядна.   
Остальные параметры  вы можете указать на ваше усмотрение: Type(Тип), Automation status (статус кейса для автоматизации), Layer (уровень кейсов), Behavior (отметка о позитивных/негативных действиях).

<details close>
  
  <summary>Пример оформления </summary>
  
 ![image](https://github.com/netology-code/shqa-diplom/assets/77622076/6e063b61-4062-48eb-abc0-32785b8615f9)

</details>

### Этап 3. Предварительное согласование тест-плана и оформленных тестовых сценариев с дипломным руководителем. 

На этом этапе направьте свою работу дипломному руководителю для предварительного согласования, чтобы исключить возможные ошибки.

### Этап 4. Тестовый прогон кейсов в QASE с созданием TestRun.   

1. Выберите в боковом меню создание TestRun.
    
<details close>
  
  <summary>Скриншот к шагу 1 </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/3619cd37-8219-4b3a-a3ca-f1c380cef42e)

</details>

2. Укажите детали тестового прогона, его дату и выберите кейсы, которые необходимо включить в основную релизную проверку раздела Профиля.

<details close>
  
  <summary>Скриншоты к шагу 2 </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/7cd3da41-0cc5-4c74-a559-dcd2a6234a7e)

![image](https://github.com/netology-code/shqa-diplom/assets/77622076/65faec43-dfb7-4601-9efb-f232b2786de2)

</details>

3. Результатом данного задания  будет созданный и пройденный тестовый прогон из описанных ранее кейсов.

<details close>
  
  <summary>Пример оформления </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/61fa2ab7-34d9-48a4-886f-e0f9a13df1dc)

</details>

Подробнее про создание прогона можно ознакомиться в [официальной документации QASE](https://docs.qase.io/general/get-started-with-the-qase-platform/create-a-test-run-1). 

### Этап 5. Оформление багрепортов.  

Для всех кейсов со статусом Failed оформите багрепорты в виде комментариев с приложением скриншота.

<details close>
  
  <summary>Скриншот к этапу 5 </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/3296d0e9-996e-4689-be29-d306a6fad054)

</details>

### Этап 6. Моделирование тестовых сценариев возникновения экранов ошибок.

Главный экран приложения очень важен для позитивного опыта пользователя. Дизайнеры предусмотрели все возможные ситуации загрузки, когда что-то на экране может пойти не так. Ваша задача - убедиться, что разработчики реализовали все виды обработки ошибок по дизайну.

В соответствии с [макетами](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1174-32087&mode=design&t=ZUlcH64HHiqeHbaI-0) смоделируйте на своем тестовом окружении  данные ситуации и предоставьте ссылки на скриншоты с воспроизведенными ошибками.

Необходимо воспроизвести следующие экраны: 
1. Загрузка [скелетона](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1176-34691&mode=design&t=lzQp36VBfw2Vs0hR-0) ([здесь](https://ux.pub/editorial/vsie-chto-vam-nuzhno-znat-o-skielietnoi-zaghruzkie-prilozhienii-riezultaty-issliedovaniia-4dal) можно почитать подробнее про скелетную загрузку).
2. [Экран общей загрузки](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=2957-31420&mode=design).
3. [Не удалось загрузить данные](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1296-52640&mode=design&t=oW7DOIkOH850Kb7e-0).
4. [Ошибка отсутствия интернета](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1296-52813&mode=design).
5. [Ошибка серверная](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1296-52980&mode=design).

Используйте возможности девайсов и функционал сниффера для воспроизведения данных кейсов.


## Рекомендации по работе над дипломом

1. Не откладывайте надолго начало работы над дипломом. В таком случае у вас останется больше времени на получение рекомендаций от руководителя и доработку диплома. 
2. Дипломный проект — это итог вашей учебы и практический рабочий опыт. Отнеситесь к нему серьезно.
3. Составлять кейсы — это рутинная механическая работа по анализу, обобщению и оформлению данных. Но при этом кейсы показывают, как глубоко вы погрузились в задачи тестирования, как можете искать проблемы, придумывать решение, выбирать оптимальные способы и справляться с рутиной.
4. Максимально продумайте свой тайм-менеджмент при работе над дипломным проектом. Разбейте работу на части для удобства и выполняйте их поочерёдно. Так вы будете успевать учитывать комментарии от руководителя и не терять мотивацию. 

## Критерии оценки

Для получения зачета по дипломной работе должны быть выполнены следующие требования:
- Задания сданы в виде оформленного документа со всеми требуемыми ссылками и доступами на тестовый проект в QASE.
- Все кейсы в проекте оформлены в соответствии с требованиями, имеют обязательные поля  и учитывают максимальный охват функционала (должно быть оформлено не менее 20-25  кейсов). Помните, что в первую очередь вы практикуетесь для себя. Чем больше практики - тем легче в работе.
- Тестовый прогон полностью пройден и зафиксированы результаты.
- Практические задания на поиск ошибок выполнены с предоставлением скриншотов.

Работа будет направлена на доработку, если:
- Задание выполнено не полностью или с существенными ошибками;
- Решение не соответствует выше описанным требованиям.

 ### Правила приема работы

- В личном кабинете отправлена ссылка на Google Doc с выполненными заданиями;
- В документе настроены права доступа «Просматривать могут все в Интернете, у кого есть ссылка»;
- Решение оформлено по [шаблону](https://u.netology.ru/backend/uploads/lms/content_assets/file/1328/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F_%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0._%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD.xlsx));
- Таблицы в решении отформатированы с переносами и правильной вёрсткой ([ссылка на пример оформления](https://u.netology.ru/backend/uploads/lms/content_assets/file/1330/%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80._%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F_%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0._.xlsx)).
