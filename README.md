# SOULFAM RACE

**SOULFAM RACE** is an Android application for workouts and races on Bluetooth Low Energy fitness equipment that supports the FTMS (Fitness Machine Service) standard.

The application is developed by **Anatoliy Moskalenko**.

## Features

### Bluetooth FTMS equipment

SOULFAM RACE can discover, save, connect to, and receive workout data from compatible:

- rowing machines;
- indoor bikes;
- treadmills;
- elliptical trainers;
- steppers.

Not every Bluetooth fitness machine supports FTMS correctly. Available metrics and control functions depend on the equipment manufacturer and model.

### Personal workouts

The application displays real-time workout information received from connected equipment. Depending on equipment capabilities, metrics may include:

- elapsed time;
- distance;
- speed;
- pace;
- cadence;
- power;
- resistance or incline;
- stroke count;
- calories;
- heart rate.

Users can configure the workout display and set a distance goal.

### Workout programs

Users can create and run custom interval workout programs. Supported targets depend on the connected equipment and may include speed, pace, power, resistance, incline, cadence, distance, and time.

### Local races

SOULFAM RACE supports local races with multiple connected fitness machines, virtual opponents, relay races, and team-average races.

### Online races

Authenticated users can:

- create and join online races;
- choose public, country, favorites, or invitation-based visibility;
- indicate readiness before the start;
- synchronize live race progress;
- view participants and race results;
- participate in individual and team races.

An online racing profile contains a display name, country, and public Online ID. Participant lists and race results may be visible to other authenticated SOULFAM RACE users, including users who did not participate in the race.

Online race records are intended to be temporary. The application attempts to remove finished and canceled races after approximately 24 hours. Actual deletion may occur later because cleanup can depend on application or service activity.

## Requirements

- Android 7.0 or later;
- a device with Bluetooth Low Energy support;
- Bluetooth permissions;
- location permission for Bluetooth scanning on Android 11 and earlier;
- internet access for online races and Firebase services;
- compatible FTMS equipment for live workout data.

## Online services

The application uses Google Firebase services for:

- anonymous authentication;
- online profiles and race storage;
- real-time race synchronization;
- remote feature configuration;
- application analytics.

Firebase services do not require the user to provide an email address, phone number, password, or Google account for online racing.

## Privacy

SOULFAM RACE does not sell personal data and does not use personal data for targeted advertising.

Read the complete [Privacy Policy](privacy-policy.md) for details about Bluetooth data, workout metrics, online profiles, Firebase services, retention, and deletion requests.

## Data deletion

To request deletion of an online profile and associated online data, email:

**[a.an.moskalenko+soulfamrace@gmail.com](mailto:a.an.moskalenko+soulfamrace@gmail.com?subject=SOULFAM%20RACE%20data%20deletion%20request)**

Include the public Online ID or application ID displayed in the application. Do not send passwords, payment information, or identity documents.

## Support

For support and questions:

**[a.an.moskalenko+soulfamrace@gmail.com](mailto:a.an.moskalenko+soulfamrace@gmail.com?subject=SOULFAM%20RACE%20support)**
