# Portfolio

Welcome to my portfolio repository! This repository contains the source code and configuration files for my personal portfolio website. The portfolio is hosted on AWS, utilizing services such as Amplify, API Gateway, Lambda, and DynamoDB.

## Deployment

The deployment of this portfolio is automated using AWS Amplify. Whenever changes are pushed to the `main` branch of this repository, Amplify automatically triggers a build and deploys the latest version of the portfolio.

To deploy the portfolio to your own AWS account, follow these steps:

1. Clone this repository: `git clone https://github.com/aryansaxena094/Portfolio.git`
2. Navigate to the repository: `cd Portfolio`
3. Make sure you have the AWS CLI installed and configured with your AWS credentials.
4. Create an Amplify app in the AWS Management Console.
5. Connect the Amplify app to this repository by selecting "GitHub" as the repository service and following the prompts.
6. Configure the build settings in the Amplify app according to your preferences.
7. Trigger an initial deployment by pushing a change to the `main` branch of this repository.

Amplify will automatically set up the necessary resources, including the API Gateway, Lambda functions, and DynamoDB tables, based on the configuration files in this repository.

## Project Structure

Here's an overview of the project structure:

- `amplify`: Contains the AWS Amplify configuration files, including the `backend` folder that defines the AWS resources for the portfolio.
- `src`: Contains the source code for the portfolio website.
- `public`: Contains static assets, such as images and CSS files.
- `README.md`: This file.

## Technologies Used

- **AWS Amplify**: Amplify is used for continuous deployment, hosting, and managing the backend resources of the portfolio.
- **API Gateway**: API Gateway enables the creation, deployment, and management of a RESTful API that serves as the backend for the portfolio.
- **AWS Lambda**: Lambda functions handle the backend logic and serve as the serverless compute for the API Gateway endpoints.
- **DynamoDB**: DynamoDB is used as the NoSQL database to store portfolio data.
- **React**: The portfolio website is built using React, a popular JavaScript framework for building user interfaces.

## Contributing

I welcome contributions to this portfolio project! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. I will review and respond to them as soon as possible.

Happy coding!