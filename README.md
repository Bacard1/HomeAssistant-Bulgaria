<h1 align="center">Home Assistant България</h1>

По-долу ще представя моя проект "Home Assistant", като ще го разделя на части и ще го представя като отделни мини-проекти.
В това хранилище ще обясня накратко идеята, целта и предимствата на всеки проект. Ако някой от тях представлява интерес за Вас, можете да последвате връзката към пълния проект под всяко описание.
<br>
<h1 align="center" color="red">Обобщение</h1>

### Цел на проекта "Home Assistant":

- **Динамичност:** Всички обекти и текстове трябва да могат да се мащабират автоматично в зависимост от размера на екрана или прозореца, като се поддържа удобен изглед в рамките на допустими граници.
- **Опростен и стегнат дизайн:** Лесен за разбиране както от възрастни, така и от деца. Включване на бързи връзки към ключови функции и информация с цел намаляване на препратките между страниците, компенсирано с изскачащи прозорци за по-добра навигация.
- **Оптимизиране на ресурсите:**
    - Намаляване на разхода на ресурси в домакинството чрез автоматизации.
    - Създаване на удобство и ненатрапчиво взаимодействие за обитателите.
- **Изграждане на структура за управление:** Разделяне на зони и групиране на сензори, осветление и превключватели за улеснение в автоматизациите. Въвеждане на йерархия за по-добра организация на групите.
- **Сигурност:** Използване на наличните устройства за защита на дома, когато няма никой в него.
- **Родителски контрол:**
  - Достъп до информация за местоположението на мобилни устройства.
  - Контрол над достъпа и използването на компютрите от деца.
- **Информираност:** Известяване на всички членове на домакинството за важни събития.
- **Интеграция на електроуреди:** Стремеж към интеграция на наличната техника, без да е необходима подмяна, доколкото това е възможно.
- **Независимост:** всичко трябва да работи без достъп до интернет.

<br>

### Снимки от моят "Home Assistant":
| Начална страница:    | Една от стаите:      | Изскачащи прозорци в стаята: |
|:--------------------|:--------------------|:--------------------|
| ![image](https://github.com/user-attachments/assets/c0aa838d-1254-4fec-b54f-724e8a331a81) | ![image](https://github.com/user-attachments/assets/18d63240-3ce3-438b-826e-0aa0712fdc33) | ![image](https://github.com/user-attachments/assets/7376a137-b84c-48b1-b314-85a92bc1495d) |
| Shopllist с картинки: | Интеграции които използвам: | Zigbee мрежа: |
| ![image](https://github.com/user-attachments/assets/4841bfc5-3007-44a6-8944-828c92286d8d) | ![image](https://github.com/user-attachments/assets/85e188d6-8d55-46ad-871b-fb6422578cfa) | ![image](https://github.com/user-attachments/assets/fe2ebfec-5623-446c-8a3c-8a5f1feacf0a) |
| Добавки: | Мониторинг: | Натоварване хардуер: |
| ![image](https://github.com/user-attachments/assets/cb5b7ebb-7234-4821-9867-abe2de667ae3) | ![image](https://github.com/user-attachments/assets/39dbc905-90aa-4b76-8358-399418b98a6e) | ![image](https://github.com/user-attachments/assets/a2139e51-4ebe-4e87-bc3b-c17f58c0a6a9) |


<br>
<h1 align="left" color="red;">Проекти:</h1>


<h3 align="center"><strong>Създаване/Интегриране на Zigbee мрежа </strong></h3>

![image](Statik/IMG/Andere/украса_002.png)
### Предимства на Zigbee мрежата:
- Не зависи от интернет. С добавката Zigbee2MQTT, HomeAssistant сам хоства и потдържа Zigbee устроиствата Ви.
- Не натоварва допълнително основната интерет мрежа.
- Лесна миграция, инсталация на устройства.
- Zigbee устройствата сами по себе си са "Рутери" и удължават сигнала на мрежата.
- Zigbee устройствата са ефтини.
- Лесен ъпгрейд при натоварена мрежа.

| Карта на Zigbee устройства: | Карта на устройства в Zigbee2MQTT: |
|:--------------------|:--------------------|
| ![image](https://github.com/user-attachments/assets/c8c7f7ec-93f8-4f5f-9cc9-c2d30576c9d0)  | ![image](https://github.com/user-attachments/assets/fe2ebfec-5623-446c-8a3c-8a5f1feacf0a) |

<a href="Statik/Projekts/HomeAssistant-Zigbee-Network">
    <img align="center" src="Statik/IMG/Andere/Бутон към целият проект.png" alt="Алтернативен текст" width="30%" height="30%">
</a>
<a href="">
    <img align="center" src="Statik/IMG/Andere/Бутон към.png" alt="Алтернативен текст" width="30%" height="30%">
</a>
</a>


<a href="#" class="myButton">Към проекта</a>

.myButton {
	box-shadow: -1px 2px 0px 2px #9fb4f2;
	background:linear-gradient(to bottom, #2e7bff 5%, #4297ff 100%);
	background-color:#2e7bff;
	border-radius:33px;
	border:3px solid #4e6096;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:28px;
	padding:9px 76px;
	text-decoration:none;
	text-shadow:0px 1px 0px #283966;
}
.myButton:hover {
	background:linear-gradient(to bottom, #4297ff 5%, #2e7bff 100%);
	background-color:#4297ff;
}
.myButton:active {
	position:relative;
	top:1px;
}

<a href="Statik/Projekts/HomeAssistant-Zigbee-Network">
    <img align="center" src="Statik/IMG/Andere/Бутон към Zigbee2MQTT.png" alt="Алтернативен текст" width="30%" height="30%">
</a>


