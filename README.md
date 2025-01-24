# Calendar App with Hevy API Integration

![image6](https://github.com/user-attachments/assets/0049d1fb-3a8e-4f5f-b74f-75ccf688542f)
![image](https://github.com/user-attachments/assets/2c7ac02d-104f-4c8f-a213-9b81365f7716)
![ui2](https://github.com/user-attachments/assets/44b37bdc-5b48-4258-9b7c-27c86b66a16f)
![ui3](https://github.com/user-attachments/assets/82e943ee-54f9-4c19-ae38-eb58a1acd97d)
![image](https://github.com/user-attachments/assets/e4bd00ed-ae97-4954-9ea0-48393c5cb101)
![image](https://github.com/user-attachments/assets/43a7d14b-b810-4811-b71d-78a1d199089b)


This is a Calendar application I created mostly for personal use. It's designed to cater to my abnormal work shifts, as well as to track my workouts and weight.

## Features

1. **Hevy API Integration: [Hevy](https://www.hevyapp.com/)**
   - Sync your Hevy workout data with the calendar. Data such as exercise type, sets, reps, weight, and volume are all imported.
   - Middle click with mouse while hovering over day cell to open menu. Alternatively, press "H" key while the cell is selected.

2. **Weight Tracking**
   - Input your weight each day. The app tracks your weight over time with a graph.

3. **Workout Scheduling**
   - Choose the type of workout and time.
   - Indicate "rest" days.

4. **Edit Work Shift Data**
   - Choose between various preset work shift types or create your own.
   - Select Annual Leave and Non-work types.

5. **Free Time Calculator**
   - Calculates free time as the time between work shifts (assuming a 10-hour shift), minus 8 hours for sleep and 1 hour for work preparation.

6. **Custom Default Cycle Creator**
   - Create a work cycle (x days long) to automatically populate the entire calendar.

7. **Save / Load Calendar Data**
   - Save calendar data as a `.JSON` file.
   - Load calendar data from a `.JSON` file.
   - `.JSON` files capture all calendar data, including imported Hevy workout data and default cycle data.

8. **Alerts**
   - Create alerts for various events such as birthdays, public holidays, work, etc.
   - Write custom text for the alerts.

9. **Completed Day / Check**
   - Mark a day/workout as completed with a green check.

10. **Robust Day / Cell Selection Tools**
    - Select one day at a time or multiple days by dragging with the mouse or holding `CTRL` + click.

11. **Charts / Graphs**
    - Graph tracking your weight change over time.
    - Graphs tracking your weight progress for a given rep range.
    - Graphs tracking your rep progress for a given weight.
    - Graphs tracking exercise volume and overall workout volume.
    - Graphs tracking estimated One Rep Max (ORM).
