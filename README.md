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

### Модуль 2.
Полезные ссылочки:
- [VIA (VGG Image Annotator)](https://www.robots.ox.ac.uk/~vgg/software/via/)
- [via.html](https://www.robots.ox.ac.uk/~vgg/software/via/via.html)
### Выводы
В целом, наши два разметчика получили отличные результаты.  
У каждого из них были свои идеи при работе с разметкой изображений, и не допустили никаких серьезных ошибок в разметке.  
В итоге, я решил использовать данные из первого разметчика (т.е. df_1), так как в нем содержится больше информации и он более полный.

Более подробную информацию об обработке данных изображений разметки см. также:
- [Colab notebook](https://colab.research.google.com/drive/1zZKYIRrRDK33TuXnf-8n25ErVvXv51Cn?usp=sharing) (Модуль_2 → m4154_Ван_Цюаньюй_Модуль_2_Практическое_задание_colab.ipynb)

### Модуль 3. Мультимодальные данные
### Принцип связки мультимодельных данных:
Принцип связки мультимодельных данных заключается в интеграции и использовании информации из различных модальностей для более полного понимания задачи. Мультимодальные данные могут включать в себя текст, изображения, звук, видео и другие формы информации, связывание этих данных позволяет создавать более эффективные и комплексные модели машинного обучения или искусственного интеллекта.
### Возможные кейсы использования полученных мультимодальных данных (где их можно использовать/какую модель построить и тд):
В этой задаче мы создали мультимодальный датасет об изображениях кошек и собак, так и связанных с ними текстовой информации.
Этот мультимодальный датасет имеет много потенциальных применений в контексте машинного обучения, включая:
1) Классификация изображений: С использованием этого мультимодального датасета можно построить модель классификации изображений, которая автоматически определит, изображен ли на фотографии кот или собака. Это полезно для разработки интеллектуальных фотоальбомов и поисковых систем изображений.
2) Обнаружение объектов: На основе данных изображений кошек и собак можно построить модель обнаружения объектов, которая распознает местоположение кошек или собак на изображении. Это находит применение в областях видеонаблюдения, автономного вождения и других.

Более подробную информацию см. также:
- [Colab notebook](https://colab.research.google.com/drive/1oT3BOKGsF5d8R9MCGOcwoeH8Gvysx13I?usp=sharing) (Модуль_3 → m4154_Ван_Цюаньюй_Модуль_3_Мультимодальные_данные_colab.ipynb)

### Модуль 4.
Мы нашли пример датасета “[African Wildlife](https://www.kaggle.com/datasets/biancaferreira/african-wildlife/data)” с платформы kaggle.  
Пример датасета содержит четырех распространенных животных в природных заповедниках Южной Африки: буйволы, слоны, носороги и зебры.  
Как показано на рисунке ниже:  
![image](https://github.com/gdnjr5233/Data-collection-and-markup-for-machine-learning/assets/64023974/e6c08f08-1238-4d2a-8844-6c93e9d7034c)
Датасет содержит не менее 376 изображений для каждого класса животных, собранных с помощью функции поиска изображений Google и помеченных для обнаружения объектов. Каждый пример в датасете состоит из jpg-изображения и txt-файла с меткой. Изображения имеют разное соотношение сторон и содержат хотя бы один пример определенного класса животных. На одном изображении может присутствовать несколько экземпляров животных. Также на одном изображении могут встречаться представители других классов.
### Такие мультимодальные синтетические данные могут быть использованы в следующих областях:
- Научные исследования
Такие данные могут быть полезными для ученых в области исследования поведения животных, мониторинга экосистем и других областей научных исследований. Анализ изображений и связанной с ними текстовой информации может предоставить сведения о поведении животных, предпочтениях среды обитания и так далее, что может стать научной основой для работ по сохранению природы.
- Образование в области охраны природы
Объединение этих изображений с соответствующей текстовой информацией может создать яркий и образовательный контент, предназначенный для представления обществу экосистемы и животных Южной Африканской природной резервации. Такие учебные материалы могут использоваться в школьном образовании, музейных выставках или онлайн-обучении.
- Распространение в социальных сетях
Создание увлекательного контента с использованием этих данных и его публикация в социальных сетях может способствовать повышению осведомленности о работе по охране дикой природы. Обмен таким контентом и обсуждение его в сети помогут увеличить общественный интерес к охране дикой природы и экосистем.
### Ожидаемый эффект от обнаружения животных:
![image](https://github.com/gdnjr5233/Data-collection-and-markup-for-machine-learning/assets/64023974/85e4e9f1-19e1-40cb-9633-106f6b978cb8)
И конечно, мы также можем дополнить и синтезировать дополнительные данные о дикой природе на основе этого датасета, чтобы сделать его богаче, а также идентифицировать больше животных и повысить точность классификации изображений.  
В целом, такие мультимодальные синтетические данные имеют широкий спектр применения и могут охватывать науку, образование, туризм и социальные коммуникации, способствуя повышению интереса и понимания общества по вопросам охраны природы.
