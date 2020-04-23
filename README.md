# ETIS
### Тема
    Мобильная версия ЕТИС на андроид
### Состав группы разработчиков
`Студенты 2 курса ПГНИУ группы Фундаментальной информатики и информационных технологий-2:`
* @noctual `Сычёв Иван Андреевич`
* @d0pelganger `Карнушин Никита Вячеславович` 
* @MishaPershakov `Першаков Михаил Алексеевич`
# Техническое задание
## 1. Введение  
### 1.1. Наименование программы  
Наименование — "ETIS"
### 1.2. Назначение и область применения  
Мобильное приложение предназначено для упрощения процесса получения информации студентами.
Предполагается, что приложение включит в себя получение доступа к:  
* Расписанию;  
* Учебному плану;
* Оценкам и рейтингу;
* Пропущенным Занятиям;
* Объявлениям и приказам;
* Литературе и взятым книгам;
* Сообщениям от преподавателей;
* Смене пароля.
## 2. Требования к приложению
### 2.1. Требования к функциональным характеристикам  
Приложение должно обеспечивать возможность выполнения перечисленных
ниже функций:  
* Вход в личный кабинет и возможность повторной авторизации в системе ЕТИС без ввода логина и пароля при истечении срока жизни сессии.  
* Возможность получения информации по учебному плану, расписанию, оценкам и рейтингам.
* Возможность получения сообщений от преподавателей.
* Возможность смены пароля.
* Возможность получения информации о пропущенных занятиях.
* Возможность получения информации по объявлениям.
* Возможность получения информации о приказах.
* Возможность просмотра рекомендуемой литературы.
* Возможность просмотра взятых книг из библиотеки.
### 2.2. Требования к надежности
Функционирование Мобильного приложения без зависаний и критических ошибок. По возможности минимизировать расход трафика. 
### 2.2. Требования к программному обеспечению
ОС android с API Level не ниже 15 (Android 4.0.3, 4.0.4).
## 4. Стадии и этапы разработки
### 4.1. Стадии разработки
Разработка должна быть проведена в три стадии:
1. Разработка технического задания;
2. Создание приложений;
3. ~~Загрузка приложений в общий доступ;~~
### 4.2. Этапы разработки
На стадии разработки технического задания должен быть выполнен этап разработки, согласования и утверждения настоящего технического задания.  
На стадии создания приложения должны быть выполнены перечисленные
ниже этапы работ:  
* Разработка приложения;
* Проведение испытаний приложения.
*~~На стадии загрузки приложения в общий доступ должны быть выполнены работы по загрузке приложений в Google Play.~~
## 5.3. Содержание работ
1. Проектирование приложения (на бумаге).  
1.1. Проработка структуры (решаем, где и что будет находиться).  
1.2. Подбор цветовых решений для интерфейса.  
2. Создание класса для получения информации из вэб-версии информационной системы ЕТИС.  
2.1. Анализ HTTP запросов и исходного кода страниц.  
2.2. Создание методов класса для авторизации, парсинга информации о расписании, оценках и рейтингах, учебном плане.  
2.3. Тестирование.  
3. Создание интерфейса.  
3.1. Создание activity авторизации.  
3.2. Создание меню.  
3.3. Создание activity для расписания, оценок, учебного плана.  
3.4. Тестирование интерфейса.    
5. Финальное тестирование приложения.  
## 6. Источники разработки
Документы, на основании которых ведется разработка:  
* ГОСТ 34.602-89  
* ГОСТ 34.601-90  
* Техническое задание
