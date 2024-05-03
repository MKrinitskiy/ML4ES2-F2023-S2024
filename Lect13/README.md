## DL4ES, Лекция 13

#### Пакетная нормализация (batch normalization); искусственное дополнение данных (data augmentation); Tensorboard для отладки процесса обучения нейросетей.



Лекция посвящена обсуждению подходов пакетной нормализации данных и внедрения шума  в процесс обучения нейронных сетей посредством искусственного дополнения данных для ускорения и стабилизации обучения.

**Нормализация данных**: Рассматривается подход пакетной нормализации для стабилизации распределения активаций и ускорения обучения.

**Внедрение шума**: Рассматривается искусственное дополнение данных (data augmentation) как способ внедрения шума для улучшения обобщающей способности модели, особенно при недостатке данных.

На практической части лекции демонстрируется использование PyTorch и TensorBoard для построения, обучения нейросетей и анализа процесса обучения через визуализацию распределений активаций, весов и градиентов.

При демонстрации результатов обсуждается влияние аргументации данных на качество модели на примере задачи аппроксимации функции "мексиканская шляпа" и важности мониторинга распределений в процессе обучения для диагностики и коррекции процесса обучения.