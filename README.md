# Workout Generator

A personalized workout generator that creates custom exercise routines based on your current fitness capabilities.

## Features

- Input your current fitness level and exercise capabilities
- Generate customized workouts for different body parts
- Track workout history
- Modern, user-friendly interface
- Automatic workout scaling based on your capabilities

## Setup

1. Make sure you have Python 3.7+ installed on your system
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   python workout_app.py
   ```

## How to Use

1. **Profile Tab**
   - Select your fitness level (beginner/intermediate/advanced)
   - Enter your current maximum repetitions for various exercises
   - Click "Save Profile" to store your information

2. **Generate Workout Tab**
   - Choose the type of workout you want (Full Body/Upper Body/Lower Body/Core)
   - Click "Generate Workout" to create a personalized routine
   - The workout will be scaled based on your capabilities

3. **History Tab**
   - View your last 5 generated workouts
   - Track your workout history and progress

## Data Storage

Your profile and workout history are stored locally in `user_data.json`. 