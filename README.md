# E-commerce Back End 

## Description
* A database manager for an e-commerce platform to allow for searches by category, product name, or tag.

## Installation
* This application runs an SQL database, using Sequelize as an ORM and MySQL as the SQL dialect.
* Please install dependencies locally with the command
```bash
npm install
``` 
```bash
npm run seed
```


** Video Link (Screencastify)
![Link to Screencastify video]()

## Usage
* This application allows a database manager to access existing data entries by a number of different query methods. A user can look up categories, which themselves contain product(s), and to those products are attributed tags.
* Alternately, a user could look up a specific product, whose entry contains reference to its specific category and the tags with which it is associated.
* Finally, a user could search for products by tag (which we could interpret as 'keyword' or 'descriptor' and be presented with any products (and their associated categories) that pertain to that key.

## Support

### Roadmap

### Contributions

## Authors & Acknowledgment
* David F Mueth
* Thanks to Boot Camp cohort
* 
## License
* ISC

