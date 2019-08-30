# https://www.hebcal.com

## Description
This system is for convert between Hebrew and Gregorian dates and see today's date in a Hebrew font.

## Entity definition

id - numeric of posted conversions
cfg - what kind of file is needed to get output
gy - Gregorian year
gm - Gregorian month
gd - Gregorian day

## API definition

GET /api/dates/:id - get information about convertion based on ID

POST /api/dates - post information about conversion

DELETE /api/dates/:id - delete information based on ID

PUT api/dates/:id - update informaiton based on ID



