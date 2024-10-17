# Manipal Hackathon 2024 README Template

**Team Name:** FINMINDS

**Problem Statement:** Investing in mutual funds can be a great way for young adults to start their investment journey, but understanding how to choose the right fund can be challenging. Create a mobile app that simplifies the process of selecting and investing in mutual funds by making it engaging and educational. The app should feature game mechanics that allow users to simulate investing in various mutual funds, manage a virtual portfolio, and participate in investment challenges. Integrate educational content such as tutorials, quizzes, and real-world scenarios to teach key investment concepts. Include features like leaderboards, achievements, and rewards to enhance engagement. Reference: https://www.amfiindia.com/investor-corner/knowledge-center/equity-funds.htmy

## 📜 Introduction
  
Our web app offers a comprehensive learning platform for individuals interested in mutual funds and stock markets. It combines educational content with practical tools to enhance the learning experience. Users can take notes directly within the app and download them instantly, ensuring seamless knowledge retention. A built-in reader, powered by JavaScript, provides text-to-speech functionality for more accessible learning. The mutual fund simulator offers in-depth fund information with performance graphs—created using Python—displayed at daily, weekly, monthly, and yearly intervals. Built with Next.js and React on the frontend and JavaScript on the backend, our platform ensures a smooth and engaging user experience for beginners and seasoned investors alike.

## ✨ Features

Website: 

1. **Educational Content**  
   - Learn about mutual funds and stock markets with well-structured resources.

2. **Notes-Making Section**  
   - Write notes while learning and download them instantly.

3. **Text-to-Speech Reader**  
   - Reads content aloud for improved accessibility.

4. **Mutual Fund Simulator**  
   - View detailed fund information.  
   - Analyze fund performance with graphs at daily, weekly, monthly, and yearly intervals.

5. **Performance Graphs**  
   - Generated using Python for accurate visualization.

6. **Technology Stack**  
   - **Frontend:** Built with Next.js and React.  
   - **Backend:** Powered by JavaScript, including the speech function.  

These features ensure an engaging, educational, and user-friendly experience for anyone looking to learn about and explore the world of investing.

## 🟢 Access

🌐 Website link: https://example.com

📱 App's APK file location: [`android/build/my-app.apk`](android/build/my-app.apk)

OR

📱 Play store link: https://play.google.com/store/apps/details?id=com.digilocker.android

## 📦 Instructions For Local Deployment With Docker (Optional)

To deploy the application locally using docker, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-team-repo/manipal-hackathon-2024.git
    cd manipal-hackathon-2024
    ```

1. Build the docker image

    ```bash
    sudo docker build -t hackathon .
    ```

1. Start a container using the built image and expose necessary ports

    ```bash
    sudo docker run -it --rm -p 3000:3000 hackathon
    ```

1. Access the application at http://localhost:3000

## ⚙️ Instructions For Local Deployment Without Docker

```
Python version: 3.10

Operating system: Ubuntu 22
```

Follow these steps to run the project locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-team-repo/manipal-hackathon-2024.git
    cd manipal-hackathon-2024
    ```

1. Install dependencies

    ```bash
    npm install
    ```

1. Start server

    ```bash
    npm run start
    ```

1. Access the application at http://localhost:3000
