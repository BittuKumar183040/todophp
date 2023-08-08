
# Todo Applicaton
Build using Php and mysql database for single user. In which user can add delete and make as complete to the added todo items.

This application provide modern styling and intractive user experence with responsive User Interface.


## Installation

pull the code from the [repository](https://github.com/BittuKumar183040/todophp.git)

  * setting up Frontend.
  ```bash

  git clone https://github.com/BittuKumar183040/todophp.git
  
  paste the folder into webserver location:
   wamp server - "C:\Wamp\www\"
```
    * setting up Backend.
```bash
  Import the sql database file inside the MySQL database.
    (which is present inside the repository you cloned)
```
  After successfully performing all the steps we see below output:
  ![aDelete](https://github.com/BittuKumar183040/todophp/assets/64475463/b07f46c7-df2b-4172-97c2-b4e6eab37ec1)


## Database Reference

Database name - **todos**


#### Get all items

```http
  SELECT * FROM items;
```

|     id    |   name   |       status       |
| :-------- | :------- | :----------------- |
| `Integer` | `string` |     `Short Int`    |

## Author

- [@BittuKumar183040](https://github.com/BittuKumar183040/)


