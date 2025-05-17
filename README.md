# detection-of-phishing-sites
Detection of Phishing Sites | Colab Notebook
https://colab.research.google.com/drive/1VwAyAWwm7JsPkE6sCV5dNHLhHHixEi8B?usp=sharing
Проект: Мультимодальная нейросетевая модель для детекции фишинговых сайтов
Технологии:
Python, TensorFlow/Keras, Scikit-learn
Гибридная архитектура (CNN + Bidirectional LSTM)
Обработка текста (Tokenizer, Embeddings) + числовые признаки URL
Ключевые результаты:
✅ F1-score: 0.96 ± 0.016 (10-fold cross-validation)
✅ Лучший фолд: F1=1.0 (идеальное детектирование)
✅ ROC-AUC: 0.98 ± 0.013
✅ Интерпретируемость: Выделены топ-10 фишинговых ключевых слов
Особенности реализации:
Стратифицированная кросс-валидация
Балансировка классов через class_weight
Оптимизация: AdamW + ReduceLROnPlateau
Визуализация: матрица ошибок, ROC-кривая, графики обучения
