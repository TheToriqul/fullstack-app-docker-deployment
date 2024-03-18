# Full Stack Application Deployment With Docker

Welcome to the Full Stack Application Deployment With Docker project! 🚀

This project demonstrates the power of Docker and Docker Compose in deploying a full stack application seamlessly on AWS EC2. Whether you're a seasoned developer or just getting started with containerization, this project provides an excellent opportunity to dive into deploying complex applications with ease.

### Microservice Architecture Demo

<figure > 
<p align="center">
  <img src="./project-architecture.png" alt="project architecture" />
  <p align="center">Project Architecture</p> 
</p>
</figure>


## Project Overview

Building and deploying full stack applications can be a daunting task, especially when it comes to managing dependencies, environments, and scaling. With Docker, we simplify this process by encapsulating each component of our application into containers, ensuring consistency across development, testing, and production environments.

## Features

- **Client Service**: Frontend built with modern frameworks like React, Vue, or Angular.
- **API Services**: Backend services handling various aspects of the application logic.
- **Database Service**: Utilizing MySQL or another database management system to store and manage application data.
- **Worker Service**: Managing background tasks efficiently.
- **Redis**: Leveraging Redis for caching and message brokering.
- **Nginx**: Serving as a high-performance web server and reverse proxy for routing requests to the appropriate services.

## Why Docker?

- **Portability**: Docker containers can run on any platform, making deployment across different environments a breeze.
- **Isolation**: Each container encapsulates its dependencies, ensuring that applications run consistently regardless of the host environment.
- **Scalability**: Docker's lightweight nature enables effortless scaling of services horizontally or vertically as demand fluctuates.
- **DevOps Efficiency**: Docker streamlines the development-to-production workflow, empowering teams to ship code faster and with fewer errors.

## Getting Started

1. **Clone the Repository**:

```bash
git clone https://github.com/TheToriqul/Full-Stack-Application-Deployment-with-Docker.git
cd Full-Stack-Application-Deployment-with-Docker
```

2. **Set Environment Variables** (if needed):

If any environment variables are required, create a `.env` file in the root directory of the project and define the variables there.

3. **Build and Run the Docker Containers**:

```bash
docker-compose up --build
```

4. **Access the Application**:

Once the containers are up and running, access the application in your web browser using the public IP address of your AWS EC2 instance. Replace `localhost` with the public IP address.

## Contributing

I welcome contributions from the community! Whether you're interested in adding new features, fixing bugs, or improving documentation, your help is greatly appreciated. Please refer to our [Contribution Guidelines](CONTRIBUTING.md) for more information on how to get started.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.

## Have Questions or Feedback?

If you have any questions, feedback, or suggestions for improvement, please don't hesitate to [open an issue](https://github.com/TheToriqul/Full-Stack-Application-Deployment-with-Docker/issues). We'd love to hear from you and help in any way we can!

Let's Dockerize and deploy with confidence! 🐳
```

Make sure to update the instructions in the "Getting Started" section to reflect the usage of the public IP address of your AWS EC2 instance for accessing the application.