# VFS-Automa-Plugin

Код предназначен для использования с плагином для браузера Automa. Файлы скачать и импортировать как Workflow в Automa.

Сегодня (20.08.2023) алгоритм содержит три отдельных шага, которые помогут ускорить действия на сайте Визового центра.

## Visa choice and applicant form

Этот алгоритм надо запустить после выбора визы пользователем вручную. Позволяет пройти неактивную кнопку "Продолжить", заполнить автоматически анкету, если были заполнены глобальные переменные в алгоритме. Отключает таймаут бездействия. Останавливается на вкладке "Your details" (следующей после заполнения анкеты и перед календарём).

## Go to payment after slot choice

После выбора пользователем дня и времени нажать Ctrl + Enter и тогда алгоритм быстро прокликает по всем кнопкам до оплаты.

## Go back from payment

На вкладке с надписью Payment Disclaimer при нажатии Ctrl + Shift + Enter алгоритм возвращает на вкладку выбора слота.
