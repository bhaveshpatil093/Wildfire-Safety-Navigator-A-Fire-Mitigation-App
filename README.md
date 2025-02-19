# 🔥 Wildfire Safety Navigator: A Fire Mitigation App

## 📋 Table of Contents

- [About the Project](#about-the-project)
  - [Features](#features)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## 🔍 About the Project

Wildfire Safety Navigator is a mobile application designed to assist communities in mitigating the risks associated with wildfires. By providing real-time data, safety guidelines, and emergency response features, the app aims to enhance preparedness and response to wildfire incidents.

### ✨ Features

- **Real-Time Alerts**: Receive notifications about nearby wildfires and evacuation orders.
- **Safety Guidelines**: Access up-to-date information on best practices before, during, and after a wildfire.
- **Emergency Contacts**: Quickly connect with local emergency services and shelters.
- **Interactive Map**: View active fire locations, risk zones, and safe evacuation routes.

### 🛠️ Built With

- **Frontend**: React Native
- **Backend**: Node.js with Express
- **Database**: MongoDB
- **APIs**: Integration with NASA's Fire Information for Resource Management System (FIRMS)

## 🚀 Getting Started

To set up the project locally, follow these steps.

### 📋 Prerequisites

- **Node.js**: Please make sure you have Node.js installed. You can download it [here](https://nodejs.org/).
- **MongoDB**: Set up a MongoDB database. You can use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for a cloud solution.
- **React Native Environment**: Follow the official [React Native setup guide](https://reactnative.dev/docs/environment-setup) to configure your development environment.

### 🛠️ Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/bhaveshpatil093/Wildfire-Safety-Navigator-A-Fire-Mitigation-App.git
   cd Wildfire-Safety-Navigator-A-Fire-Mitigation-App

2. **Install Backend Dependencies**:

   ```bash
   cd backend
   npm install

3. **Configure Environment Variables**:
- Create a `.env` file in the `backend` directory with the following content:

   ```bash
   MONGODB_URI=your_mongodb_connection_string
   FIRMS_API_KEY=your_nasa_firms_api_key

4. **Start the Backend Server**:

   ```bash
   npm start

5. **Install Frontend Dependencies**:

   ```bash
   cd ../frontend
   npm install

6. **Start the React Native App**:
- For iOS:
   ```bash
   npx react-native run-ios

- For Android:
   ```bash
   npx react-native run-android

## 📱 Usage
Once the application is running, users can:
- **View Active Wildfires**: Access the interactive map to see current wildfire locations and statuses.
- **Receive Alerts**: Get notified about new fires or changes in existing ones based on your location.
- **Access Resources**: Find information on evacuation plans, safety measures, and contact details for emergency services.

## 🤝 Contributing
Contributions are welcome! To contribute:

1. **Fork the Repository**: Click the "Fork" button at the top right of the repository page.

2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/YourFeatureName

3. **Commit Your Changes**:
   ```bash
   git commit -m 'Add some feature'

4. **Push to the Branch**:
   ```bash
   git push origin feature/YourFeatureName

5. **Open a Pull Request**: Navigate to the repository on GitHub and click the "New Pull Request" button.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

## 📬 Contact
- **Name**: Bhavesh Patil
- **Email**: bhaveshpatiltech@gmail.com
- **LinkedIn**: linkedin.com/in/bhaveshpatil094

## 🙏 Acknowledgments
- **Data Providers**: Thanks to NASA's FIRMS for wildfire data.
- **Icons and Graphics**: FontAwesome for icons.
- **Contributors**: Special thanks to all contributors and testers.
