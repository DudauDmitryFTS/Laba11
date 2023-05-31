# Тема 3 Создание сложных приложений c Compose.
## Часть 3. События в Compose

## Порядок выполнения лабораторной работы:
- Для выполнения лабораторной работы Вам нужно сделать Fork данного репозитория в свою учетную запись на GitHub.
- После чего осуществить [клонирование](https://docs.github.com/ru/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop) удаленного репозитория себе на компьютер.
- Открыть и запустить проект в Android Studio.
- Внести изменения в проект согласно файла с каждым пунктом заданиия.
- Зафиксировать изменения и отправить их на GitHub для каждого пункта задания (есть в Google class).
- Предъявить работу преподавателю: 
    - Запущенное приложение либо в эмуляторе, либо на телефоне;
    - Удаленный репозиторий в GitHub с историей изменений (commit) `(если истории фиксации изменений не будет - это будет приравниваться к невыполнению задания)`.
## Описание предметной области 
1. Сделал клонирование репазитория.
2. Создал файл JoinButton.kt в пакете components и добавил базовую структуру кнопки в файл.
3. Затем я добавил состояние для кнопки - IDLE и PRESSED, чтобы управлять ее поведением. 
4. Я использовал JoinButton() для управления состоянием кнопки и вызвал эту функцию в функции Post() для добавления кнопки в приложении.
Чтобы обновить Header(), чтобы он мог принимать onJoinButtonClick передавать его в JoinButton(), я внес некоторые изменения в код.
5. Наконец, я компилировал и запускал приложение, чтобы убедиться, что кнопка работает должным образом.
6. Когда приложение перестала показывать ошибки, завершил лабораторную работу.
