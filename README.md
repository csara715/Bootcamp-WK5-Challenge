# Work Day Scheduler


## User Story

```md
AS A student and employee with an extremely busy schedule
I WANT to add events to a daily planner and easily view my busy schedule
SO THAT I can manage my time effectively and not miss any important appointments or deadlines for that day
```

## Acceptance Criteria

```md
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with hourly timeblocks for my standard working hours from 9AM to 9PM
WHEN I view the timeblocks for that day
THEN each hourly timeblock is color coded to indicate whether it is in the past (grey), the present (red), or the future (green)
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
WHEN I close the browser and reopen the browser
THEN the saved events persist
```

The following animation demonstrates the application functionality:

![A user clicks on slots on the color-coded calendar and edits the events.](./assets/05-third-party-apis-homework-demo.gif)

- https://csara715.github.io/Bootcamp-WK5-Challenge/



