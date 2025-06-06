Документация Инженера
====

Данный репозиторий содержит материалы команды YO YAO, участвующщей в секции Future Engineers, создания самоуправляемой машины, сезона 2025 WRO.

## Контент

* `t-photos`содержит 2 фото комадны (одно из которых официальное, а другое неофициально, оба фото включают всех участников команды)
* `v-photos` содержит 6 фоток робота (с каждой стороны робота, сверху и снизу), а также дополнительно привидены подробный инструкции по сборке основных компонентов нашего робота
* `video` содержит файл video.md с ссылкой на видео с ездой робота
* `schemes` содержит фото со всеми электрическими компонентами, который были использованы и как они используются в нашем роботе и связаны между собой
* `src` содержит код, программу для всех компонентов робота с пояснениями в коде
* `other` описание того как были соединены компоненты между собой и как производится взаимодействие
## Введение
 Первая версия нашего робота для участия на региональных отборчных была создана из деталей набора LEGO EV3, однако столкнувшись с большими проблемами и критическими ошибками нами было принято решение полностью пересмотреть наше решение. Позже мы обнаружили наборы LEGO SPIKE, которые в отличии от набора LEGO EV3 продолжал поддерживаться компанией LEGO, а также детали данного набора были более высокого качества по сравнению с деталями набора LEGO EV3. 
 
 Помимо набора LEGO SPIKE мы рассматривали и другие возможные решения, такие как использование Raspberry PI Zero W, исполльзование искусственного интеллекта и камеры для организации поворота и объезда препятствий на раунде Obstacle Challenge и другие, однако для реализации наших идей нам не хватало умений. Вследствии чего, собранные нами прототипы были хуже, чем изначальный робот, собранный из деталей набора LEGO EV3. После чего мы приняли решение попробовать детали из набора LEGO SPIKE. Далее последует описание решения, которое было подготовлено нами на Республиканский этап World Robotics Olympiad.   
 
 Робот был собран из деталей комплекта LEGO Spke, на одном блоке, хабе из данного издания. Были использованы следующие моторы и датчики: большой мотор, средний мотор, ультразвуковой датчик света, датчик расстояния в количестве 3 штук. Провода были подключены последовательно, отдавая приоритет каждой детали соответственно. Программа для робота была написана используя блок-код, программы SPIKE App. Поворотная система была реализована при помощи датчиков, которые измеряли расстояние до внутренних и внешних стен, при достаточном приближении к внешней стене и отсутствия внутренней стены в поле видимости датчика совершается поворот.

 
