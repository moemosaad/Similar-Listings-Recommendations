# Similar_Listings_Recommendations
This is a microservice for a similar listings component.

## Motivation

This project was developed to gain a fundamental understanding of service-oriented architecture.

### Installing

To install dependencies, run 

  ```
  npm install
  ```
  
## Running the tests

In Similar-Listings-Recommendations directory, run 

  ```
  node run test
  ```

## Deployment

### AWS

To start web service

  1. To establish port forwarding, run
  ```
  sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 3011
  ```

  2. In Similar-Listings-Recommendations directory, run
  ```
  npm run dev
  ```

## Built with

#### Tech/frameworks used

* React
* NodeJs/Express
* MongoDB

#### Features

* AWS EC2 (Optional)
* AWS S3 (Optional)

#### Testing

* Jest
* Puppeteer

## Authors

Moe Mosaad

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Jared Elison
* Sujin Lee
* Austin Joo

MIT © Moe Mosaad
