Calendar App
![calendar8](https://github.com/user-attachments/assets/e585a899-2724-4f34-ae36-a734d0d4890c)

This is a Calendar application I created mostly for personal use. It's designed to cater to my abnormal work shifts, as well as to track my Gym habits and weight.

Features:

1. Hevy API integration.
   - This allows users to sync their Hevy workout data with the calendar. Data such as exercise type, sets, reps, weight and volume are all imported.
2. Weight tracking.
   - User can input their weight each day. The app will track the user's weight over time with a graph.
4. Workout scheduling.
   - User can choose type of workout, and time.
   - User can indicate "rest" days.
6. Edit work shift data
   - User can choose between various preset work shift types, or create their own.
   - User can select Annual Leave and Non-work types.
7. Free time calculator
   - Free time is calculated as the time between work shifts (assuming 10 hour shift), minus 8 hours for sleep and 1 hour for work preperation.
8. Custom default cycle creator
   - Users can create a work cycle (x days long), and this can be used to automatically populate the entire calendar.
9. Save / Load calendar data
   - Calendar data is saved as .JSON file.
   - Calendar data can be loaded from .JSON file.
   - .JSON will capture all calendar data including imported Hevy workout data, and default cycle data.
10. Alerts
   - Users can create alerts for various events such as birthdays, public holidays, work ect.
   - Users can write custom text for the alerts.
11. Completed day / check
    - User can mark a day / workout as completed (green check)
12. Robust day / cell selection tools
    - The user can select one day at a time, or select multiple days by either dragging with the mouse, or holding CTRL + click.
13. Charts / Graphs
    - User can view a graph which tracks their weight change over time.
    - User can view graphs which track their weight progress for a given rep range.
    - User can view graphs which track their rep progress for a given weight.
