//Формат:{Код, newItemCharacter(Код, Название, Улучшаемость, Шагулучшения, Базовоезначение, Цена, Доступноврагам)}
{CharacterStatCode.MaxHP, CreateStat(CharacterStatCode.MaxHP, "максимальноеХП", true, 10, 1f, 1, true)}, 
{CharacterStatCode.Dmg, CreateStat(CharacterStatCode.Dmg, "дамаг", true, 1, 1f, 2, true)}, 

{CharacterStatCode.AtkSpeed, CreateStat(CharacterStatCode.AtkSpeed, "Скоростьатаки", true, 10, 5f, 3, true)}, 
{CharacterStatCode.MoveSpeed, CreateStat(CharacterStatCode.MoveSpeed, "Скоростьпередвижения", true, 10, 5f, 4, true)}, 
{CharacterStatCode.Luck, CreateStat(CharacterStatCode.Luck, "Удача", false, 2, 2f, 5, false)}, 
{CharacterStatCode.CritChance, CreateStat(CharacterStatCode.CritChance, "Шанскрита", true, 0, 10f, 6, true)}, 
{CharacterStatCode.EvadeChance, CreateStat(CharacterStatCode.EvadeChance, "Шансуворота", true, 0, 7f, 7, true)}, 
{CharacterStatCode.Armor, CreateStat(CharacterStatCode.Armor, "броня", true, 0, 2f, 8, true)}, 
{CharacterStatCode.DebuffResist, CreateStat(CharacterStatCode.DebuffResist, "сопротивлениедебафам", true, 0, 3f, 9, true)}, 
{CharacterStatCode.Vampire, CreateStat(CharacterStatCode.Vampire, "Вампирка", true, 0, 1f, 10, true)}, 
{CharacterStatCode.HpFromDropRestore, CreateStat(CharacterStatCode.HpFromDropRestore, "Кол-воХПприподнятиихилки", true, 10, 1f, 11, true)}, 
{CharacterStatCode.DropRadius, CreateStat(CharacterStatCode.DropRadius, "Радиусподбора", true, 10, 1f, 12, true)}, 
{CharacterStatCode.BulletFlySpeed, CreateStat(CharacterStatCode.BulletFlySpeed, "Скоростьполетапули", true, 10, 2f, 12, true)}, 
{CharacterStatCode.BulletTimeAlive, CreateStat(CharacterStatCode.BulletTimeAlive, "Времяжизнипули", true, 10, 2f, 12, true)}