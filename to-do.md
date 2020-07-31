Phase 1:
    - Front-End:
        - create `createAccount.html`
            - to include:
                - explanation of features
                    - how 'My Bar' works
                        - saves ingredients and updates them with each drink made
                        - uses ingredients to find craftable recipes
                    - how recipes are presented
                        - tinder-esque presentation
                        - search feature
                    - what is included in recipes
                        - recipes
                        - photos
                        - history/facts
                    - ask whether user would like recipes to be presented with liquid oz measurements or mL
        <!-- - create `index.html` -->
            <!-- - to include: -->
                <!-- - drop down menu
                    - recipe discovery
                    - favorites
                    - 'My Bar'
                    - search
                    - profile -->
                - get started button
        - create `choices.html`
            -to include:
                - dynamically updated list based on 'My Bar' ingredients and what exists in the recipe database
                - tinder-esque presentation
                - ability to scroll through list view rather than tinder-esque style presentation if desired (some tinder like features would work better on smaller devices)
                - ability to go to `recipe.html`, swipe left for disinterest in recipe, or swipe up to add to favorites
        - create `recipe.html`
            - to include:
                - dynamically updated DOM based on what recipe is selected
                - to include:
                    - recipe
                        - use whichever measurement system user chose
                        - ability to "batch make" drinks, changing their measurements
                            - warn user above 3 drinks that it may be better to mix two drinks at a time because of the size of the average shaker
                        - proper glassware
                    - photos
                    - history/facts
                    - button to add to favorites
        - create `favorites.html`
            - dynamically updated DOM based on what recipes are in favorites
            - present in a list view only
            - ability to remove recipes from favorites
        - create `profile.html`
            - ability to swap between metric and imperial measurements for recipes
        - create `myBar.html`
            - ability to add ingredients
                - liquor
                    - by volume
                        - airplane
                        - fifth
                        - handle
                    - by bottle estimate
                        - present user with image of bottle based on either fifth or handle, and a slider to estimate remaining liquor
                - bitters
                - fruits
                - juices/syrups
            - remainder of each ingredient is presented in a list view, broken up by the above categories
            - color-coded based on what remains
    - Back-end:
        - create database for recipes
            - present recipes as JSON objects with all necessary data for `choices.html` and `recipe.html`
            - start with tequila
        - create database for `myBar.html`
            - updates based on what drink the user makes
            

                        
        