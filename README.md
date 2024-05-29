# WorkoutPal Mobile App

Welcome to WorkoutPal, your go-to app for tracking and analyzing your workouts seamlessly. This app is designed to help you log, analyze, and review your workouts with ease. Below, you'll find the detailed description of the app's functionalities and how to use them.

## Functional Requirements

1. **User Authentication**
   - Secure login and sign-up functionality to access the WorkoutPal app.

2. **Workout Upload and Analysis**
   - Users can select videos from their local device.
   - Input workout intensity, body weight, and load weight.
   - Upload workout details to our API for analysis.

3. **Workout Summary**
   - View detailed workout summaries upon receiving API responses.

4. **Workout History**
   - Access past workouts and retrieve summaries for each workout.

## App Structure

The app is divided into three main tabs:

### Home Tab

The Home tab welcomes users and displays a weekly workout progress indicator, motivating users to complete more workouts.

![Home Tab UI](images/home_tab_ui.png)

### Upload Tab

The Upload tab is where users can:
- Select a video from their camera roll.
- Input workout intensity, load weight, and body weight.
- Submit the workout for analysis.

**UI Elements:**
- **Choose Video Button:** Prompts users to select a video from their camera roll.
- **Sliders:** Three sliders for intensity, body weight, and load weight.
- **Analyse Workout Button:** Sends the video and input data to the API for analysis. The process is asynchronous, allowing users to continue using the app while the video is being processed. A pop-up indicates that the workout is being analyzed, followed by an exercise summary once the response is received.

![Upload Tab and Exercise Summary UI](images/upload_tab_ui.png)

### Workout History Tab

The Workout History tab allows users to:
- View past workouts.
- Display exercise summaries when workouts are tapped. Data is pulled from our Firebase backend.

![Workout History and Exercise Summary UI](images/workout_history_ui.png)

## How to Use

1. **Login/Sign-Up:** Start by securely logging in or signing up.
2. **Home Tab:** Check your weekly progress and stay motivated.
3. **Upload Tab:** Select a workout video, input relevant data, and submit for analysis.
4. **Workout Summary:** View the summary once the API response is received.
5. **Workout History:** Review your past workouts and summaries.

## Installation

Clone the repository and open the project in Xcode:

```bash
git clone https://github.com/YourUsername/WorkoutPal.git
cd WorkoutPal
open WorkoutPal.xcodeproj
```

Ensure you have the necessary dependencies installed using CocoaPods:

1. Install CocoaPods if you haven't already:

```bash
sudo gem install cocoapods
```

2. Navigate to the project directory and install the dependencies:

```bash
cd WorkoutPal
pod install
```

3. Open the `.xcworkspace` file:

```bash
open WorkoutPal.xcworkspace
```

4. Build and run the app on your simulator or device from Xcode.

## Contact

For any questions or feedback, please contact us at [andycraig200@gmail.com](mailto:andycraig200@gmail.com).

---

Enjoy using WorkoutPal and stay fit!

---
