```
CREATE DATABASE IF NOT EXISTS movie_manager;


CREATE TABLE `movie` (
    movie_id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    release_year INT,
    genre VARCHAR(100),
    director VARCHAR(255)
);

```

Run in terminal with env

```
MYSQL_HOST='movie-manager.ct51vyrywran.us-east-1.rds.amazonaws.com' MYSQL_USER='admin' MYSQL_PW='rootroot' MYSQL_DB='movie_manager' node index.js
```


