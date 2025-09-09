# Zelda Recipes JSON

## About

This repository provides a complete, open-source JSON dataset of all 187 recipes from *The Legend of Zelda: Tears of the Kingdom*. This dataset was originally created for the Hyrule Cookbook project but is now maintained separately for public use.

## Usage

You can access the raw JSON data directly for use in your projects via the following URL:

`https://raw.githubusercontent.com/omercha/zelda-recipes-json/main/recipes.json`

## Data Structure

Each recipe object in the JSON array follows this structure:

```json
{
  "cookbook_id": 1,
  "name": "Mushroom Skewer",
  "ingredients": ["Any Mushroom"],
  "image": "https://www.zeldadungeon.net/wiki/images/1/1d/Mushroom_Skewer_-_TotK_icon.png",
  "description": "This simple mushroom-packed skewer has its colorful presentation to thank for its appeal."
}
```

-   **`cookbook_id`**: (Number) A unique identifier for the recipe based on the recipe's position in the game's cookbook.
-   **`name`**: (String) The name of the recipe.
-   **`ingredients`**: (Array of Strings) A list of ingredients required to make the recipe.
-   **`image`**: (String) A URL to an image of the recipe icon sourced from zeldadungeon.net.
-   **`description`**: (String) The description of the recipe provided by the game.

## Contributing

Contributions are welcome! If you find any errors or missing data, please feel free to open an issue or submit a pull request.

## License

This dataset is made available under the MIT License. See the `LICENSE` file for more details.
