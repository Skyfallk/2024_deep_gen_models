# 2023_processing_and_generating_images_course
Репозиторий с материалами курса "Глубокие генеративные модели (Deep Generative Models)" в AITalantedHub.

В данный момент происходит активное развитие методов генерации данных, которые могут совершить революцию в применении ИИ. Данный курс расскажет о развитии генеративных сетей, от GAN’ов до диффузионных моделей и LLM. Студенты узнают теоретические основы решения задач генерации текса, изображений, аудио, познакомятся с современными sota архитектурами. Узнают как дообучать диффузионные модели и LLM под свои задачи.

## Домашние задания

Когда залили выполенное ДЗ на git, ссылку на git с ДЗ оставить в соответствующей колонке. Репозиторий должен быть приватным. Для возможности проверки выслать инвайты на него на аккаунты менторов:
- artyomnaz
- NikitaKononov
- EgorovM
- denkogit
- Skyfallk

Для того чтобы отправить ДЗ на провекрку поставте в [таблице](https://docs.google.com/spreadsheets/d/1U7xckpo6i3Z0PNCimt8Vhr6vJ_SnA-z385FQaZ_9IKg/edit#gid=0) на против своей фамилии в соответствующей колонке '+'. После проверки вместо него появятся баллы.

| ДЗ | Где лежит | Кол-во баллов |deadline|
| ----------- | ----------- |-----------|-----------|
| Байесовская генерация и автоэнкодеры| |15|09.03.24|
| Имплементация и обучение GAN | ...|30|24.03.24|
| | |10||
| | |30||
| | |15||
| Доклады | |10|16.04.24|


## Выполнение и оформление ДЗ

### Общие требования к выполнению

- необходио создать репозиторий для выполнения домашних задиний
- в master ветке положить README с ФИО, названием предмета, выбранной задачей и названием датасета
- под каждое домашнее задание создаем ветку homewor_<номер ДЗ> (например, homework_1)
- в репозитории обязательно должно присутствовать README
- в репозитории обязательно должен присутствовать файл requarements.txt  с версиями билиотек, которыми вы пользовались при выполнении ДЗ
- код с выполненым ДЗ можно хранить в виде jupyter notebook или .py скриптов
- если ДЗ выполняли в google colab или kaggle положите в README ссылку

#### README должен содерджать:
1. Описание задачи которую решаете (кратко; пример: генерация лиц, поиск аномалий, дообучение сети знаниям о ...)
2. Датасет который испольщуете для решения задачи (какой нашли, как собирали, сколько и какие изображения)
3. Результаты обучения\экспериметы

##### Результаты обучения
Секция с результатами обучения должна содержать:
1. График лосс функции в процессе обучения
2. График метрик на валидационной выборке во время обучения
3. 5-10 примеров изображений с результатом работы сети
4. Значения метрик

##### Эксперименты
Большая часть домашених заданий будет заключаться в постановке эксперимента и анализа его результатов. Секция экспериментов должна содерать следующее:
1. Цель эксперимента (например: получить сходимость, сгененировать изображение с и т.д.)
2. Идея эксперимента (например: замедлить обучение дискриминатора, учить его каждые n эпох)
3. Результаты эксперимента (графики и метрики)
4. Сравнение с baseline (например:сошлась ли сеть, стало ли генерироваться лучше, предположить почему; сравнить графики лоссов, генерируемые изображения)
5. Выводы

### Логирование обучения

Для логирования поведения лоссов и валидационных метрик использовать:

1. [Tensorboard](https://pytorch.org/tutorials/intermediate/tensorboard_tutorial.html)
2. [Weights & Biases](https://docs.wandb.ai/tutorials/pytorch)

## Темы докладов

[Таблица](https://docs.google.com/spreadsheets/d/19WSW79lqwbI0yOtDTVUMyVJt9jdZQSW0E5h5qfTlkWA/edit#gid=0) с темами докладов и заявленными участниками.

Для того чтобы выборать доклад или присоединится к уже существующей группе, допишите в колонке Участники свою фамилию.

Не более 3-ех человек на доклад!!!

### Требования к докладу

1. регламент: не более 15 мин на доклад, 5 мин на вопросы
2. минимум осветить три вопроса:
- в чем проблема, коротко как ее решали раньше
- в чем идея: как исправляем проблему
- основной результат: исправили ли проблему, сравнение с результатом другими подходами
3. доклад может быть выполнен 1-3 студентом\ами
4. обязательно презентация
5. критерии оценки:
- полнота ответов на основные 3 вопроса
- подача материала (сам рассказаз и презентация)

### Советы по презентации
- красивая презентация, это та которая помогает донести тезис
- одни тезис-один слайд, не громоздите много инфы в одно место
- не стремитесь сделать визуально эстетично, стремитесь четко структурировать информацию
- четко определите что хотите сказать каждым слайдом
- попробуйте рассказать материал друг другу, проверьте, попадаете ли вы в регламент

## Полезная литература:
1. Девид Фостер: Генеративное глубокое обучение. Творческий потенциал нейронных сетей
2. Jakub Langr, Vladimir Bok: GANs in action


## Навигация

