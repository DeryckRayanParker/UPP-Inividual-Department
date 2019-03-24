Інтегральні тести до підсистеми «Деканат»
Вимоги до системи:
•	Ведення списку учбових семестрів та робочих тижнів
•	Ведення списку студентів, потоків та груп.
•	Ведення списку аудиторій
Тести:
На головній сторінці графічного інтерфейсу підсистеми будуть декілька кнопок для зручної навігації по функціоналу застосування.
Ведення списку аудиторій
Користувач натискає кнопку «Аудиторії». Перед ним має відобразитись список всіх доступних аудиторій. Також, у вікні будуть присутні елементи фільтрації та редагування. Має бути можливість обрати з випадаючого списку номер корпусу або обрати пункт «всі». Якщо користувач обрав певній номер корпусу перед ним мають відображатися лише ті аудиторії, що знаходяться в цьому корпусі. Якщо користувач обрав пункт «всі» - мають відобразитись всі аудиторії, згруповані за номером корпусу. 
Також, буде кнопка «додати», при кліканні на яку має відобразитися вікно створення аудиторії. Якщо аудиторія, яку намагається створити користувач не валідна ( номер аудиторії меньший за 1, така аудиторія вже існує, завеликий номер аудиторії) – программа виведе на екран повідомлення з інформацією про некоректно введені данні. Корпус можна буде обрати с випадаючого списку існуючих корпусів.
Користувач не зможе редагувати аудиторії, а лише створювати та видаляти.
У списку біля кожної аудиторії буде кнопка «видалити». Якщо користувач натисне її, підсистема виведе повідомлення з попередженням, що аудиторія буде видалена назавжди. Якщо користувач натисне «ОК» аудиторія буде видалена з бази, а список з аудиторіями оновиться. Інакше – нічого не відбудеться.
Ведення списку студентів, потоків та груп.
Користувач натискає кнопку «студенти та групи». Перед ним відображається три кнопки : «Студенти», «потоки» та «групи». При натисканні на кожну має відобразитися список усіх студентів, груп та потоків відповідно до вибору користувача. Сторінки будуть подібними. 
Студенти
Відображається список студентів. Над ним буде 2 випадаючих списки, поле для вводу да кнопка пошуку. Користувач може обрати у першому списку потік, а у другому – групи, які йому належать. Якщо потік не обрано, список з групами буде не активний. У полі для вводу можна буде ввести прізвище студента для пошуку. Якщо такого студента немає у заданій групі, або немає взагалі – буде пустій список студентів. Також, студента можна буде шукати за спеціальністю та роком навчання.
Зі списку можна буде обрати конкретного студента. Тоді відкриється сторінка з усіма даними про студента. Їх можна буде відредагувати та зберегти. Якщо користувач введе невалідні данні – система виведе повідомлення на екран та підкреслить стрічки з невалідними даними ( наприклад, цифри у прізвищі студента). Можна змінити групу або потік студента. Для цього є спеціальний випадаючий списко груп, що належать певному потоку. При зміненні потоку, має оновитися список доступних груп. Студента можна видалити. При цьому він має видалитись з групи, до якої належав. Є можливість створити студента. Для цього необхідно обрати потік, потім групу, що  належить до цього потока та коректно заповнити всі данні про студента. При наявності невалідних даних система виведе повідомлення. Якщо всі данні валідні і користувач натисне кнопку «зберегти» в базі з’явиться новий запис про студента, а також, тепер у списку груп він буде відображатися у своїй групі.
Групи
Виводиться список всіх груп. Я можливість фільтрування за номером групи і за потоком.
Користувач не набрає номер та назву потоку та групи, а лише обриає зі списку наявних. Данні про номер групи автоматично оновлюються при виборі потоку. Якщо юзер обирає певну групу, відкривається сторінка з її номером, а також зі всіма студентами, що входять до її складу. Номер можна змінити, якщо ввести коректні данні та якщо групи з таким номером не існує. Інакше користувач побачить повідомлення про помилку та буде змушений змінити дані. Біля кожного запису студента у списку буде 2 кнопки «видалити» та перевести. При видаленні студента, він більше не буде належати до цієї групи та не буде відображатись у списку. При переведені у іншу – користувач зможе обрати певній потік і групу. Після цього – студент буде відображатися у тій групі, куди його було переведено. Групу можна видалити. При цьому всіх студентів, що належали до цієї групи теж буде видалено
Потоки
Буде відображатися список всіх потоків. Якщо обрати певний потік – можна буде побачити всі групи що входять до його складу. Функціонал схожий на «группи». При видаленні потоку – видаляються всі групи, що до нього належали. Групу можна буде видалити окремо, або перенести в інший потік . Якщо в іншому потоці вже буде група з таким номером – нічого не відбудеться та користувач побачить повідомлення про дублікати.

Ведення списку учбових семестрів та робочих тижнів
Коли користувач на головній сторінці обирає «тижні та семестри» він переодить на сторінку, де може обрати «тижні» та «семестри» . При натисканні на копку – відкривається список тижнів та семестрів відповідно.
Тижні
Відсортовані за номером. Можна обрати конкретний семестр та переглянути всі тижні, які йому належать, або повернутись до списку. Можна переглянути обраний тиждень – дату початку та кінця. Редагувати, видаляти та створювати
Семестри
Семестри можна фільтрувати за роком. Рік обирається зі списку доступних. Можна перейти до конкретного семестру, переглянути всі тижні, що до нього належать, їх кількість і довжину семестру ( дата початку першого тижня і дата кінця останнього). Семестр можна створити. При цьому, необхідно указати рік, дату початку семестру та кількість тижнів. Кількість тижнів не може бути меншою за 4 та більшою за 16. Систем має підрахувати дату кінця семестру. Коли користувач натисне кнопку «створити» створиться семестр, та n тижнів, де n – кількість тижнів, введена користувачем. Одному року не може належати більше 3-х семестрів. Тож якщо в році 3 семестри, його не можна буде обрати при створенні нового семестру. Семестр можна видалити. При цьому всі тижні, які йому належали теж буде видалено.


