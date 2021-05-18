# nx_bootcamp_webapp

Это статаический сайт сделаный с помощью Pelican

Для запуска необходимо проделать следующие шаги:
1. Скачать файлы с GitHub к себе на компьютер
2. Если у вас нет Docker - нужно скачать его с официального сайта Docker (https://www.docker.com/products/docker-desktop) 
3. Открыть командную строку и перейти в папочку "host"
4. Выполнить команду "docker build -t some-content ." (Без кавычек)
5. Выполнить команду "docker run --name mysite -d -p 8080:80 some-content" (Без кавычек)
6. Теперь в поисковике (Google, Яндекс или другие) введите "localhost:8080" (Без кавычек)
