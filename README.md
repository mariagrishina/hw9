# HW9 - Регулярные выражения
**********
# 1
-  В задание следовало удалить все пустые строки. 
  Использовала регулярное выражение: ^\s+ и и заменила все вхождения на пробел( в  "Replace").
  ![](// https://pp.userapi.com/c846521/v846521629/6651a/l4eyrA4e1BA.jpg /150x100)
# 2
-  В задание следовало найти всех князей и города, имя и название которых оканчивается на "слав". 
  Использовала регулярное выражение: [А-ЯѢ]+[а-яѣ]+(слав)[а-яѣ]+ . 
Всего упоминаний о князьях нашла: 564.
# 3
-  В задание следовало найти все упоминания Новгорода. 
  Использовала регулярное выражение (Нов)+.(город)[^W] . 
Всего упоминаний Новгорода нашла: 58.
