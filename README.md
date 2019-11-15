# GoogleCalendarTerminal

Simple Google Calendar terminal client to list your next 10 events and insert an event

## Use

### To list next 10 events

```
go run calendar.go
```
### To insert an event
```
go run calendar.go insert <title> <description> <Begining datetime YYYY-MM-DDTHH:MM:SS> <End datetime YYYY-MM-DDTHH:MM:SS>
```
Example:
```
go run calendar.go insert Study 'I need to study programming' 2019-11-16T00:00:00 2019-11-16T10:00:00´
```
Be aware that the the time zone is Europe/Lisbon. If you need some help setting up your environment reed [this](https://developers.google.com/calendar/quickstart/go) and [this](https://developers.google.com/calendar/v3/reference/events/insert)
