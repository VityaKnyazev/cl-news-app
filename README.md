<h1>CLEVERTEC (final task)</h1>

<p>CLEVERTEC final task:</p>


<p>Требования:</p>

<ol>

<li>
Требования и их реализация изложены в файлах README.md миросервисов (config, users, news).
</li>

</ol>

<h3>Порядок запуска и использование:</h3>

<ol>

<li>Билдим cloud config server приложение: cd /cl-config и .\gradlew clean build 
Запускаем cloud config server в docker: docker-compose up -d
</li>

<li>Билдим users microservice app: cd ../cl-users и  .\gradlew clean build 
Запускаем users microservice app в docker: docker-compose up -d
</li>

<li>Билдим главное новостное приложение news app: cd ../cl-news и .\gradlew clean build 
Запускаем news app в docker: docker-compose up -d
</li>

</ol>

<ol>
<li>Примеры ендпоинтов описаны в README.md микросервисов</li>
</ol>
