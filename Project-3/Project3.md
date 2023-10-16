Задачи проекта:
-
1. Составить приемочный тест-кейс для сайта [ToDo List](https://sky-todo-list.herokuapp.com/)
2. Создать коллекцию в Postman на основе тест-кейса
3. Создать заглушки в Mockoon операций Todo-приложения
   - На получение списка  задач должен возвращаться массив из 3 и более задач.
   - На создание задачи  должен возвращаться UUID новой задачи
   - Если в запросе был передан заголовок result со значением empty list, заглушка должна вернуть пустой массив
   - Если title новой задачи содержит слово «ошибка», заглушка должна вернуть HTTP 500 и тело с указанием ошибки
   
Документация проекта:
- 
  - [Приемочный тест-кейс](https://docs.google.com/document/d/1ECwIGDNPu9sQDaXl9gDF9cJVi2TjuId0yZPduvkCMZs/edit?usp=sharing)
  - [Заглушка Mockoon](https://github.com/kenstavichute/QA_engineer/blob/main/Project-3/todolist.json)
  - [Коллекция Postman](https://github.com/kenstavichute/QA_engineer/blob/main/Project-3/acceptance_test_case.postman_collection.json)
