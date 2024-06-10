# Задания по учебной практике модуля "Системное программирование", группа К0711-23, 2024 год
Ваше задание по распределению ниже нужно выполнить любым из способов - процессами, потоками или asyncio. Можете совмещать способы, если посчитаете это необходимым. Защита предполагает ваше объяснение решения, демонстрацию работоспособности вашего решения.
## Распределение задач
  Вершинина - 1  
  Данилов - 3  
  Иванов - 2  +
  Иноземцев - 1  
  Исаева - 1  
  Коренякин - 2  
  Машталер - 3  
  Ромоданов - 1  
  Тарасов - 2  
  Татарников - 3  
  
# Задачи
## 1
Проджект менеджер и несколько разработчиков работают над задачами вместе. ПМ сообщает разработчикам о появлении новой задачи, к выполнению которой они приступают в случае, если они не находятся в отпуске (у каждого разработчика есть при создании псевдослучайное максимальное число задач, которые он готов выполнить прежде, чем пойти в отпуск на 2 следующие задачи). В случае, если работник в отпуске, он пропускает задачу. Кроме этого, у любого разработчика есть шанс в 5% на то, что с задачей он не справится. Разработчики работают некоторое псевдослучайное время над задачами и сообщают ПМу, что с задачей они справились. Для того, чтобы ПМ посчитал выполнение задачи успешным, он должен получить положительный ответ по выполнению от N-1 разработчиков. При этом ПМ ожидает выполнения задач ограниченное количество времени, в противном случае он сообщает о провале и сбрасывает эту задачу для разработчиков. Работа завершается в случае, если у ПМа больше не осталось задач. Добавить выводы на все части любого действия в программе.

## 2
Два повара и официант обеспечивают обслуживание клиентов в ресторане. От качества их работы зависит удовлетворенность клиента.
Первый повар принимает заказ от официанта и в соответствии с заказом какое-то время подготовливает продукты для его приготовления, передавая их в итоге второму повару.
Второй повар принимает продукты от первого повара, и какое-то время готовит заказ, передавая его официанту. 
Официант передает заказ клиенту. НО! На самом деле официант проверяет то наличие заказов от клиентов, то наличие готовых заказов у второго повара.
Все трое рабочих (два повара и официант) выполняют свою работу с псевдослучайным качеством от 0 до 10 (по любому выбранному вами закону). Качество работы каждого влияет на качество предоставляемой клиенту услуги. Клиент также умножает получившееся значение на псевдослучайный коэффициент (например, от 0.8 до 1.2). Таким образом, становится известно, насколько он доволен своим блюдом.
Добавить выводы всех действий в приложении. Работники работают до тех пор, пока есть клиенты. Как только клиенты заканчиваются, работники выжидают некоторое небольшое время, и закрывают ресторан. Программа завершается.

## 3
Гоночный автомобиль приезжает на пит-стоп. Автомобиль обслуживают 5 работников, каждый из которых выполняет определенную (любую, на ваше усмотрение) работу. Проблема в том, что приступить к обслуживанию они могут только все вместе, но после отъезда автомобиля работникам требуется некоторое псевдослучайное время для того, чтобы подготовиться к обслуживанию следующего. Автомобиль же приезжает на пит-стоп вне зависимости от готовности работников, и по приезду автоматически запускает таймер пит-стопа. Как только работники закончат, таймер останавливается и выводится, а автомобиль уезжает. Программа завершается, когда автомобили перестают приезжать на пит-стоп, и работники дожидались некоторое время, но не дождались больше ни одного автомобиля.
