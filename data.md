# Présentation des données

Pour ce TP, nous utiliserons les données **movies** qui contiennent des informations sur des films de différentes époques et genres.

| Colonne          | Type   | Description                                       | Exemple                                                   |
|------------------|--------|---------------------------------------------------|-----------------------------------------------------------|
| title            | string | Titre du film                                     | Intolerance: Love's Struggle Throughout the Ages           |
| year             | int    | Année de sortie du film                           | 1916                                                      |
| genres           | list   | Liste des genres du film                          | ["Drama", "History"]                                       |
| cast             | list   | Liste des acteurs principaux                      | ["Lillian Gish", "Spottiswoode Aitken", "Mary Alden"]      |
| directors        | list   | Liste des réalisateurs du film                    | ["D.W. Griffith"]                                          |
| writers          | list   | Liste des scénaristes du film                     | ["D.W. Griffith", "Anita Loos"]                            |
| countries        | list   | Liste des pays de production                      | ["USA"]                                                    |
| languages        | list   | Langues du film                                   | ["English"]                                                |
| plot             | string | Résumé court du film                              | The story of a poor young woman, separated by prejudice... |
| fullplot         | string | Résumé détaillé du film                           | Intolerance and its terrible effects are examined in...    |
| imdb.rating      | float  | Note IMDb du film                                 | 8.0                                                       |
| imdb.votes       | int    | Nombre de votes IMDb                              | 9880                                                      |
| tomatoes.viewer.rating | float | Note des spectateurs Rotten Tomatoes               | 3.8                                                       |
| tomatoes.viewer.numReviews | int | Nombre de critiques des spectateurs sur Rotten Tomatoes | 4718                                                      |
| tomatoes.viewer.metter | int | Notes des critiques sur Rotten Tomatoes | 77                                                      |
| awards           | object | Prix du film                        | {"wins": 1, "nominations": 0, "text": "1 win."}            |
| type             | string | Type du contenu (film, série, etc.)               | movie                                                     |

Voici un exemple de données :

```json
{
  "_id": {
    "$oid": "573a13e9f29313caabdcd99c"
  },
  "plot": "An imaginative children's film about a young Australian boy's passion for flight and his challenge to compete in the World Paper Plane Championships in Japan.",
  "genres": [
    "Family"
  ],
  "cast": [
    "Ed Oxenbould",
    "Sam Worthington",
    "Julian Dennison",
    "Peter Rowsthorn"
  ],
  "num_mflix_comments": 2,
  "title": "Paper Planes",
  "fullplot": "An imaginative children's film about a young Australian boy's passion for flight and his challenge to compete in the World Paper Plane Championships in Japan.",
  "languages": [
    "English"
  ],
  "released": {
    "$date": "2015-01-15T00:00:00Z"
  },
  "directors": [
    "Robert Connolly"
  ],
  "writers": [
    "Robert Connolly",
    "Steve Worland"
  ],
  "awards": {
    "wins": 1,
    "nominations": 4,
    "text": "1 win & 4 nominations."
  },
  "lastupdated": "2015-08-29 00:01:59.890000000",
  "year": 2014,
  "imdb": {
    "rating": 6.2,
    "votes": 1635,
    "id": 3328716
  },
  "countries": [
    "Australia"
  ],
  "type": "movie"
},{
  "_id": {
    "$oid": "573a13e9f29313caabdcdad7"
  },
  "plot": "An asphalt contractor, who has sacrificed his life to make a profit, finds himself in a financial dead-end. The ever gentle-minded road engineer Rauno Kannisto is hired to the construction ...",
  "genres": [
    "Comedy"
  ],
  "countries": [
    "Finland"
  ],
  "cast": [
    "Jussi Vatanen",
    "Seppo Halttunen",
    "Martti Suosalo",
    "Milka Ahlroth"
  ],
  "title": "Middle of the Road",
  "fullplot": "An asphalt contractor, who has sacrificed his life to make a profit, finds himself in a financial dead-end. The ever gentle-minded road engineer Rauno Kannisto is hired to the construction site, to build a road that cuts through the vast forests by the Russian border. He knows nothing of the financial difficulties. Soon, Rauno finds himself in a situation where he doesn't know which way to turn. The sub-contractor becomes the main contractor, workers are loaded in containers from the other side of the border, and the contractor's wife has a smile that makes you lose your sleep. Middle of the Road is a dark comedy about loyalty and greed.",
  "languages": [
    "Finnish"
  ],
  "released": {
    "$date": "2013-11-17T00:00:00Z"
  },
  "directors": [
    "Matti Ijès"
  ],
  "writers": [
    "Matti Ijès (script)",
    "Heikki Reivilè (script)"
  ],
  "awards": {
    "wins": 1,
    "nominations": 0,
    "text": "1 win."
  },
  "lastupdated": "2015-08-02 00:12:20.870000000",
  "year": 2013,
  "imdb": {
    "rating": 4.5,
    "votes": 62,
    "id": 3331044
  },
  "type": "movie"
}
```