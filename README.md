
Manga Store

**Manga Library Management System**

The Manga Library Management System is a Java-based application developed using the Spring Framework. This project provides a comprehensive platform for managing a collection of manga books. Users can perform various operations such as adding new book to the library, editing existing entries, and deleting records. Additionally, the system features a shopping cart functionality, enabling users to add book to their cart for purchase.

Key features:
- **Add Book**: Easily add new book titles to the library with detailed information.
- **Edit Book**: Update existing book details to keep the library current.
- **Delete Book**: Remove book titles that are no longer needed.
- **Shopping Cart**: Select book books and add them to a shopping cart for a seamless purchasing experience.



## Tech Stack

**Languages:** Java , SpringBoot , HTML5 , Thymeleaf

**Server:** Tomcat

**DataBase:** Mysql


## Run Locally

Clone the project

```bash
  git clone https://github.com/Paresh018/Anime-Library-Java.git
```

Add mysql configurations in application properties

```bash
spring.datasource.name=*****
spring.datasource.url= jdbc:mysql://localhost:3306/anime_store?ServerTimezone=UTC
spring.datasource.username=*****
spring.datasource.password=*****
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL57Dialect
```

Run the program in STS / Eclipse / Intellij

 hit url on your browser

```bash
  http://localhost:8080/ 
```


