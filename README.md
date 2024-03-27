# my UNET realization with HumanSegmentationProblem

*in pdf file there're the results of the trained model shown through a selection of some photos

*in tqdm.png can see the process of model learning
Enjoy)

![UNET_arch](https://neerc.ifmo.ru/wiki/images/d/dc/U-net-architecture.png)

Курс посвящен основам глубокого обучения и методам применения нейронных сетей в различных задачах.

Обучение на курсе позволит понять теоретические основы работы нейронных сетей и приобрести прикладные навыки работы с современными моделями. Практическая часть курса включает в себя работу с текстами, изображениями, вопросно-ответными системами и генеративными моделями.

Для успешного освоения материалов курса необходимо обладать следующими знаниями:

* Программирование на Python (рекомендуем [МФК “Основы программирования и анализа данных на Python”](https://github.com/MSUcourses/Data-Analysis-with-Python/blob/main/Python/lectures_spring_2023.md)).
* Линейная алгебра, оптимизация, статистика (рекомендуем [факультатив "Математика для анализа данных"](https://github.com/MSUcourses/Data-Analysis-with-Python/tree/main/Math))
* Основы машинного обучения (рекомендуем [МФК “Машинное обучение для решения прикладных задач”](https://github.com/MSUcourses/Data-Analysis-with-Python/blob/main/Machine%20Learning/lectures_spring_2023.md)).

Продолжительность: 1 семестр (12 лекций).

## 📋 Содержание

Дата лекции | Запись лекции | Конспект | Домашнее задание | Дедлайн сдачи 
|:----:|----|:----:|:----:|:----:|
|07.02.2024| [Лекция 1. Вводная лекция](https://youtu.be/_fvs0msh_f0) | [Конспект 1](https://colab.research.google.com/drive/1tT0lwNsERmCaVvrR2WsLW3LBq6KrOJ1t) |---|---|
|14.02.2024| [Лекция 2. PyTorch. Градиентный спуск для обучения нейросети](https://www.youtube.com/live/QJe4srKrwQA) | [Конспект 2](https://colab.research.google.com/drive/1M9D_0RWHPJvuTERSwcGRlLWdQnMUDnQp) | [ДЗ 2](https://contest.yandex.ru/contest/59939/problems/) | 03.03.2024 |
|21.02.2024| [Лекция 3. Обучение по батчам, регуляризация](https://www.youtube.com/live/L1OVB9V28jI) | [Конспект 3](https://colab.research.google.com/drive/1SNhwxGfVp4fbG_athXegnyw97EQVCUIc?usp=sharing) | [ДЗ 3](https://contest.yandex.ru/contest/60132/problems/) | 10.03.2024 |
|28.02.2024| [Лекция 4. Компьютерное зрение. Сверточные нейросети](https://youtube.com/live/7raMKcf04dk) | [Конспект 4](https://colab.research.google.com/drive/1ZMu6C3ZEt3kCSDBNWGM6sicXL5-EhSve?usp=sharing) | [ДЗ 4](https://contest.yandex.ru/contest/60375/problems/) | 17.03.2024 |
|06.03.2024| [Лекция 5. Архитектура сверточных нейросетей. Transfer learning](https://www.youtube.com/live/ZnQhxR2Cp58?si=9Q0DUlvCfe0df2nW) | [Конспект 5](https://colab.research.google.com/drive/1-yQp_QkusL4v_Ardz6IH9d-XQAC1AB0B) | [ДЗ 5](https://contest.yandex.ru/contest/60604/problems/) | 24.03.2024 |
|13.03.2024| [Лекция 6. Эмбеддинги, word2vec](https://www.youtube.com/live/C54N3Zx97H4) | [Конспект 6](https://colab.research.google.com/drive/160u2lVYTMPDPEFpa4ZfYa52YAx9d6xjb) | [ДЗ 6](https://contest.yandex.ru/contest/60846/problems/) | 31.03.2024 |
|20.03.2024| [Лекция 7. RNN и классификация текста](https://www.youtube.com/live/teZW5M6mRCk) | [Конспект 7](https://colab.research.google.com/drive/1lpmcAd46ytFA30Pn_X3KNxUJ-hl1eU_7) | [ДЗ 7](https://contest.yandex.ru/contest/61082/problems/) | 07.04.2024 |

* [YouTube плейлист с видеозаписями лекций](https://youtube.com/playlist?list=PL2mBTfXHM2qiVYN7jMN6tfYyDXKscX9zE)

## 📝 Ссылки и дополнительная литература

* Yoshua Bengio. Deep Learning. MIT Press, 2017.
* The Hundred-Page Machine. Learning Book by Andriy Burkov (Andriy Burkov, 2019).
* [Онлайн-учебник по машинному обучению](https://academy.yandex.ru/dataschool/book)

### 📚Список полезных материалов от преподавателей

1. [Pythontutor](https://pythontutor.ru/): интерактивный учебник по Питону с задачами на каждую тему.

   Также небольшая подборка материалов для тех, кто хочет быстро освежить/улучшить знания Python:

* [Хороший и короткий туториал от Stanford’а](http://cs231n.github.io/python-numpy-tutorial/)
* [Репозиторий с большим набором примеров/упражнений](https://gitlab.erc.monash.edu.au/andrease/Python4Maths/tree/master)

2. Ликбез по функциям, производной, градиенту и градиентной оптимизации в виде colab-ноутбуков. Поможет понять градиентный спуск, как обучаются нейросети. 
* [колаб по функциям](https://colab.research.google.com/drive/1Qc18v4byGmYFqUaJbmMEwRq5MSpmZmuh?usp=sharing);
* [колаб по производной](https://colab.research.google.com/drive/1Etz36ELaIoqOoDR_gbLVn3HsMfxtbK2Q?usp=sharing);
* [колаб по оптимизации](https://colab.research.google.com/drive/1I73AiHtN0XvXCgCMj1oLKZTNw4CRDdTL?usp=sharing).

3. Книга [“Создаем нейронную сеть](https://vk.com/doc44301783_578949209?hash=GF6d6zgN2oXiFi8S66dzZg7eCV3cTi5SZykZoQMTxwD)”. Тут о том, как устроены и работают нейросети суперпростыми словами и с картинками. После первых глав этой книги станет понятно, как работает обучение нейросетей.

4. [Введение в Data Science и машинное обучение](https://stepik.org/course/4852/info): курс от института биоинформатики, где совсем кратко рассказывается про основы нейросетей и данные. Большое время курса уделено решающим деревьям. Именно через этот курс можно познакомиться с первыми библиотеками по машинному обучению. Один из самых полных курсов для старта и введения.

5. [Семинар по теме "Матрично-векторное дифференцирование"](http://www.machinelearning.ru/wiki/images/5/50/MOMO17_Seminar2.pdf) (курс "Методы оптимизации в машинном обучении", ВМК+Физтех, осень 2017)
   
   [Заметки по матричному дифференцированию от Стенфорда](http://cs231n.stanford.edu/vecDerivs.pdf)

   Более сложные книги, которые могут быть полезны в рамках прохождения курса:
1. [Probabilistic Machine Learning: An Introduction; English link](https://probml.github.io/pml-book/book1.html), [Русский перевод](https://dmkpress.com/catalog/computer/data/978-5-93700-119-1/)
2. [Deep Learning Book: English link](https://www.deeplearningbook.org/). Первая часть (Part I) крайне рекомендуется к прочтению.

   Более полный список хороших книг/лекционных заметок на русском и английском языке можно найти [здесь](https://github.com/girafe-ai/ml-course/blob/master/extra_materials.md)


**Youtube**

En:
* [Канал Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy) - рассказывает про обучение глубоких нейронных сетей на больших наборах данных.
* [Классный канала 3Blue1Brown от Гранта Сандерсона](https://youtube.com/c/3blue1brown) с комбинацией математики и развлечения, где объяснения сопровождаются анимацией (просто о сложном).

Ru:
* [Переводы](https://www.youtube.com/@VertDiderScience) научно-популярных видео, лекций в т.ч. роликов выше.
* [Machine Learning Podcast.](https://www.youtube.com/@machinelearningpodcast9502)

**Блоги и каналы:**

* [КвазиНаучный блог Александра Дьяконова АНАЛИЗ МАЛЫХ ДАННЫХ](https://dyakonov.org/ag/)
* [Sebastian Ruder blog about natural language processing and machine learning](https://ruder.io)
* [Andrej Karpathy blog](http://karpathy.github.io)
* [DL in NLP](https://t.me/dlinnlp) - новости и обзоры статей на тему обработки естественного языка, нейросетей и всего такого.
* [DLStories | Нейронные сети и ИИ](https://t.me/dl_stories) - новинки искусственного интеллекта и нейронных сетей, разборы статей.
* [NN for Science](https://t.me/nn_for_science) - новинки из области машинного обучения с прицелом на использование в науке.
* [эйай ньюз](https://t.me/ai_newz) - новости из мира AI в сопровождении мнения автора канала.

**Курсы:**

* [Open Machine Learning course](https://github.com/girafe-ai/ml-course)
* [Курс по машинному обучению. Проект «ИИ Старт»](https://stepik.org/course/125587/promo)

## 🎥Видеоинструкции

* [Регистрация для получения доступа к заданиям курса](https://youtu.be/R1_Xzr3Eyso )
* [Установка Python и Jupyter Notebook на Windows](https://youtu.be/fVu3OjCfVps)
* [Особенности работы с Google Colab ](https://youtu.be/Fbdisx6XUzw)
* [Типы ошибок в Яндекс. Контест и способы их устранения ](https://youtu.be/y3nRM1Wd_3M)

## ❓Часто задаваемые вопросы

* [Где лучше писать код на python?](https://github.com/MSUcourses/Data-Analysis-with-Python/blob/main/Python/instructions/IDE-review.md)
* [Как пользоваться Яндекс.Контестом?](https://github.com/MSUcourses/Data-Analysis-with-Python/blob/main/Python/instructions/yandex_contest.md)
* [На что обращать внимание при работе с вводом-выводом?](https://github.com/MSUcourses/Data-Analysis-with-Python/blob/main/Python/instructions/input-output.md)
* [Как использовать Google Colab в качестве среды разработки?](https://github.com/MSUcourses/Data-Analysis-with-Python/blob/main/Python/instructions/GoogleColab.md)

## 📞 Контакты
* [Телеграм-канал](https://t.me/+p52yYKfqD040NGMy) с основной информацией по курсу
* [Телеграм-чат](https://t.me/+UcXax0tW_3JhZmJi) для вопросов, связанных с курсом
* [Телеграм-бот](https://t.me/msumfk_bot) для получения доступа к домашним заданиям, записи на консультации и вопросов, связанных с курсом
