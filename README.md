## About

This repository provides a complete, open-source JSON dataset of all 228 recipes from *The Legend of Zelda: Tears of the Kingdom*. This dataset was originally created for the Hyrule Cookbook project but is now maintained separately for public use.

## Usage

You can access the raw JSON data directly for use in your projects via the following URL:

`https://raw.githubusercontent.com/omercha/zelda-recipes-json/main/recipes.json`

## Data Structure

Each recipe object in the JSON array follows this structure:

```json
{
  "id": 1,
  "name": "Mushroom Skewer",
  "ingredients": [
    "Any Mushroom"
  ],
  "image": "https://www.zeldadungeon.net/wiki/images/1/1d/Mushroom_Skewer_-_TotK_icon.png",
  "method": "pot"
}
```

-   **`id`**: (Number) The position of the recipe in the game's cookbook.
-   **`name`**: (String) The name of the recipe.
-   **`ingredients`**: (Array of Strings) A list of ingredients required to make the recipe.
-   **`image`**: (String) A URL to an image of the recipe icon from zeldadungeon.net.
-   **`method`**: (String) How the recipe is cooked. Values: "pot", "extreme_heat", "extreme_cold" or "hot_spring".

## Contributing

Contributions are welcome! If you find any errors or missing data, please feel free to open an issue or submit a pull request.

## License

This dataset is made available under the MIT License. See the `LICENSE` file for more details.
