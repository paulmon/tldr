# date

> Set or display the system date.
> More information: <https://ss64.com/osx/date.html>.

- Display the current date using the default locale's format:

`date +%c`

- Display the current date in UTC and ISO 8601 format:

`date -u +%Y-%m-%dT%H:%M:%SZ`

- Display the current date as a Unix timestamp (seconds since the Unix epoch):

`date +%s`

- Display a specific date (represented as a Unix timestamp) using the default format:

`date -r 1473305798`

- Get seconds since epoch for a date-time

`date —date='06/12/2012 07:21:22' +"%s"`

- Get date from seconds since epoch

`date -d @1620966124.350`

- Get current seconds since epoch

`date +%s`