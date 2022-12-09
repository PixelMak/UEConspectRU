1. Отключить освещение UE4. 
World Settings -> Lightmass -> Force No Precomputed Lights -> True
2. Build -> Build All Levels.
3. Выделить все источники освещения на карте и включить для них настройку Movable. (Point Light, Direction Light и т.д.)
Details -> Transform -> Mobility -> Movable
4. Включить обработку Lumen.
Settings -> Project Settings -> "Engine -> Rendering" -> "Global Illumination -> Lumen"
5. Перезапустить проект.