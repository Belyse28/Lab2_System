# Lab 2 – Bicycle Rental and Mushroom Identification System

## Project Overview

This project is a C# Windows Forms application developed as part of Lab 2 coursework. It combines two programs into one system: a Bicycle Rental Cost Calculator and a Mushroom Identification System.

Users can create an account, log in, and select which service they want to use through a dashboard.

## Features

### 1. User Authentication
- User registration (Sign Up).
- User login.
- Username and password validation.
- Password confirmation during registration.
- Duplicate username validation.
- Error and success messages using Windows Forms MessageBox.

### 2. Bicycle Rental System
Allows users to calculate bicycle rental costs based on starting and ending times.

**Hourly Rental Rates:**

| Time Period | Rate per Hour |
|---|---:|
| 00:00 – 07:00 | 500 RWF |
| 07:00 – 14:00 | 1,000 RWF |
| 14:00 – 19:00 | 1,500 RWF |
| 19:00 – 21:00 | 1,000 RWF |
| 21:00 – 24:00 | 500 RWF |

**Input Validations:**
- Starting time must be an integer between 0 and 23.
- Ending time must be an integer between 1 and 24.
- Ending time must be greater than starting time.
- Invalid inputs are rejected with appropriate error messages.

### 3. Mushroom Identification System

Identifies one of six mushroom types using a maximum of three questions.

**Mushroom Types:**
1. Agaric Jaunissant
2. Amanite Tue-Mouche
3. Cepe de Bordeaux
4. Coprin Chevelu
5. Girolle
6. Pied Bleu

**Identification Questions:**
- Does your mushroom grow in a forest?
- Does your mushroom have a convex cup?
- Does your mushroom have a ring?
- Does your mushroom have gills?

The program selects questions based on previous answers and validates that users enter Yes or No.

## Technologies Used

- C#
- .NET
- Visual Studio
- Git and GitHub




