# Домашняя работа №3 по курсу "Go. Уровень 2"

### Создал папку проекта и перешел в нее:
```
$ mkdir HW2_3
$ cd HW2_3
```

### Создал проект на GITHUB

### Создал файл README.md (в процессе работы указываю все шаги)
```
$ touch README.md
```

### Создаем модуль hello
```
$ go mod init hello
```


### Создал коммит и запушил
```
$ git add .
$ git commit -m"init commit"
```

### создал тег
```
$ git fetch
$ git tag -a v0.0.1 -m"v0.0.1"
$ git push origin v0.0.1
$ git push origin main
```

### загрузил внешний модуль
```
$ go get rsc.io/quote
```