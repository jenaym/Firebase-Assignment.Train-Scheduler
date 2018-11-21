# Firebase-Assignment.Train-Scheduler

## App Overview
- A train schedule application that incorporates Firebase to host arrival and departure data
- The app will retrieve and manipulate this information with Moment.js
- This website will provide up-to-date information about various trains, namely their arrival times and how many minutes remain until they arrive at their station

## App Specs
- When adding trains, administrators are able to submit the following:
    - Train Name
    - Destination
    - First Train Time -- in military time
    - Frequency -- in minutes
- App calculates when the next train will arrive relative to the current time
- Users from many different machines are able to view the same train times
