
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

and FORMAT can be any format allowed by the date command in PHP

Some common Formats:

- "Y-m-d"     will produce 2015-06-25
- "d/m/Y"     will produce 25/06/2015
- "M jS Y"    will produce Jun 25th 2015
- "l jS F Y"  will produce Thursday 25th June 2015

You can also set the default format in the phpList settings. It will appear in the General settings.
When you have a default format, you can leave FORMAT empty and just use eg.

[TODAY]

The replacement works both in the body of a campaign and the subject of the campaign.



