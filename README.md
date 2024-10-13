# Currency-Converter-Application
This is a simple application based on JavaFX that converts currencies using the latest exchange rates obtained through FreeCurrencyAPI. 
The application provides an easy-to-use interface where users can select currencies and input the amount for conversion.

Functional Features:

1. Input Amount for Conversion:
   - A text field where the user can enter the amount of money they want to convert.

2. Select the Source Currency:
   - Uses a dropdown list (`ComboBox`) where users can select the currency from which they want to convert. The list is automatically populated with up-to-date currency codes fetched from the API.

3. Select the Target Currency:
   - A second dropdown list (`ComboBox`) allows users to select the currency into which they want to convert. The list is also automatically populated with data from the API.

4. Convert Button:
   - The "Convert" button triggers the currency conversion process, after which the result is displayed on the screen.

5. Display Result:
   - The conversion result is displayed in the format: `<amount> <source currency> = <converted amount> <target currency>`. For example, `100 USD = 85.37 EUR`.

6. Error Handling:
   - Potential errors are handled:
     - If the user inputs an invalid amount (e.g., text instead of a number), an error message is displayed.
     - If there is no connection to the API or another error occurs while loading data, a corresponding error message is shown.
     - The program checks whether the currencies are selected and displays a message if one of them is missing.

7. Fetching Up-to-Date Currency Rates:
   - The application fetches currency exchange rates through FreeCurrencyAPI in JSON format using an HTTP request. The exchange rates are stored in a map (where the key is the currency code and the value is the exchange rate).

![image](https://github.com/user-attachments/assets/10723565-d7c9-4556-9846-2e5b6d403c5c)                   ![image](https://github.com/user-attachments/assets/8d520f43-9b8c-44db-a100-f9b1cc024bc3)              ![image](https://github.com/user-attachments/assets/ebe5002c-2ec8-4118-891c-baf8c336b76f)

Dependencies of the application:

JavaFX — for the graphical user interface.
org.json — for working with JSON.
Java SE standard libraries — for HTTP requests (HttpURLConnection, BufferedReader).

This project is useful for several reasons:

1. Practice with JavaFX: It allows learning how to create graphical user interfaces in Java, which is valuable for desktop application development.
  
2. Integration with external API: It demonstrates how to send HTTP requests and process JSON responses, which is important for building applications that interact with web services.

3. Currency converter implementation: The application can be used as a simple and convenient tool for currency conversion using real-time exchange rates.

4. Exception handling: The project includes handling various errors, which teaches proper exception management in applications.

5. Extensibility: This project can serve as a foundation for building more complex financial or analytical applications.

The "Currency Converter" application is a useful tool for converting currencies using current exchange rates. It demonstrates key aspects of graphical interface development using JavaFX and integration with external APIs to fetch real-time data.

Key Takeaways about the Application:

1. User-Friendliness The intuitive interface allows users to quickly and easily convert currencies by entering the required data and selecting the appropriate currencies from dropdown lists.

2. Technological Relevance The use of JavaFX and working with JSON via HTTP requests reflects modern approaches in application development that often interact with web services.

3. Error Handling The application includes error-handling mechanisms, enhancing the user experience and making it more reliable.

4. Broad Opportunities for Development This project can serve as a foundation for creating more complex applications in the financial domain, including functionality for data analysis and additional currency operations.

Overall, this application not only fulfills its primary function but also provides developers with practical experience in creating user interfaces and working with APIs.



Это простое приложение на основе JavaFX, которое конвертирует валюты с использованием последних курсов обмена, полученных через FreeCurrencyAPI. 
Приложение предоставляет удобный интерфейс, где пользователи могут выбрать валюты и ввести сумму для конвертации.

Функциональные особенности:

1. Ввод суммы для конвертации:
   - Текстовое поле, в которое пользователь может ввести сумму денег для конвертации.

2. Выбор исходной валюты:
   - Выпадающий список (`ComboBox`), где пользователь может выбрать валюту, из которой хочет конвертировать. Список автоматически заполняется актуальными валютными кодами, полученными через API.

3. Выбор целевой валюты:
   - Второй выпадающий список (`ComboBox`), позволяющий выбрать валюту, в которую нужно конвертировать. Список также автоматически заполняется данными из API.

4. Кнопка конвертации:
   - Кнопка "Convert" запускает процесс конвертации валюты, после чего результат отображается на экране.

5. Отображение результата:
   - Результат конвертации отображается в формате: `<amount> <source currency> = <converted amount> <target currency>`. Например, `100 USD = 85.37 EUR`.

6. Обработка ошибок:
   - Возможные ошибки обрабатываются:
     - Если пользователь ввел некорректную сумму (например, текст вместо числа), выводится сообщение об ошибке.
     - Если нет подключения к API или возникла другая ошибка при загрузке данных, выводится соответствующее сообщение.
     - Программа проверяет, выбраны ли валюты, и выводит сообщение, если одна из них не выбрана.

7. Получение актуальных курсов валют:
   - Приложение получает курсы обмена валют через FreeCurrencyAPI в формате JSON с помощью HTTP-запроса. Курсы валют сохраняются в виде карты (где ключ — это код валюты, а значение — курс валюты).
  
![image](https://github.com/user-attachments/assets/10723565-d7c9-4556-9846-2e5b6d403c5c)         ![image](https://github.com/user-attachments/assets/8d520f43-9b8c-44db-a100-f9b1cc024bc3)        ![image](https://github.com/user-attachments/assets/ebe5002c-2ec8-4118-891c-baf8c336b76f)

Зависимости приложения:

- JavaFX — для графического интерфейса.
- org.json — для работы с JSON.
- Стандартные библиотеки Java SE — для выполнения HTTP-запросов (HttpURLConnection, BufferedReader).

Этот проект полезен по нескольким причинам:

1. Практика с JavaFX: Позволяет научиться создавать графические пользовательские интерфейсы на Java, что полезно для разработки настольных приложений.
  
2. Интеграция с внешним API: Демонстрирует, как отправлять HTTP-запросы и обрабатывать ответы в формате JSON, что важно для создания приложений, взаимодействующих с веб-сервисами.

3. Реализация конвертера валют: Приложение можно использовать как простой и удобный инструмент для конвертации валют с использованием актуальных курсов обмена.

4. Обработка исключений Проект включает обработку различных ошибок, что учит правильному управлению исключениями в приложениях.

5. Расширяемость Этот проект может служить основой для создания более сложных финансовых или аналитических приложений.


Приложение "Currency Converter" представляет собой полезный инструмент для конвертации валют, используя актуальные курсы обмена. Оно демонстрирует ключевые аспекты разработки графических интерфейсов с помощью JavaFX и интеграцию с внешними API для получения данных в реальном времени.

Основные выводы о приложении:

1. Удобство использования Интуитивно понятный интерфейс позволяет пользователям быстро и легко конвертировать валюты, вводя необходимые данные и выбирая соответствующие валюты из выпадающих списков.

2. Технологическая актуальность Использование JavaFX и работы с JSON через HTTP-запросы отражает современные подходы в разработке приложений, которые часто взаимодействуют с веб-сервисами.

3. Обработка ошибок Приложение включает механизмы обработки ошибок, что улучшает пользовательский опыт и делает его более надежным.

4. Широкие возможности для развития Этот проект может стать основой для создания более сложных приложений в области финансов, включая функционал для анализа данных и дополнительных валютных операций.

В целом, данное приложение не только выполняет свою основную функцию, но и предоставляет возможность разработчикам получить практический опыт в области создания пользовательских интерфейсов и работы с API.
