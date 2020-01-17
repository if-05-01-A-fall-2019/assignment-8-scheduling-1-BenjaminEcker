# Basic of Scheduling

## 1.)

Für eine Prozess wird vorher eine bestimmte Zeit festgelegt in der seine Sachen ausführen kann wenn er aber irgendwo blockiert wird er einfach gestoppt und muss sich als neuer Prozess hinten einreihen.

## 2.)

| Process |A | B | C | D | E | F | G | H |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
Expected run time (msec) | 8 | 5 | 16 | 12 | 55 | 21 | 2 | 34
---

Sum: 576
Average: 19,125

| Process |G | B | A | D | C | F | H | E |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
Expected run time (msec) | 2 | 5 | 8 | 12 | 16 | 21 | 34 | 55
---

2,5,8,12,16,21,34,55
Sum: 409
Average: 51,125 
