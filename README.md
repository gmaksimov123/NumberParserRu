# NumberParserRU

Напишите на своём любимом языке функцию преобразованию целого числа в строку прописью. В любом падеже и в любом роде. Прототип функции:

```
string sumProp(int nSum, string sGender, string sCase)

nSum - целое число менее триллиона (максимум 999 999 999 999)

sGender - род ("М"-мужской, "Ж"-женский, "С"-средний)

sCase - падеж ("И"-именительный, …, "П"-предложный)
```

Пример вызова функции	Результат

```
sumProp(31, "М", "Р")	"тридцати одного"

sumProp(22, "С", "Т")	"двадцатью двумя"

sumProp(154323, "М", "И")	"сто пятьдесят четыре тысячи триста двадцать три"

sumProp(154323, "М", "Т")	"ста пятьюдесятью четырьмя тысячами тремястами двадцатью тремя"
```