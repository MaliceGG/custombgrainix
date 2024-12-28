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
