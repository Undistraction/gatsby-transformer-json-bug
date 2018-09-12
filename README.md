# README

# Steps to reproduce

1. `npm i`
2. `gatsby develop`
3. Navigate to `http://localhost:8000/___graphql?query=%7B%0A%20%20settingsJson%20%7B%0A%20%20%20%09alpha1%0A%20%20%20%20bravo1%0A%20%20%20%20charlie1%0A%20%20%7D%20%0A%20%20%20%0A%7D%0A`

# Expected

All settings have defined values.

# Result

Only one setting has a defined value. The others are null.

Note that the json files can be found in `./src/content/settings`.
