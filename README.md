# CustomBG
***Описание мода:***  
CustomBG - мод позволяющий ставить статичный задний фон в меню.  
(*Любителям играть с ТП или создавать GDPS / FanMade самое то!*)  
  
![](/assets/images/cutsombgmenu.png)  
  
![](/assets/images/custombgicon.jpg)  
  
***Установка мода:***  
- Скачиваем файл "custombg.zip" и распаковываем  
- Перекидываем ".geode" в папку с Geometry Dash
- Ресурсы ".png, .json" перекидываем в папку "Resources" где находиться Geometry Dash

***Настройка мода:***  
Открываем ".json" и видим ***"NoGroundInLevelSearchLayer": true***  
True - убирает пол в меню где находиться оффициальные уровни.  А False показывает.  
  
![](/assets/images/NoGroundsFalse.png)  ![](/assets/images/NoGroundsTrue.png)  
  
Дальше идёт сам задний фон. ***"name.png"*** название картинки которая будет задним фоном в меню.  
*РАЗРЕШЕНИЙ ДЛЯ ФОНА:  
".png = 480 x 270"  
"-hd.png = 960 x 540"  
"-uhd.png = 1920 x 1080"*  
```
	"backgrounds": {
		"MenuLayer": 	         "name.png",
		"CreatorLayer":          "name.png",
		"GarageLayer":           "name.png",
		"LevelSearchLayer":      "name.png",
		"LevelBrowserLayer":     "name.png",
		"LevelSelectLayer":      "name.png",
		"LevelInfoLayer":        "name.png",
		"LeaderLayer":           "name.png",
		"GauntletLayer":         "name.png",
		"GauntletSelectLayer":   "name.png",
		"EditLevelLayer":        "name.png"
	}
```  
MenuLayer - Меняет задний фон в главном меню.  
CreatorLayer - Меняет задний фон в меню с выборами (*Gauntlet, Weekly, Daily и т.д*).  
GarageLayer - Меняет задний фон в меню с иконками.  
LevelSearchLayer - Меняет задний фон в меню поиска уровней.  
LevelBrowserLayer - Меняет задний фон в меню со списком онлайн / созданных уровней.  
LevelSelectLayer - Меняет задний фон в меню с оффициальными уровнями.  
LevelInfoLayer - Меняет задний фон в меню онлайн уровня.  
LeaderLayer - Меняет задний фон в таблицах лидеров.  
GauntletLayer - Меняет задний фон в меню со списками гаунтлетов.  
GauntletSelectLayer - Меняет задний фон внутри гаунтлета (*Тоесть список уровней в определенном Gauntlet*.  
EditLevelLayer - Меняет задний фон в меню при созданий / редактора уровня (*Тоесть где название, описание, вход в редактор уровня и т.д*).
