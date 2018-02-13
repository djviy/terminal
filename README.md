# terminal  
Команды терминала  
![alt text](https://github.com/djviy/terminal/blob/master/icon-terminal-128.png "Terminal logo")

### man - программа для вызова справки по другим проргаммам и системным вызовам  
**man mkdir** - справка по вызову программы  
**man -f mkdir** - *-f* - упоминание во всех категориях  
**man mkdir(1)** - например первая категория справки

### Установка **tree**
*Плагин для отображения дерева папок и файлов*  
Ubuntu/Debian: sudo apt-get install tree  
macOS: brew install tree [Установить brew](https://www.google.com)

### История
**history** - история команд  
**~/.bash_history** - история команд (вызывается из домашней категории)  
**!32** - запустить команду 32  
**!!** - повтороить запуск  
**!l** - *l* первая буква начала команды в истории, которая выполнит эту команду
**CTRL + R** **l** - поиск по истории, где встречаются буквы 'l'

### Переменные окружения  
**wich ls** - найти где лежит проргамма ls  
**ls /bin/** - программы  
**env** - переменные окружения  
**PATH** - в переменной *PATH* записан список директорий, в которых ищется исполняемый файл  
**export MYVAR=10** - добавить переменную *MYVAR* в окружение  
**unset MYVAR** - удалить переменную. Работает в рамках текущей сессии  

### Поток
**ls > output** - записать в файл output результат работы проргаммы  
**sort < file1** - отсортировать содержимое файла file1 и вывести на экран  
**sort < file1 > file2** отсортировать file1 и результат записать в file2  
**cat file1 | sort | uniq** - вывод cat из file1 перенаправить в sort (перенаправление STDOUT одного процесса в STDIN другого). *uniq* - убрать дубликаты строк если идут подряд  
**ls | grep file** - вывести на экран файлы содержашие *file*  
**ls | wc** - кол-во строк, букв  
**cat file1 | grep SomeText | sort | uniq | wc -l > file2** - вывести на экран из файла *file1*, отсортировать по тексту *SomeText*, отсортировать по списку, убрать дубликаты, вывести количество строк, записать в *file2*
