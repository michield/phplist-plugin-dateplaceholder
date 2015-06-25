
# phplist-plugin-dateplaceholder
provides date related placeholders in campaigns

Using this plugin will add date related placeholders:

You can use formatting like the "date" command in PHP (see https://php.net/date)

The general format for a placeholder is:

[PLACEHOLDER:FORMAT]

where PLACEHOLDER can be one of:

- TODAY
- YESTERDAY
- TOMORROW
- NEXTWEEK
- LASTWEEK
- NEXTMONTH
- LASTMONTH
- (more to follow)

and Format can be any format allowed by the date command in PHP

You can also set the default format in the phpList settings. It will appear in the General settings.
When you have a default format, you can leave FORMAT empty and just use eg.

[TODAY]


