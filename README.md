FoundryVTT-fallout-ru-compendiums
# Неофициальный перевод компендиумов из Core Rulebook для системы Fallout Roleplaying Game

![image](https://github.com/user-attachments/assets/56c6e796-826c-4313-bd55-f7ce55cc96d2)

В качестве основы перевода был использован перевод Core Rulebook отсюда: [https://pikabu.ru/story/fallout_2d20_the_roleplaying_game_perevod_na_russkiy_10071472](https://docs.google.com/document/d/1qISv-b70rvKzHSAse072rUG7S2QVihRCQemySKasPU0/edit?usp=drive_web&ouid=104747016494815220530)

Перевод выше я редактировал на своё усмотрение (почти все изменения я выделил красным) и в результате источником для терминологии послужил этот вариант перевода: https://docs.google.com/document/d/1de8FzlD4_-I4cKiTrrvd1AETVZCjZg_d/edit?usp=drive_link&ouid=102399268789017924160&rtpof=true&sd=true

## Описание некоторых предметов содержит ссылки для удобства. Для того, чтобы они работали необходимо:

1. Создать копию компендиума

![image](https://github.com/user-attachments/assets/cd092bec-6bdb-4775-9c59-5aa046685803)

2. Назначить название **полностью совпадающее** с оригинальным названием библиотеки. Для этого по сути нужно лишь удалить "(Копия)" из названия.

![image](https://github.com/user-attachments/assets/9c9492cd-1c49-4e27-be59-8daa361f48a3)

![image](https://github.com/user-attachments/assets/0f244aca-2343-4cb3-88de-9d9c896186f2)

3. Повторить для всех остальных компендиумов.

В результате и ссылки будут работать и вы получите независимые копии компендиумов, которые можете редактировать на своё усмотрение, не опасаясь потерять при обновлении модуля. 

### Комментарии по терминологии:

**Scavenging** - Мародёрство (В изначальном переводе был "Поиск Ресурсов", что громоздко и не очень хорошо отражает суть слова Scavenging. Мародёрство тоже не идеально подходит, но лучше я не смог придумать)

**Burst** - Очередь (В изначальном переводе был "Массированный", хотя "Очередь" с русского на английский переводится как "Burst" и по смыслу речь идёт об очереди)

### Прочие комментарии:

1. Как было сказано выше, в отличие от оригинальных компендиумов идущих с системой, эти компендиумы включают ссылки на другие предметы. Например, броня и оружие в описании имеет ссылки на моды, которые можно применить к ним. Это сделано для удобства, чтобы не приходилось каждый раз искать моды и другие предметы в книгах или компендиумах. Для того, чтобы ссылки работали, необходимо создать локальные копии всех компендиумов как это было описано выше.  

2. Ввиду особенности устройства модуля, невозможно сделать автоматически расходуемое оружие, такое как взрывчатка или метательное оружие. Для этого существует отдельно оружие, например Осколочная граната, используемое для совершения бросков атаки и урона, а также отдельно существует боеприпас Осколочная граната, который автоматически расходуется при совершении атак. В описании предметов обоих видов существует ссылка на второй вид, чтобы добавить его в инвентарь для полноценного использования.

3. Также для предметов, которые можно скрафтить, в описании добавлены рецепты крафта с ссылками на ингредиенты, а также указаны необходимые для крафта навыки, перки, вид верстака, сложность и требуется ли рецепт ("Редкий"). Для предметов, которые для крафта требуют лишь материалы, а не конкретные предметы, в описании дана таблица сложности и необходимых материалов, где жирным шрифтом выбрано необходимое значение.

4. Добавлены Штык и Дробилка (моды приклада) в качестве оружия.

5. Добавлены все виды шприцов в виде отдельных боеприпасов. На вкладке "Атрибуты" Инъекционного карабина необходимо выбрать используемый вид шприца в качестве боеприпаса.

6. Добавлены несколько НИПов, на которые ссылаются некоторые предметы. 

### Добавлены случайные таблицы.
Включены все таблицы добычи, а так же осложнения при использовании оружия и мародёрстве. 
Поскольку при нахождении брони совершается бросок для определения части тела, были созданные отдельные таблицы для каждого вида брони, на которую ссылается основная таблица добычи "Одежда и Броня", таким образом, одного броска по ней достаточно. Аналогично сделана система случайных для книг и журналов. 
Касательно шприцов для Инъекционного карабина написано в правилах, что их находят в одном из видов, потому я добавил случайную таблицу для определения найденного вида шприца. 
Ещё добавлены в качестве предметов некоторые оружия с модами, которые указаны в таблицах добычи оружия. Однако, для Плазменного карабина указан мод long barrel, который не поддерживается на Plasma gun (Очевидно, ошибка в Core Rulebook, одна из множества), поэтому я не стал его применять. 
В таблице "Прочее" можно найти несколько предметов, количество которых определяется броском кубов. Формула вставлена в текст и при нахождении необходимо будет нажать на неё для броска кубов (см. ниже). 

![image](https://github.com/user-attachments/assets/c87aaf7a-3fd2-4ebc-8670-e9615d1ee876)

### Кроме того, были обнаружены следующие ошибки в оригинальных компендиумах:
- У мода .50 Ресивер отсутствовало свойство "Жестокий"
- Отсутствие модов long scope и Recon Scope  для лёгкого оружия
- У мода Flamer Barrel отсутствовало свойство Gain Spread
- Отсутствал Boosted Capacitor для энергооружия
- Cкорострельность минигана увеличена с 0 до 5
- Дальность огнемёта уменьшена со средней на ближнюю
- Добавлены отсутствующие данные о крафте модов на Карабин Гаусса

Также, возможно, Вас заинтересует другой мой модуль с переводом этой системы: https://github.com/Super-zapper/FoundryVTT-fallout-ru
