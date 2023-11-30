# Basic Django Authentication

Allow users easily authenticate and build authorization tokens into any existing Django web application. 

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description

A basic django authentication system is necessary for control and access within and outside your Django app. With the right setup, you can properly authenticate and authorize users before they can access resources within your application. Having an efficient auth system improves your app's security posture and allows only the right people to have access. Django provides an out of the box experience for authentication, and by leveraging on this, one wouldn't have to worry too much about managing Django web apps' security with third-party service(s).

## Features

Here are what makes the project tick! Please go through the features to see why this project is awesome!

- Simple Dashboard
    - This is the landing page for all authenticated users. However, users would be directed to the login page when they are not authenticated. 
    - You can add customizations to change the looks of the dashboard to suit your taste. 
- User Authentication
    - Guest users can simply create a user account by registering and loggging into the web app.
    - Existing users who've had their session expired would have to re-authenticate again by signing into the web app from the login page
    - Authenticated users can logout when they're done using the app. Logging out would automatically end all active sessions and convert the user into an anon or guest user. So which means, functionalities and services that depends on a user to be authenticated would no longer be available.
- Default Message Framework Integration
    - This only improves the user's experience by letting them know the outcome of the operations that they've completed within the applicaition.

## Installation

Setting up and installing this project is quite straightforward and easy. Below are detailed step on how to get this web app up and running. 

1. Install a virtual environment. 
```bash
pip intall virtualenv

```

2. Create and activate a virtual environment 
```bash
virtualenv generic_name

cd generic_name && Scripts\activate
```

3. Clone the project's github repo and cd into project
```bash
git clone https://github.com/chideegit/basic-django-authentication.git

cd basic-django-authentication
```

4. Install all the dependencies contained in the [requirements.txt](./requirements.txt) file. 
```bash
pip install -r requirements.txt
```

5. Make migrations, migrate and  then run local server 
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
## Usage
Navigating through the app is as easy as it look. You can follow through the steps below to have an idea of the experience before diving in yourself.

1. Navigate to http://127.0.0.1:8000/ 
2. If there's an existing account, then you would have to log in, if not, click on the 'Sign Up' link to create a new user account. 
3. After creating a new user account, you'd be required to log in. 
4. Once you're logged, then you're free to enjoy the simplistic UI architecture and think of customization ideas to the dashboard and also adding new features!

## Contributing
If you would like to contribute to the project, please follow the guidelines outlined in the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

## License
This project is licensed under the MIT License - see the [LICENSE file](./LICENSE) for details.

## Acknowledgments
Special thanks to the Django community for providing a robust framework.

Feel free to reach out for any questions, issues, or feature requests!

Happy coding🚀