# Similar_Listings_Recommendations
This is a monolithic application for a recommendation component.

## Motivation

This project was developed to gain a fundemental understanding of service-oriented architecture.

### Prerequisites

At least 5 Amazon EC2 instances with static ip addresses is preferred for the deployment of this service. 
1 for the load balancer, 1 for the database server, and 3 or more for microservice instances.

### Installing


## Running the tests

## Screenshots

Include logo/demo screenshot etc.

## Deployment

### AWS

To start web service

  1. To install dependencies, run 
  
  
  2. To establish port forwarding, run
  ```
  sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 3011
  ```

  3. In Similar-Listings-Recommendations directory, run
  ```
  npm run dev
  ```

To start database


## Built with

#### Tech/frameworks used

* React
* NodeJs/Express
* PostgreSQL

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
