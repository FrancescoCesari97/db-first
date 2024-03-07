# "Used car " Table

| FIELD     | TYPE        | ATTRIBUTES                         | INDEX |
| --------- | ----------- | ---------------------------------- | ----- |
| id        | INT         | NOT NULL, UNSIGNED, AUTO INCREMENT |       |
| model     | VARCHAR(25) | NOT NULL, DEFAULT("anonymous")     |       |
| company   | VARCHAR(20) | NOT NULL, DEFAULT("anonymous")     |       |
| KM        | INT         | NULL, DEFAULT(0)                   |       |
| plate     | CHAR(7)     | NOT NULL, DEFAULT("not assigned")  |       |
| condition | TEXT        | NULL                               |       |
| price     | DECIMAL     | NOT NULL                           |       |
