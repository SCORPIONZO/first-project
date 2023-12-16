 #   Учимся работать с  GIT 

#### GIT это Система контроля версий
----

 Осваиваем навыки ввода запроса в Терминале
   ----
 -  переходим в домашнюю директорию **cd~**
 -  создаем файл командой    **touch**
 -  создаем папку командой   **mkdir**
 - удаляем командой **rm** ; **rmdir** (*при неоюходимости*)
   
 Инициализируем репозиторий
 ----
  - создаем папку и инициализируем ее командой **git init**
  - если есть необходимость разгитить, если что пошло не так **rm-rf.git**
       - ###### *!!!но имей ввиду что эта операция необратима!!!*
  - Проверяем статус репозитория: прописываем команду **git status**
       - если видишь такое сообшение : nothing to commit (create/copy files and use "git add" to track)  то все ок идем дальше

  Добавляем файлы в репозиторий
  ----
  - Добавляем файлы в репозитрий командой **git add**
    
    - например файлы  todo.txt  readme.txt и т.д

   Делаем коммит
   ----
  - вводим команду **git commit** с ключом -m (ключ присваивает коммиту сообщение)
      
  - *команду нужно вводить в той папке, которую определили в качестве репозитория*
    
  Просмотреть историю коммитов
   ----
  - команда ввода запроса **git log**
    
       - *команда по умолчанию выводит коммиты в обратном хронологическом порядке*

  Подитожим
   -----
    
Git — это система контроля версий, которая помогает отслеживать изменения в проекте. Этот инструмент можно использовать как для индивидуальной, так и для командной работы.
Git позволяет сохранять изменения локально и при необходимости возвращаться к предыдущим версиям проекта. Также можно создать удалённую копию на хостинг-платформе, которая работает с Git, и поделиться результатом с другими. Удачи!!! А вот глубже разобраться тебе поможет вот этот модуль от Яндекса 
[Жмякай сюда](https://practicum.yandex.ru/git-basics)


А вот пример того как выглядит в терминале
-------

```kirillatabaev@imac Desktop % mkdir git-status-lesson
kirillatabaev@imac Desktop % cd git-status-lesson 
kirillatabaev@imac git-status-lesson % git init
Initialized empty Git repository in /Users/kirillatabaev/Desktop/git-status-lesson/.git/
kirillatabaev@imac git-status-lesson % touch README.md
kirillatabaev@imac git-status-lesson % git add README.md 
kirillatabaev@imac git-status-lesson % git commit -m 'Добавить README'
[main (root-commit) 43e1b7d] Добавить README
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
kirillatabaev@imac git-status-lesson % ```
    
    
      
    
         
         
         
   






