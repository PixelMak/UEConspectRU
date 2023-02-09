#Заметки 
Отключаем динамическое освещение и прочие фишки UE5:

1.  **Dynamic Global Illumination Method** -> "None"
2.  **Reflection Method** -> "None" 
3.  **Shadow Map Method** -> "Shadow Map"
4.  **Default RHI** -> "DirectX 11"
5.  Ray Tracing Shadows** -> off

Nanite: Хорошо работает на расстоянии, однако может просаживать FPS при приближении. В этом случае лучше использовать LODы.

Support Global clip plane for Planar reflections - Улучшение отражений в воде.

Заметки по найтркам графики:
- Reflections - влияет на свет и Lumen, на отражение лучей света от материала. На значениях ниже Hight, по ощущениям, вообще отключает отражение лучей света от материалов.