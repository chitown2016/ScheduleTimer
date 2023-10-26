# ScheduleTimer

The code is originally written by Andy Brummer. It allows to schedule a function call which is not trivial in C#. For example,
using this library you can shedule a function call like this:

ScheduleTimer TickTimer = new ScheduleTimer(); \
TickTimer.AddJob(new Schedule.ScheduledTime("Daily", "1:04 PM"), new Action(() => YourFunction(yourInput)));



