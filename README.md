# Gym & Padel Management System

A desktop management application developed in **C++** using **Qt Widgets** to streamline the management of gym and padel club operations. The system provides functionality for managing members, staff, coaches, workout sessions, padel court bookings, subscriptions, and administrative activities through an intuitive graphical user interface.

## Features

### Member Management

* Register new members
* Update member information
* Search and view member records
* Manage membership details

### Gym Management

* Manage gym classes and training sessions
* Track workouts and exercise plans
* Store workout history
* Assign coaches to members and classes

### Padel Court Management

* Manage padel courts
* Create and track court bookings
* Schedule reservations
* Monitor court availability

### Subscription Management

* Create and renew subscriptions
* Track membership payments
* Monitor subscription status and validity

### Staff Administration

* Manage staff records
* Manage coaches and receptionists
* Perform administrative operations

## Technologies Used

* C++
* Qt 6 (Qt Widgets)
* Qt Creator
* MinGW 64-bit Compiler
* Object-Oriented Programming (OOP)

## Project Structure

```text
├── Booking.cpp / Booking.h
├── Coach.cpp / Coach.h
├── GymClass.cpp / GymClass.h
├── Manager.cpp / Manager.h
├── Member.cpp / Member.h
├── PadelCourt.cpp / PadelCourt.h
├── PadelSystem.cpp / PadelSystem.h
├── Receptionist.cpp / Receptionist.h
├── Staff.cpp / Staff.h
├── SubscriptionManagement.cpp / SubscriptionManagement.h
├── Workout.cpp / Workout.h
├── WorkoutHistory.cpp / WorkoutHistory.h
├── main.cpp
├── mainwindow.cpp
├── mainwindow.h
└── test4.pro
```

## Requirements

Before running the application, make sure the following software is installed:

* Qt Creator
* Qt 6.x Desktop Kit
* MinGW 64-bit Compiler

## Installation & Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/zziad11/gym-padel-management-system.git
cd gym-padel-management-system
```

### 2. Open the Project

1. Launch **Qt Creator**
2. Select **File → Open File or Project**
3. Open the project file:

```text
test4.pro
```

### 3. Configure the Project

* Select a compatible Qt Desktop Kit (Qt 6 + MinGW 64-bit)
* Allow Qt Creator to configure the build settings

### 4. Build the Application

In Qt Creator:

```text
Build → Build Project
```

or press:

```text
Ctrl + B
```

### 5. Run the Application

In Qt Creator:

```text
Build → Run
```

or press:

```text
Ctrl + R
```

The application should compile and launch successfully.

## Building from the Command Line

If Qt is added to your system PATH, you can also build the project manually:

```bash
qmake test4.pro
mingw32-make
```

Run the executable:

```bash
./debug/test4.exe
```

or

```bash
./release/test4.exe
```

depending on the build configuration.



## Learning Outcomes

This project demonstrates:

* Object-Oriented Design in C++
* Desktop Application Development with Qt
* GUI Design and Event-Driven Programming
* Class Modeling and System Architecture
* Data Structures




**[Ziad Mohamed]**

