# Articles

## Описание

Программа генерирует статьи из слов. Слова и статьи хранятся в базе данных <a href="http://hsqldb.org/">HSQLDB</a>, хранимой в виде
файла.

## Технологии

* Java
* HSQLDB
* Slf4j, Log4j
* Maven
* Checkstyle

## Запуск через терминал

<p>1. Собрать jar через Maven</p>

```bash
mvn install
```
<p>2. Запустить jar файл</p>

```bash
java -jar target/app.jar
```

## Запуск через IDE

1. Перейте к папке ``src/main/java`` и файлу ``ru.job4j.articles.Application``
2. Нажать на кнопку запуска метода ``main`` в IDE
