# Bands

> this API consists in creating a band which is associated with the members and different categoris. I used sterializer to associate the id of a member to a band. 

![Screenshot](https://github.com/vic778/band/blob/master/screen/screen1.png)

This API is made of three models:
- Band model
- Member model


The API has the following endpoints:


returns all the bands

`GET /bands`

allows admin to create a band

`POST /bands/new`

returns a specific item

`GET /bands/id`

allows admin to edit a band

`PUT /bands/id`

allows admin to delete an item

`DELETE /instruments/id`

## Built With

- Rails
- Ruby 
- Heroku

## Getting Started

Here are the steps to follow in order to get this project on your local computer.

### Prerequisites

`rails v7.0.2 +`

`ruby v3.0.2 +`

### Setup

clone this repo by typing `git clone https://github.com/vic778/band`

### Install

install the dependencies by typing `bundle install`

### Usage

start the local server by running `rails s`

### Testing

run the tests by typing `bundle exec rspec`

### Deployment

N/A

## Author

👤 **Victor Barh**

- GitHub: [@Vvic778](https://github.com/vic778)
- Twitter: [@victoirBarh](https://twitter.com/)
- LinkedIn: [LinkedIn](https://linkedin.com/in/victoir-barh)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used !

## 📝 License

This project is [MIT](lic.url) licensed.
