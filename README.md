### Файл с изначальными данными в разархивированном TXT файле хранится в проекте по пути:
  ```
  src/main/resources/file
  ```
#### Для запуска программы нужно выполнить:
  ```
  maven clean package
  ```
#### и затем
  ```
  java -Xmx1G -jar target/MyApp-1.0.jar src/main/resources/file/lng-4.txt
  ```
