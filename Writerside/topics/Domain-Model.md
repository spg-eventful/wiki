# Domain Model

## The TechnicalLog

The most complicated part of our domain model is the TechnicalLog implementation.
The TechnicalLog is responsible for the display of an equipment's movements.

A technical log logs the following for each action:

* from location + datetime
* to location + datetime
* by who (who was responsible for this duration)

Here is a simple example of one log

| from                | to                         | who?  |
|---------------------|----------------------------|-------|
| Warehouse 1 @ 13:00 | Warehouse 2 @ 15:00        | Ilja  |
| Warehouse 2 @ 18:00 | Event 1 @ 21:30            | Ilja  |
| Event 1 @ 21:30     | Event 1 @ 23:00            | Jakob |
| Event 1 @ 23:00     | Warehouse 1 @ 04:00 +1 day | Ilja  |

```PlantUML
```

{ src="../pumls/domain-model.puml" }