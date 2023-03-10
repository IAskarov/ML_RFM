# Сегментирование клиентов онлайн-магазина подарков

**Бизнес-задача:** произвести сегментацию существующих клиентов, проинтерпретировать эти сегменты и определить стратегию взаимодействия с ними.

**Техническая задача**: построить модель кластеризации клиентов на основе их покупательской способности, частоты заказов и срока давности последней покупки, определить профиль каждого из кластеров.

# Основные цели проекта:
- Произвести предобработку набора данных.
- Провести разведывательный анализ данных и выявить основные закономерности.
- Сформировать категории товаров и клиентов.
- Построить несколько моделей машинного обучения, решающих задачу кластеризации клиентов, определить количество кластеров и проинтерпретировать их.
- Спроектировать процесс предсказания категории интересов клиента и протестировать вашу модель на новых клиентах.

Итак, у нас есть данные о более чем полумиллионе транзакций. Каждая из них описывается следующими признаками:
- InvoiceNo — номер счёта-фактуры (уникальный номинальный шестизначный номер, присваиваемый каждой транзакции; буква "C" в начале кода указывает на отмену транзакции);
- StockCode — код товара (уникальное пятизначное целое число, присваиваемое каждому отдельному товару);
- Description — название товара;
- Quantity — количество каждого товара за транзакцию;
- InvoiceDate — дата и время выставления счёта/проведения транзакции;
- UnitPrice — цена за единицу товара в фунтах стерлингов;
- CustomerID — идентификатор клиента (уникальный пятизначный номер, однозначно присваиваемый каждому клиенту);
- Country — название страны, в которой проживает клиент.
