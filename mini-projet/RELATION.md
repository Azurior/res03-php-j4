|  pages  |         | media (table de liaison) |        |  projects  |
| ------- |     =>  | ------------------------ |        | ---------- |
|   id    |         |       pages_id           |        |            |
|         |         |       projects_id        |   <=   |   id       |

| profil |    =>    | media |
| ------ |          | ----- |


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


