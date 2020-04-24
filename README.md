# Breast-Cancer

Аналіз розділений на 4 частини:
1. Визначення проблеми та джерела даних;
2. Дослідницький аналіз даних;
3. Попередня обробка даних;
4. Побудова та оптимізація моделі.

### [Notebook 1](https://github.com/YehorDiachenko/Breast-Cancer/blob/master/1%20Problem%20Identification.ipynb): Визначення проблеми та завантаження даних.
**Мета: визначити тип інформації, що знаходиться в наборі даних.**
В цьому Notebook використовується мова програмування Python для імпорту наборів даних з метою ознайомлення з цими даними та пошуку методу їх обробки.
### [Notebook 2](https://github.com/YehorDiachenko/Breast-Cancer/blob/master/2%20Exploratory%20Data%20Analysis.ipynb): Розвідувальний аналіз.
**Мета: дослідити дані використовуючи засоби їх представлення: графіки, таблиці, діаграми.**
В цьому Notebook застосовуються методи дослідження та візуалізації даних за допомогою бібліотек python (Pandas, matplotlib, seaborn). Ознайомлення з даними - це важливий етап, який надає корисні знання для попередньої обробки даних.
### [Notebook 3](https://github.com/YehorDiachenko/Breast-Cancer/blob/master/3%20Data%20Preprocessing.ipynb): Попередня обробка даних.
**Мета: знайти найбільш прогнозовані ознаки даних та відфільтрувати їх таким чином, щоб це підвищило прогнозовану силу аналітичної моделі.**
В цьому Notebook використовується вибір ознак для зменшення багатовимірності даних. Це важливо для підготовки даних до розробки прогностичних моделей.
### [Notebook 4](https://github.com/YehorDiachenko/Breast-Cancer/blob/master/4%20Predictive%20Model%20Using%20SVM.ipynb): Прогностична модель з використанням методу опорних векторів (SVM).
**Мета: побудувати прогностичну модель SVM для прогнозування діагнозу пухлини молочної залози.**
В цьому Notebook будується прогностична модель, використовуючи алгоритм машинного навчання SVM для прогнозування діагнозу пухлини молочної залози. Діагноз пухлини молочної залози - це бінарна змінна (доброякісна або злоякісна). Також модель оцінюється за допомогою матриці плутанини, що працює на ROC-кривих, які є важливими при оцінці та інтерпретації пристосованої моделі.
### [Notebook 5](https://github.com/YehorDiachenko/Breast-Cancer/blob/master/5%20Optimizing%20SVM%20Classifier.ipynb): Оптимізація SVM класифікатора.
**Мета: побудувати прогностичну модель SVM для прогнозування діагнозу пухлини молочної залози.**
В цьому Notebook налаштовуються гіперпараметри моделі класифікації SVM за допомогою scikit-learn.
### [Notebook 6](https://github.com/YehorDiachenko/Breast-Cancer/blob/master/6%20Comparison%20Between%20Different%20Classifiers.ipynb): Оцінка класифікаторів.
**Мета: отримати дані про кількісні та якісні показники класифікаторів.**
В цьому Notebook автоматизуються стандартні робочі процеси за допомогою python scikit-learn pipelines і оцінюється робота алгоритмів LR, LDA, KNN, CART, NB та SVM.