# Начало работы

## Установка

Под linux ставим из пакетов `apt install golang`

Пользователи MacOS могут воспользоваться `brew install go`

Установочные файлы для других операционных систем (MS Windows, Darwin, ARM) или
исходники можно скачать с официального сайта: https://golang.org/dl/.

## Настройка окружения

В основном, вся настройка сводится к установке переменной окружения GOPATH, данная
переменная определяет путь к рабочей директории (workspace). Для чего нужна эта переменная
мы разберем в дальнейшем.

Все примеры, которые приведены в дальнейшем, находятся в папке `src` данного репозитория.
Вы можете склонировать данный репозиторий, чтобы в дальнейшем не набирать примеры вручную.

```
git clone https://github.com/pahanini/go-for-php-developers-book.git
```

Сделаем директорию репозитория рабочей (linux):

```
export GOPATH=path-to/go-for-php-developers-book
```

Windows:
```
set GOPATH=`path-to\go-for-php-developers-book`
```

В дальнейшем, говоря о рабочей директории, мы будем иметь в виду директорию
с этим репозиторием.

## IDE

[IDEA](https://www.jetbrains.com/idea/) и [Atom](https://atom.io/) поддерживают работу
с Go через соответствующие плагины.
