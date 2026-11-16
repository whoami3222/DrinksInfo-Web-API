# DrinksInfo

DrinksInfo is a .NET console application for browsing cocktail categories and drinks. It retrieves data from [TheCocktailDB](https://www.thecocktaildb.com/) and displays the results in console tables.

## Requirements

- .NET 10 SDK
- Internet access to reach TheCocktailDB API

## Run

From the project directory:

```powershell
dotnet run
```

Or from the repository root:

```powershell
dotnet run --project .\DrinksInfo\DrinksInfo.csproj
```

## Usage

1. Choose a category from the displayed categories list (for example, `Shot`).
2. Choose a drink by entering its ID from the drinks list.
3. Enter `0` at the drink prompt to return to the categories.
4. After viewing a drink's details, press a key to return to the categories.

The application fetches categories, drinks in a category, and drink details directly from TheCocktailDB. No API key or local database is required.
