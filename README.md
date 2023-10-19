# SocialNet-ImageShare: A Social Networking App

A sample social networking application built with Node.js and MongoDB, designed primarily for uploading and sharing images.

## Features

- User Registration & Login
- Upload Images
- Share Images with other Users
- Comment on Shared Images
- Profile Customization

## Technologies

- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Frontend**: HTML, CSS, and JavaScript

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (version 14 or higher recommended)
- [MongoDB](https://www.mongodb.com/try/download/community)

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/SocialNet-ImageShare.git
```

2. Navigate to the project directory:
```
cd SocialNet-ImageShare
```

3. Install the required npm packages:
```
npm install
```

4. Start the MongoDB server (based on your OS and configuration).

5. Create a `.env` file in the root of your project and add the following:
```
DB_URI=mongodb://localhost:27017/socialnet-imageshare  <!-- Replace with your MongoDB URI if different -->
SECRET=your_secret_key_for_jwt   <!-- Replace with your secret key -->
```

6. Run the application:
```
npm start
```

7. Visit `http://localhost:3000` in your browser to access the app.

## Usage

1. **Register/Log In**: Start by registering an account or logging in if you already have one.
2. **Profile Page**: Navigate to your profile page to upload and manage your images.
3. **Feed**: View shared images from other users and interact with them.
4. **Share & Comment**: Share your images or comment on shared images.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change. Please ensure to update tests as appropriate.

## License

[MIT License](./LICENSE)  <!-- Replace with a link to your LICENSE file if you have one -->

## Contact

For any queries, feel free to contact:
- Email: az00721@gmail.com
