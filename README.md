# Базовые команды консоли Git.

Git - это программа, которая позволяет отслеживать изменения в программах, текстовых файлах,
больших документах, веб-сайтах и т.д.

В этом репозитории представлен набор основных команд терминала Git.

1. pwd - вывести на экран путь к рабочей папке, в которой мы сейчас находимся.
2. cd - сменить директорию.
3. ls - вывести на экран содержимое директории.
4. ls -a - вывести на экран содержимое директории плюс скрытые файлы.
5. touch - создание нового файла.
6. mkdir - создание директории (папки).
7. mkdir -p - создание за один шаг целой структуры директорий.
8. cp - копирование файлов (необходимо указать, какой файл и куда копируется).
9. mv - перемещение файлов и папок (необходимо указать, что и куда перемещается).
10. cat - чтение файлов, выведет на экран содержимое файла. Работает только с текстовыми файлами.
11. rm - удаление файла.
12. rmdir - удаление пустой папки.
13. rm -r - удаление папки со всем её содержимым.

## Символы консоли Git.

1. ~ - домашняя директория.
2. .. - родительская директория.
3. / - отделение директорий одной от другой.
4. && - объединение команд в одной строке.

Это основные команды и символы для работы в терминале Git.

## Статусы файлов в репозитории (git status)

1. untracked - неотслеживаемый. Новый файл в Git-репозитории.
2. staged - подготовленный. После команды git add.
3. tracked - отслеживаемый. не отображается при вызове команды git status.
4. modified - изменённый. Отслеживаемый файл изменили, но ещё не использовали git commit.