# Checkers
Программа для игры во [фризские шашки](https://ru.wikipedia.org/wiki/%D0%A4%D1%80%D0%B8%D0%B7%D1%81%D0%BA%D0%B8%D0%B5_%D1%88%D0%B0%D1%88%D0%BA%D0%B8).

*Необходим интерпретатор Python версии не ниже, чем 3.6*
## Использование
Запустите файл `MainWindow.pyw`, введите размер грани игровой доски (от 4 до 12), выберите сторону, за которую вы будете играть, в диалоговом окне.<br />
За противоположную сторону играть будет компьютер. Если вы хотите сохранить текующую игру, нажмите кнопку `Save`. При следующем запуске сохранённая игра будет автоматически восстановлена на доске.<br />
Если вы хотите начать новую игру, используйте кнопку `New Game`.<br />
Чтобы совершить ход шашкой, кликните на шашку. Все доступные для хода этой шашкой клетки будут выделены красным или зелёным цветами. Фиолетовым цветом будут выделены клетки, в которые шашка может попасть после посещения красных клеток. Чтобы сбросить фокус с шашки кликнине на другую шашку или на свободную клетку.<br />
Для получени справки воспользуйтесь иконкой с вопросиком.<br />
Для сетевой игры с оппонентом запустите процесс игры и кликните на икону `Network game`. Далее, выберите способ поиска оппонента: Автоматически или Вручную. При автоматическом поиске игрок, первый запустивший игру, выбирает размер поля и сторону, за которую он будет играть. После появления окна `Please, wait your opponent` второй игрок, находящийся в той же локальной сети что и первый, запускает процесс игры и без выбора стороны и размера доски начинает игру с полученными от первого игрока цветом и размером доски.<br />
При поиске оппонента вручную, вам придётся выбрать, будете ли вы хостом данной партии. Если да, то вы выбираете размер поля и сторону.<br />
Когда хост выберет параметры игры, ему выведется окно с его IP адрессом и просьбой подождать оппонента.<br />
Оппонент хоста должен отказаться быть хостом и должен ввести IP хоста в поле ввода, когда его об этом попросят.<br />
Далее начнётся игра.
## Установка программы
Сохраните папку со сборкой в произвольном каталоге.<br />
В консоли с помощью команды `pip` установите библиотеку PyQt5:
> C:\\>pip install pyqt5

## Автор
Чернущенко Денис, май 2017 года