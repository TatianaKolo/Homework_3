# **Практическое задание 1**
# Урок 1. Первое использование контроля версий
## _**Для работы с контролем версий используем следующие команды:**_
* git config -- global user.name - вводит имя для инициализации имени пользователя
* git config -- global user. email – вводит почту пользователя для связи с ним  
* git init - создает новый репозиторий Git (из папки, в которой работаешь)
* git log – используется для просмотра истории коммитов
* git checkout и git checkout master - используется для просмотра внесённых изменений в различные ветви репозитория (в чём разница пока не поняла). 
* сlear – удаляет все команды, отображавшиеся в терминале (это не влияет на историю коммитов)
## При необходимости сохранения внесённых изменений повторяем 2 команды:
1. git add название файла - (таб поможет заполнить имя)
2. git commit -m "обязательно вводим текст об изменениях, который позволит любому пользователю понять, что изменилось" 

# Урок 2. Установка и настройка системы контроля версий
+ git branch – позволяет создавать, просматривать, переименовывать и удалять ветки:
+ git branch name - команда позволяет создавать новую ветку
+ git branch –d name – клманда на удаление ветки
+ git checkout –b name – команда на создание новой ветки с одновременным переходом в эту ветку для работы 
+ git merge name – команда на слияние веток

# Дополнительные команды для работы в Visual Studio
## ctrl S – сохраняет текст документа
## ### - теги форматируют в макдаун, меняют уровень текста, (размер шрифта), всего 6 уровней 

# Text marking
+ (*) одна звёздочка с двух сторон без пробела - *курсив*
+ (**) две звёздочки с двух сторон - **полужирный**
+ (_) нижнее подчёркивание (по одному с двух сторон) - _тоже курсив_
+ (__) нижнее подчёркивание (по два с двух сторон) - __тоже полужирный текст__
+ (_**) с двух сторон - _**полужирный и курсив одновременно**_ или _часть текста только курсивом, а **другая часть и курсивом и полужирным** шрифтом_ или наоборот **часть полужирным шрифтом, _а другая часть - полужирным и курсивом_ одовременно**
+ (~~) две тильды с двух сторон - ~~зачёркнутый текст~~ 
+ (+) плюс и (*) одна звёздочка с пробелом – значок списка (точка)

## Links
Everything is easy with links
<https://gist.github.com/Jekins/2bf2d0638163f1294637#Images>

## Images 
Чтобы вставить изображение, надо написать следующее: ![описание картинки, если она в этой же папке или маршрут к ней](название файла с расширением, например, .png)
![скриншот](2022-11-14_08-35-58.png) 
## ### - теги форматируют в макдаун, меняют уровень текста, (размер шрифта), всего 6 уровней тегов


# <https://gist.github.com/Jekins/2bf2d0638163f1294637#Images>
# ![скриншот](2022-11-14_08-35-58.png) 
>>>>>>> student_4

[def]: D:\УВР\курсы\22-23\брейн\семинары\Test.md

## GitHub (ГитХаб)

1. Делаем форк (**fork**) интересующего нас репозитория. 
2. Делаем **git clone** для нашей версии этого репозитория. Так появляется версия на нашем аккаунте, и именно эту версию мы клонируем. 
3. Создаём ветку с предлагаемыми изменениями.
4. Производим все изменения только в этой ветке. 
5. Отправляем эти изменения на свой аккаунт (**push**). 
6. В окне на GitHub появляется возможность отправить **pull request**

https://gb.ru/posts/soveti-pro-git – Советы для тех, кто осваивает Git

## **The End!**