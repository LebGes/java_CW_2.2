# Контрольная работа 2 (2 семестр)

## Практика

1. Считать файл в список.
2. Создать класс BroadcastsTime работающий со временем в формате (hh:mm)

class BroadcastsTime implements Comparable {
    byte hour() {...}
    byte minutes() {...}
    boolean after(BroadcastsTime t) {...}
    boolean befor(BroadcastsTime t) {...}
    boolean between(BroadcastsTime t1, BroadcastsTime t2) {...}
    ...    
}

3. Создать класс описывающий программу (канал, время, название)
4. Создать и наполнить данными из файла структуру Map<время, List<программа>>
5. Создать List<программа> со всеми программами всех каналов
6. вывести все программы в порядке возрастания канал, время показа
7. вывести все программы, которые идут сейчас
8. найти все программы по некоторому названию
9. найти все программы определенного канала, которые идут сейчас
10. найти все программы определенного канала, которые будут идти в некотором промежутке времени
11. отсортированные данные сохранить в файл формата .xlsx 
