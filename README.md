# Установка Jupyter Notebook 

## Windows 10/11

### Шаг 1: Скачивание и установка Anaconda

1. **Скачайте установщик Anaconda**:
    - Перейдите на [официальный сайт Anaconda](https://www.anaconda.com/download).
    ![](https://i.postimg.cc/R0vzbmnZ/temp-Imageu-Cqh-S8.avif)
    - Нажмите **Skip registration**
    - Скачайте Anaconda для Windows

2. **Установите Anaconda**:
   - Запустите скаченный установщик.
   - Выберите "Just Me" или "All Users" в зависимости от ваших предпочтений.
   - Убедитесь, что опция "Add Anaconda to my PATH environment variable" отключена (рекомендуется).
   - Завершите установку, следуя подсказкам установщика.

### Шаг 2: Запуск Jupyter Notebook

1. **Запустите Anaconda Navigator**:
   - После установки Anaconda найдите и запустите "Anaconda Navigator" из меню "Пуск".
   ![](https://i.postimg.cc/GmhWkK04/2024-05-07-20-45-36.png)

2. **Запустите Jupyter Notebook**:
   - В Anaconda Navigator нажмите на значок "Launch" рядом с Jupyter Notebook.
   ![](https://i.postimg.cc/GtxfD8qP/2024-05-07-20-46-14.png)
   - Откроется браузер с интерфейсом Jupyter Notebook.

### Шаг 3: Альтернативный способ запуска Jupyter Notebook через Anaconda Prompt

1. **Создайте папку, где будете делать проект**
![](https://i.postimg.cc/63sb1LPL/2024-05-07-20-52-06.png)
На картинке выше я создал папку в директории: ```C:\Users\Андрей\Desktop\jupyter```

2. **Откройте Anaconda Prompt**:
    - Найдите "Anaconda Prompt" в меню "Пуск" и запустите его.
    - Введите в терминале "Anaconda Prompt" команду  
    ```cd C:\Users\Андрей\Desktop\jupyter```
    ![](https://i.postimg.cc/TwrN85M8/2024-05-07-20-57-52.png)
    Только замените путь **C:\Users\Андрей\Desktop\jupyter** на путь до своей папки.  
    Немного про команду **cd** (_"change directory"_). Она используется для навигации между различными папками в файловой системе. Синтаксис команды: 
     ```bash
     cd [путь]
     ```

3. **Запустите Jupyter Notebook**:
   - Введите в Anaconda Prompt команду:
     ```bash
     jupyter notebook
     ```
     ![](https://i.postimg.cc/DZjJwBK1/2024-05-07-21-09-46.png)

   - Откроется браузер с интерфейсом Jupyter Notebook. Если браузер не откроется автоматически, то скопируйте ссылку из терминала Anaconda Prompt и вставьте в браузер.


## macOS

1. **Установите Jupyter Notebook через pip**:  
В терминале введите:
   ```bash
   pip install jupyter
   ```
   ![](https://i.postimg.cc/6QHn89r7/2024-05-07-21-19-20.png)
2. **Создайте папку, где будете делать проект.**
   - Создайте папку
   ![](https://i.postimg.cc/xd9cGWfK/2024-05-07-21-16-15.png)
   - Скопирутйе путь до папки, которую вы создали до этого. 
     * Для этого наводим курсор на папку и нажимаем правую кнопку мыши (или двумя пальцами на touchpad). 
     * Удерживаем «волшебную» клавишу [option] и выбираем из контекстного меню появившийся пункт «Скопировать путь до…».
   - У меня это путь ```/Users/galoev/Documents/instuction/my_project```
   ![](https://i.postimg.cc/MZBfS0Ff/2024-05-07-21-26-06.png)

3. **Запустите Jupyter Notebook**:
   - Введите в терминале команду  
     ```bash
     cd /Users/galoev/Documents/instuction/my_project
     ```
     Только замените путь **/Users/galoev/Documents/instuction/my_project** на свой путь
    - В терминале введите:
      ```bash
      jupyter notebook
      ```
      ![](https://i.postimg.cc/L4k4DxWD/2024-05-07-21-34-55.png)
   - Откроется браузер с интерфейсом Jupyter Notebook.
