# Website Scraper with MongoDB
This is a web scraping app built with MongoDB, Mongoose and Cheerio. 

The application functionality includes:
1. Display data from another website,
2. Allow users to create notes for each line of data,
3. Save the data to a NoSQL database.


![scrape](https://github.com/markcam1/markcam1.github.io/blob/master/assets/images/scrapper.png)

---

## Setup
### Installing

**Clone this repository to your local system**

 Use Git or checkout with SVN using the web URL.[Clone](https://github.com/markcam1/Scrape_Mongo.git)

```
npm install
```


### Usage
1. go to the server.js file (line 47) and the GET function with the website that you want to scrape

```
// First, we grab the body of the html with request
  axios.get("https://www.nytimes.com").then(function(response)
```

2. then save and run the server.js file.

```
node server.js
```

3. go to the http://localhost:3000/ and use the page


## Built With <a name="tools"></a>
* [Mongoose](https://www.npmjs.com/package/mongoose) - Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.
* [Node.js](https://nodejs.org/en/) - a JavaScript runtime built on Chrome's V8 JavaScript engine.
* [MongoDB](https://www.mongodb.com/download-center/community) - MongoDB is a free and open-source cross-platform document-oriented database program. 
* [cheerio]https://www.npmjs.com/package/cheerio) - Fast, flexible & lean implementation of core jQuery designed specifically for the server.


## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to me.

## Versioning
Use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/markcam1/node_word_guess/tags). 

## Authors
* **Mark Cameron** - *Initial work* - [Mark Cameron](https://markcam1.github.io/)

See also the list of [contributors](https://github.com/calendarapp1bootcamp/node_word_guess/graphs/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* UC Berkeley Extension
* Teachers [David Blanchard](https://www.linkedin.com/in/dblanchard13/), [Rai Lee](https://www.linkedin.com/in/rai-lee-38061696/), [Emma Brown](https://github.com/EmmaEm),