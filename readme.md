# Express template

## **Getting started**

To get started with this project, follow the steps below:

**Prerequisites**

- Ensure you have Node.js installed. You can download it from [Node.js official website](https://nodejs.org/).
- Install Git from [Git official website](https://git-scm.com/).
- Typescript installed globally. You can install it by running `npm install -g typescript`.

**Steps**

1. **Clone the repository**

    ```bash
    git clone git@github.com:suman7802/ExpressTemplate.git
    ```

2. **Navigate to the project directory**

    ```bash
    cd ExpressTemplate
    ```

3. **Install dependencies**

    ```bash
    npm install
    ```

4. **Create .env.local file**

    Create a `.env.local` file in the root of the project and add the environment variables, using env.example file.

5. **Run the development server**

    ```bash
    npm run dev
    ```

6. **Open the project in your browser**

    Open your browser and go to `http://localhost:8080` to see the project running.

By following these steps, you will have the project up and running on your local machine.

For createing build files run `npm run build` and for running build files run `npm start`.

# **Documentation**

> [Postman Collection](https://documenter.getpostman.com/view/27265804/2sAYkBsM99)

# **Docker compose**

### The project is equipped with a docker-compose file for easy deployment and monitoring with Grafana and Prometheus.

> To run the project using Docker, follow these steps:

```bash
docker-compose up
```

# **Features**

- Custom error class
- Custom error handler
- Logging
- Localization
- Rate limiting
- Slow down
- Multer
- API key emplemantation
- Sending Emails (sendgrid)
- Metrics (Analytics)
- Prometheus (containerized)
- Grafana (containerized)

# Features to be added

- Testing
- Conterization
- Authentication (passport.js)
- Authorization
- Grafana Loki

## Contributing

Contributors are welcome! If you'd like to enhance the project further or add new features, please follow these steps:

1. Fork the repository.
2. Clone your forked repository:
    ```bash
     git clone git@github.com:suman7802/ExpressTemplate.git
    ```
3. Create a new branch:
    ```bash
    git checkout -b feature/new-feature
    ```
4. Make your changes and commit them:
    ```bash
    git commit -m "Add new feature"
    ```
5. Push your changes:
    ```bash
    git push origin feature/new-feature
    ```
6. Open a Pull Request on GitHub.

- If you encounter a bug or want to see something added/changed, please go ahead and [Open an issue](https://github.com/suman7802/ExpressTemplate/issues/new/choose)

- If you need help with something, feel free to [Start a discussion](https://github.com/suman7802/ExpressTemplate/discussions/new/choose)

## Contact

For any questions or suggestions, feel free to reach out:

- **Email:** [mansu7802@gmail.com](mailto:mansu7802@gmail.com)
- **Website:** [suman sharma](https://sumansharma.me)
- **LinkedIn:** [suman sharma](https://www.linkedin.com/in/suman7802)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
