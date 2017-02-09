# Теория компиляторов для неофитов

Вашему вниманию предлагается электронный курс, из которого вы узнаете, как написать компилятор.
Узнаете, с чего начинать, если вы хотите написать свой язык программирования.
Узнаете, что какая магия происходит, когда вы нажимаете build в вашей любимой IDE.
Узнаете, как компилятор понимает, что вы написали в исходнике.
Узнаете, почему разные компиляторы генерируют код с разным быстродействием, 
и как помочь компилятору сделать быстрый код.
Узнаете, почему Java медленнее, чем C, и как производительность JavaScript увеличилась на порядки.
Я постараюсь показать, что сев за компьютер или азяв планшет в руки вы неизбежно сталкиваетесь 
с компиляторами, и что понимая теорию компиляции вы можете изменить свою жизнь к лучшему.

# Содержание

1. [Как построен этот курс](tutorial/howto)
2. [Лекции и лабораторные работы](tutorial/introduction.md)
3. [Курсовой проект](tutorial/project)

# Установка

Для просмотра теории установка не требуется.
Вы можете открыть [первую страницу учебника](tutorial/introduction.md)
в любимом браузере и погрузиться в теорию.
Для выполнения лабораторных работ вам потребуется установить некоторые программы, 
но не беспокойтесь, курс основан на бесплатном программном обеспечении:

1. Вам потребуется JDK, его можно скачать [здесь](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
2. Если у вас нет бороды и свитера, то вероятно вам будет легче писать код в одной из IDE: 
   [IntelliJ IDEA](http://www.jetbrains.com/idea/download), 
   [NetBeans](https://netbeans.org/features/index.html) или 
   [Eclipse](https://eclipse.org/downloads/).
3. Для генерации синтаксического анализвтора нам потребуется [ANTLR](http://www.antlr.org/download.html),
   загрузите, также плагин для выбранной вами IDE.
4. Для генерации байткода нам потребуется библиотека [ASM](http://asm.ow2.org/).

Если вы не знаете, как установить что-то из вышеперечисленного, не волнуйтесь,
мы вернемся к установке, когда нам потребуется что-то из этого программного обеспечения.

# Использование

Проходить курс рекомендуется в порядке, указанном в [этом документе](tutorial/howto).
Курс содержит примеры решения типовых задач теории компиляторов,
вы можете использовать этот код в своих проектах.
Загрузить все исходники можно командой 
```
git clone https://github.com/alepoydes/writing-compiler-for-neophytes.git
```

# Хотите внести свой вклад?

Вместе мы можем сделать курс лучше.
Вы нашли ошибку, вам есть, что добавить, или у вас есть предложение?
Создавайте сообщение на Issue Tracker,
или пишите на почту <lobanov.igor@gmail.com>.

# Разработчики

1. Лобанов Игорь Сергеевич @github/alepoydes

# Лицензия

Учебник и код могут быть свободно использованы в некоммерческих целях при условия сохранения 
ссылок на авторство.
По вопросам коммерческого использования обращайтесь по адресу
<lobanov.igor@gmail.com>.
