# time-spent
package to get timestamp between two times

> two functions

`getTimeStampFromDate(date : Date())`

`getTimeStampFromFormattedDate(dateNTime : String)`

> Returns a String - 3 months ago | 6 seconds ago | 9 years ago | 6 months ago

**In this package basically comparing previous moment(Time and Date)  and and the current moment(Time and Date)
so you need to have Previous time stored. So you can input that Date and time and get the value of Time Spent**

## How to use
`npm i time-spent`

> In your testing file

`import ts from 'time-spent';`

If you use `new Date()` with `getTimeStampFromDate` it will return **now**  
`console.log(ts.getTimeStampFromDate(new Date()));`

> prevDate is a

`new Date()`

_If you have previously stored Date, and it will return the value of time spent_
`console.log(ts.getTimeStampFromDate(prevDate));`

_If you have previously stored Date with this format - 'DD/MM/YYYY hh:mm:ss'_
`console.log(ts.getTimeStampFromFormattedDate('12/05/2020 20:45:54'));`
