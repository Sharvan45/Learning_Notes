GraphQL Notes:

Offical Site : https://graphql.org/

GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.
  
Demo Site : https://countries.trevorblades.com/  

Demo Query :

query -> keyword

query getAlbum {
  countries(filter: { code:  { eq: "IN" } }) {
    capital
    code
    emoji
    emojiU
    continent {
      name
      code
    }
  }
}
