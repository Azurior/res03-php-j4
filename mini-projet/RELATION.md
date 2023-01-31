|  pages  |         |       media_pages        |        |   media    |
| ------- |     =>  | ------------------------ |        | ---------- |
|   id    |         |       pages_id           |   <=   |            |
|         |         |       media_id           |        |     id     |

| profil |    =>    | media |
| ------ |          | ----- |

|  projects  |         |       media_project      |        |  projects  |
| ---------- |     =>  | ------------------------ |        | ---------- |
|     id     |         |       pages_id           |   <=   |            |
|            |         |       projects_id        |        |     id     |


-------------------------------------------------------------------------------------------------------------------


| profil |    =>    |       category_experience    |           | experiences |
| ------ |          | ---------------------------- |      <=   | ----------- |
|   id   |          |          profil_id           |           |     id      |
|        |          |         experience_id        |           |             |


| profil |    =>    |   category_education |           | education | 
| ------ |          | -------------------- |    <=     | --------- |
|   id   |          |      profil_id       |           |     id    |
|        |          |      education_id    |           |           |


| profil |    =>    |   category_skill |           | skill | 
| ------ |          | ---------------- |    <=     | ----- |
|   id   |          |      profil_id   |           |   id  |
|        |          |      skill_id    |           |       |


| profil |    =>    |   category_hobbies |           | hobbies | 
| ------ |          | ------------------ |    <=     | ------- |
|   id   |          |      profil_id     |           |   id    |
|        |          |      hobbies_id    |           |         |


-------------------------------------------------------------------------------------------------------------------

| projects |          | category-project (table de liaison) |              |  categories |
| -------- |     =>   | ----------------------------------- |              | ----------- |
|   id     |          |                 projects_id         |              |             |
|          |          |                 category_id         |      <=      |     id      |


