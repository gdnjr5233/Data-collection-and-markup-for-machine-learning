# Проект в рамках курса "Сбор и разметка данных для машинного обучения" от AI Talent Hub ИТМО
## Классическая задача классификации изображений - 🐱 or 🐶
### Модуль 1. Введение в сбор данных  
Cсылочки:
- [Open dataset cats and dogs from the Kaggle platform](https://www.kaggle.com/datasets/tongpython/cat-and-dog/data)
- [Web-scraping — dogs](https://pixnio.com/ru/%25D1%2584%25D0%25BE%25D1%2582%25D0%25BE/%D0%B6%D0%B8%D0%B2%D0%BE%D1%82%D0%BD%D1%8B%D1%85/%D1%81%D0%BE%D0%B1%D0%B0%D0%BA%D0%B8) 
- [Web-scraping — cats](https://pixnio.com/ru/%25D1%2582%25D0%25B5%25D0%25B3/%D0%BA%D0%BE%D1%88%D0%BA%D0%B0)
- [Colab notebook](https://colab.research.google.com/drive/1QefrCfW0jj-GqKXbrjAlOsS6Pw4Xmdvp?usp=sharing) (Пожалуйста, обратите внимание на русское пояснение в маркдауне)
### Возможные применения этих данных в контексте машинного обучения (Выводы)
Данные изображений кошек и собак имеют много потенциальных применений в контексте машинного обучения, включая:
1) Классификация изображений: Использование набора данных изображений кошек и собак позволяет обучить модель классификации изображений, которая автоматически определяет, изображен ли на фотографии кот или собака. Это полезно, например, для разработки интеллектуальных фотоальбомов и поисковых систем изображений.
2) Обнаружение объектов: На основе данных изображений кошек и собак можно обучить модель обнаружения объектов, которая распознает местоположение кошек или собак на изображении. Это находит применение в областях видеонаблюдения, автономного вождения и других.
3) Перенос обучения: Изображения кошек и собак могут быть использованы для переноса обучения, то есть обучения модели на одной задаче и применения ее к другой схожей задаче. Например, модель, обученная на этих данных, может хорошо справляться с задачей классификации других видов животных.

### Модуль 2. Практическое задание
Полезные ссылочки:
- [VIA (VGG Image Annotator)](https://www.robots.ox.ac.uk/~vgg/software/via/)
- [via.html](https://www.robots.ox.ac.uk/~vgg/software/via/via.html)
### Выводы:
В целом, наши два разметчика получили отличные результаты.  
У каждого из них были свои идеи при работе с разметкой изображений, и не допустили никаких серьезных ошибок в разметке.  
В итоге, я решил использовать данные из первого разметчика (т.е. df_1), так как в нем содержится больше информации и он более полный.

Более подробную информацию об обработке данных изображений разметки см. также:
- [Colab notebook](https://colab.research.google.com/drive/1zZKYIRrRDK33TuXnf-8n25ErVvXv51Cn?usp=sharing) (Модуль_2 → m4154_Ван_Цюаньюй_Модуль_2_Практическое_задание_colab.ipynb)
