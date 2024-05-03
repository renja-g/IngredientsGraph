# IngredientsGraph
Visualizations of Ingredients and recipes

![image](https://github.com/renja-g/IngredientsGraph/assets/76645494/394223f9-b3e1-458d-9c24-08e0d92d4a0a)


```mermaid
erDiagram
    USER ||--o{ RECIPE : has
    RECIPE ||--|{ INGREDIENT : has

    USER {
        string userId
        string username
        string email
        string encryptedPassword
    }
    RECIPE {
        string title
        string description
        string steps
        string recipe_ingredient_id
    }
    INGREDIENT {
        string name
        string unit
        string recipe_ingredient_id
    }
```
