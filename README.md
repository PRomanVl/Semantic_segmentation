# Семантическая сегментация изображений

В данном проекте нейросеть учится определять границы родимых пятен.
![image](https://github.com/PRomanVl/Semantic_segmentation/assets/96573887/4ba1a033-41c9-43b6-b56d-197c52959ad2)

Нейросеть состоит из двух частей декодера и энкодера построенных на сверточной архитектуре. Энкодер кодирует изображение в вектор представлений, а энкодер разворачивает этот вектор в изображение сегментированное по признаку наличия или отсутствия родимого пятна на пикселе


Для улучшения качества били использованны разные варианты лосс функций: BCE, FACAL(https://arxiv.org/abs/1708.02002), DICE(https://arxiv.org/abs/1707.03237), Tversky(https://www.arxiv-vanity.com/papers/1803.11078/), Lovasz(https://arxiv.org/abs/1705.08790)
![image](https://github.com/PRomanVl/Semantic_segmentation/assets/96573887/126e24d0-babe-4783-be6c-311ba4cfdca8)


Ссылка на колаб https://drive.google.com/file/d/1fiq2KQbX9yNKGYkaXWKUNpWC8d0srWoV/view?usp=drive_link
