| FIELD | TYPE || ATTRIBUTES | INDEXS |
| -------- | ------- || -------- | ------- |
| id | INT |AUTO_INCREMENT, (NOT NULL, UNIQUE, UNSIGNED) | PRIMARY_KEY|
| model | VARCHAR(50) |NOT NULL,| INDEX |
| type_fuel | VARCHAR(30) | NOT NULL, | |
| traction | CHAR(20) | NOT NULL, | |
| brand | CHAR(20) | NOT NULL, | INDEX |
| generation | DATE | NOT NULL, | |
| displacement | SMALLINT | NOT NULL, | |
| color | VARCHAR(30) | NOT NULL, Default("black") | |
| optional | VARCHAR(100) | NULL, | |
| price | INT | NOT NULL,UNSIGNED | |




