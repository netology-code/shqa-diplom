# Дипломная работа по курсу «Инженер по ручному тестированию»

## Цели дипломной работы

Дипломная работа позволит закрепить знания и навыки по тестированию мобильных приложений, работе с документацией и требованиями. Вы примените реальные рабочие  инструменты, которые с очень большой вероятностью встретите при трудоустройстве.

В результате выполнения дипломной работы вы:
- поработаете с макетами приложения и картой состояний, а также в оценке и анализе требований;
- создадите основную тестовую документацию (оформите тест план, составите тест-кейсы);
- выполните тестовый прогон по описанным кейсами в TMS сервисе Qase;
- закрепите на практике применение функций сниффера для прохождения тестовых сценариев;
- потренируетесь находить и фиксировать ошибки приложения.
  
## Инструкция к выполнению

1. Сделайте копию [Шаблона дипломной работы](https://docs.google.com/spreadsheets/d/1_YjWwRgCJDeU5_O3avXodL639UGcGWV2QGl8QfDKJtA/edit#gid=0) на свой Google Disk. 
2. В названии файла введите свои фамилию, имя и группу вместо Name, Surname, Group.
3. Зайдите в “Настройки доступа” и выберите доступ “Просматривать могут все в Интернете, у кого есть ссылка”.
 Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop).
4. Выполните все задания дипломной работы, запишите ответы и приложите необходимые скриншоты в свой Google Doc (в столбце "Комментарий" указано, что следует предоставить в качестве решения).
5. Приступив к написанию тест-кейсов, при необходимости вы можете обратиться за предварительной консультацией к дипломному руководителю,чтобы утвердить охват, вид и оформление тест-кейсов. 
6. Для проверки дипломной работы преподавателем прикрепите ссылку на ваш документ в личном кабинете.

## Подготовка к выполнению заданий

В рамках дипломной работы вам необходимо организовать процесс тестирования мобильного приложения Нетологии. Сборки приложения настроены на тестовую среду и работают с тестовой базой данных,  поэтому контент в них ограничен. Вы можете без опасений отправлять заявки на курсы, совершать необходимые для теста сценарии, не опасаясь, что вам позвонит менеджер.

Ваши шаги:

1. Выберите платформу, на которой вы хотите выполнять дипломную работу и установите на девайс (девайсы) тестовое приложение.
   
2. Скачайте выбранную вами сборку приложения (Android или iOS):
- тестовая сборка Android ([apk-файл](https://github.com/netology-code/shqa-diplom/releases));
- тестовая сборка iOS ([ipa-файл](https://github.com/netology-code/shqa-diplom/blob/main/ipa/netology_ios_qa_b1698666915.ipa)) и [инструкция по установке](https://github.com/netology-code/shqa-diplom/blob/main/ipa/ipa-instruction.md).

3. Изучите внимательно макеты тестового приложения  в [Figma](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1-2&mode=design), посмотрите наглядные кликабельные [прототипы экранов](https://www.figma.com/proto/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=2957-42492&t=KU6kNTlpAvP5TO0W-1&scaling=scale-down&page-id=2957%3A31579&starting-point-node-id=2957%3A41366&show-proto-sidebar=1).

## Этапы выполнения

Дипломная работа включает в себя следующие этапы:

1. Оценка работ и составление тест-плана.   
2. Выполнение работы (составление тест кейсов в Qase).   
3. Предварительное согласование тест-плана и оформленных тестовых сценариев с дипломным руководителем.   
4. Тестовый прогон кейсов в QASE с созданием TestRun.   
5. Оформление найденных ошибок.   
6. Моделирование тестовых сценариев возникновения экранов ошибок.
7. Сдача работы на проверку.   

### Этап 1. Оценка работ и составление тест-плана.

**Основная задача:**   
Необходимо провести анализ функционала раздела [«Профиль»](https://www.figma.com/file/t8utBtphc38VgQNnNg3olC/02-%D0%9C%D0%B0%D0%BA%D0%B5%D1%82%D1%8B-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%5BKODE-old%5D-(Copy)?type=design&node-id=1309-48877&mode=design), выделить блоки проверок и составить по ним тест-кейсы, максимально охватывающие разные сценарии. Активно применяйте техники тест-дизайна при составлении кейсов. 

**Шаги:**  
1. Зарегистрируйте свой собственный проект в  [Qase](https://qase.io/).
Qase - это популярная TMS система, которая активно используется многими компаниями при работе с тестовой документацией. При регистрации выберите тариф Free, он бесплатный и его будет достаточно для выполнения задания и практики работы в системе. Если вам понадобится более детальная информация о работе Qase , можно найти видеотуториалы на Ютюб.

Qase – это популярная TMS система, которая активно используется многими компаниями при работе с тестовой документацией. При регистрации выберите тариф Free, он бесплатный и его будет достаточно для выполнения задания и практики работы в системе. Более детальная информация о работе Qase есть в видеотуториалы на Youtube.

2. В поле Project name укажите Netology, сохраните в описании имеющиеся ссылки на тестовую документацию, чтобы они были всегда под рукой.

<details close>
  <summary>Скрин </summary>
  
![image](https://github.com/netology-code/shqa-diplom/assets/77622076/183e794a-b29d-4ee7-adb3-425cd28a1e36)

</details>
## Критерии оценки

Для получения зачета по дипломной работе необходимо:
- Задания сданы в виде оформленного документа со всеми требуемыми ссылками и доступами на тестовый проект в QASE.
- Все кейсы в проекте оформлены в соответствии с требованиями, имеют обязательные поля  и учитывают максимальный охват функционала (должно быть оформлено не менее 20-25  кейсов). Помните, что в первую очередь вы практикуетесь для себя. Чем больше практики - тем легче в работе.
- Тестовый прогон полностью пройден и зафиксированы результаты.
- Практические задания на поиск ошибок выполнены с предоставлением скриншотов.
 
   
