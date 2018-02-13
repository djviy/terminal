# terminal
 Комманды терминала

#### Установка **tree**
*Плагин для отображения дерева папок и файлов*  
Ubuntu/Debian: sudo apt-get install tree  
macOS: brew install tree [Установить brew](https://www.google.com)
------
## Файловая структура
------
**ls** - файлы и папки в текущей директории  
**pwd** *(Print working directory)* - отобразить рабочую директурию  
**mkdir** создать директорию
**mkdir -p Folder1/Folder2** - создание директорый рекурсивно
**touch File1** - создание файла
**tree Folder1** - дерево папки *Folder1*  

### mv Перемещение
**mv Folder1 Folder2** - переместить dir1 в dir2. Команда *move*, т.к. в unix системах нет переименования  
**mv Folder1/* Filder2** - переместить ВСЁ из Folder1 в Folder2

### rm Удаление
**rm File1** - удалить File1  
**rm -r Folder1** -  удаление папки Folder 1  
**rm -r * ** - удалить всё в текущем каталоге
**rm -r Folder/* ** - удалить всё в каталоге Folder
**rm -rf ** - удалить всё. ВАЖНО! Можно *rm -fr /* - можно повредить систему (*f* - force)
