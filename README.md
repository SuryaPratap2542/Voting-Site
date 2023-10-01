# Django Voting Web Application

## Overview

This is a simple Django-based web application that allows users to vote on various categories. Users can view available categories, vote for their favorite items in each category, and see the voting results in real-time.

<img width="938" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/29ead5fe-f86e-458f-9c31-8e3ec80b3476">


## Features

- User-friendly interface for voting on categories.
- Real-time updates of voting results.
- Secure user authentication and authorization.
- SQLite database for data storage.
- Responsive design for mobile and desktop.

## Getting Started

### Prerequisites

- Python (3.6 or higher)
- Django (3.0 or higher)

### Installation

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/voting-app.git
   ```

2. Navigate to the project directory.

   ```bash
   cd voting-app
   ```

3. Create a virtual environment (optional but recommended).

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

4. Install project dependencies.

   ```bash
   pip install -r requirements.txt
   ```

5. Apply database migrations.

   ```bash
   python manage.py migrate
   ```

6. Create a superuser account to access the Django admin panel.

   ```bash
   python manage.py createsuperuser
   ```

7. Start the development server.

   ```bash
   python manage.py runserver
   ```

8. Open your web browser and access the application at `http://127.0.0.1:8000`.

## Usage

1. Browse the available categories on the homepage.
2. Click on a category to view its items and vote for your favorite.
3. Check real-time voting results on the results page.
4. Use the Django admin panel to manage categories and items.

## Screenshots

1. Signup Page:  New user Create a new Account.

   <img width="938" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/27745e63-5ef9-4353-a1cf-24f42e9c2fd5">

 
 2. Signin Page:  Existing user login here.

    <img width="933" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/f8282e17-86ef-4393-9bb4-7cb68214d9af">


3.  Category Page:  Browse categories and select one to vote.

   <img width="939" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/3cecb096-f7c2-45ad-a141-56a4cd7c990e">


4.  Vote Page:  Vote for your preferred category.

<img width="941" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/070f7aeb-1229-4788-beda-3d63bc9c5c8d">

<img width="941" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/32f92626-2746-4124-8a52-781539a3928c">


5.  Result Page: View the voting results.

   <img width="931" alt="image" src="https://github.com/SuryaPratap2542/Voting-Site/assets/89827931/bb04acf1-dcf7-49fd-bbb3-5c815a06453f">


## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Create a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Django community for their excellent documentation and resources.
