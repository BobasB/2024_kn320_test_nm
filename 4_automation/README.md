## Тема: _Автоматизувати запус тестів на Github Actions/Workflows_
### Мета роботи: _Навчитись пиати конфігураційний файл для Github Actions/Workflows та створювати різні пайплайни за автоматизації_

---
### Кроки які ми виконували у даній роботі
- використовуючи графічний інтерфейс налаштували початковий конфігураційни файл [python-app.yml](../.github/workflows/python-app.yml);
- Змінили конфігурацію яка відповідає запуску наших тестів з папки [3_lab](../3_lab/);
- ми створили один воркфлов де використовуємо Пайтон 3.11 (пробували також 3.10, але наше віртуальне середовище вимагає якраз 3.11);
- налаштували команди як запустити на виконання тести, та при їх успішному виконанні вокфлов завершувався успішно;
- згенерували Бадж статусу який буде повідомляти чи правильно проранились тести ч си наша пайплайна у робочому стані;
