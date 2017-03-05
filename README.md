# Attendance

Simple attendance application for events repeating weekly.

## Installation

Download and install [Git](https://git-scm.com/) and [Meteor](https://www.meteor.com/).

    git clone https://github.com/Gimbou/Attendance.git
    cd Attendance

    (modify settings_dev.json before running the application)

    meteor npm install
    meteor --settings settings_dev.json

## Settings

- **Title**: Title of the event
- **Place**: Place of the event
- **Weekday**: Weekday of the event (1-7 starting from Monday)
- **Time**: Starting hours of the event
- **Lockdown**: Last change to sign up in minutes
- **Playercount**: How many players are needed for the event to happen
- **Password**: Login password