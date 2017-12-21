Первым делом создаем репозиторий на Github'е, копируем его ссылку потом на локальном компе делаем команку clone!

# (# => h1 tag)
## (## => h2 tag)
### (### => h3 tag)



```
(``` такие скобочки над и под для написания фрагмента кода)
```

## Ссылки, стиль текста и списки

* [Ссылка в квадратных скобках](http://www.google.com/) - одна звездочка делает пункт списка
* [Name of link](link adress)
*  *Между одной звездочкой* **Слово между двумя здочками** и ***слово между тремя звездачками***.




**Clone** - clode repo to local machine<br/>
**Commit massege** - что было сделано<br/>
**Push** - upload to repository<br/>
**Pull** - download last version from repo<br/>

**Discard** - descard last changes after commit and before push<br/>

## Log (команды внутри Logs, там где видны все ветки)
<a href="https://ibb.co/diMpaR"><img src="https://image.ibb.co/iOrBpm/TEMP.png" alt="TEMP" border="0"></a>

**Revert commit** - revert to previous version<br/>
**Reset** - Hard reset => удаляет все коммиты которые еще небыли загружены<br/>

### IMAGE UPLOADING  (через сервис ibb.com)

**NEW FORK** - Отдельная полностью не зависемая ветка. Можно использовать для создание feature...<br/>

**Double click on Branch** - cheackout для переключения между ветками

## MERGE  
* Если нужно перенести готовую ветку в основную ветку (master), подтягиваем все изменения из ветки мастер с помощью merge (кликаем на master и merge) И В ВЕТКУ FEATURE добавится код из главной ветки. (СЛИЯНИЕ ВЕТОК)
* Далее переходим в ветку Master и делаем слияние (merge) теперь все есть в master ветке
* Удаляем ветку feature


## Forks conflict
* Когда работаеи в одном файле происходит конфликт при слиянии, нужно сделать двойной клик на коммит и отредактировать так как должен выглядить код из двух источников...дале save

## Всегда создавать новые ветки
* При создании новой фичи или функционала всегда создовать новую ветку

## Важный IGNORE
* Важно игнорировать компилируемые файлы (открыть в гите ветку файлов) для C# папка bin и obj УРОК6 GB

## НЕ УДАЛЯТЬ ИЗ НОВЫХ ВЕТОК ГЛАВНЫЙ ФУНКЦИОНАЛ!
* Потому что при слиянии это удалить эти файлы из главной ветки

## Не делать большие коммиты
* Не эффекстивно
* Ненужный коммит можно откатать (revert commit)
* Cherry-pick commit in LOGS Для того что взять нужный коммит в другую ветку УРОК7 GB


# GIT CONSOLE

* git status -> files stutus ( modifed, added end nothing to )
* git commit -a -m "some commit comment"  -> commit for all files
* git push -> push to repository
















