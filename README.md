# YGO META DATA
## Background
[YGOPRODECK](https://ygoprodeck.com/) consolidates a wide range of Yu-Gi-Oh! data from card information to card prices and tournament topping decklists.  Their [API](https://ygoprodeck.com/api-guide/) gives easy access to many of these resources, it currently does not provide tournament results for each card.  I had to deal with this issue when I had to manually collect tournament results for a Natural Language Processing [project](https://github.com/JoshuaMares/CS145_Proj) that attempted to classify YGO cards as meta based on their stats and effects.  Thus, I wanted a way to automate the process of tracking the tournament viability of cards for myself and any others that wanted access to this info.

## Goal
Create a database that connects each card to their last topping meta decklist.

## Stories
1. [ ] Scrape deck page for competitive lists
2. [ ] Scrape deck lists for card numbers
3. [ ] Collect into dataframe that contains card name, deck list link, and most recent top date
4. [ ] Host data on DB
5. [ ] Create server that with public api for grabbing data
6. [ ] Automatically update card data with new decklists as they are posted