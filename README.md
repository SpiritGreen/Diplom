# Diplom
ВКР бакалавриата "ЛЭТИ". В данной работе на основе модели MobileNet v-3 были разработаны 4 архитектуры свёрточной нейронной сети для распознавания коллекционных карт.
Всего в данном проекте 5 файла:
1). Diplom - None: изначальная архитектура MobileNet v-3 без изменений. Именно эта модель показала наибольшую точность распознавания фотоизображений.
2). Diplom - BN: в данную модель был добавлен слой пакетной нормализации. Скорость обучения увеличилась, но точность распознавания уменьшилась.
3). Diplom - DO: изначальная модель с добавлением слоя DropOut. Время обучения чуть увеличилось, но точность распознавания выше не стала.
4). Diplom - BN + DO: модель, в которую добавили и слой пакетной нормализации, и слой DropOut. Так, конечно, делать не рекомендуется, но ради научного интереса надо было и данную модель тоже проверить. Скорость обучения так же увеличилась за счёт нормализации, но при этом точность распознавания изображений была выше, чем в модели только с BN. Тем не менее, точность вышла ниже, чем в модели без изменений.
5). Diplom - Results: в данном файле содердится код оценки точности обученных моделей нейронной сети. Необходимо лишь загрузить в код необходимый файл с весами обученной модели для проведения оценки точности.
