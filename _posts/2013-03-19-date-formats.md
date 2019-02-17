---
layout: post
title: Date Formats
redirect_from:
  - /date-formats
  - /2013/03/19/time
last_modified_at: 2019-02-12
---
There really is only one good short date format:

<code>YYYY-MM-DD</code>

The others are all broken:
* <code>MDY</code>, <code>DMY</code>:  
    (<code>MM/DD/YYYY</code>, <code>MM.DD.YY</code>, <code>DD/MM/YYYY</code> etc.)
  * Doesn't sort alphabetically;
  * Will confuse [the majority of the population of the
    world](https://en.wikipedia.org/wiki/Date_format_by_country) much of the time — the first twelve
      days of every month (excluding days the day number and month number match) the reader can't
      distinguish between MDY and DMY except by inference. Did the author intend
      <code>3/2/2019</code> to be read as a February date or a March date? Don't settle for
      ambiguity on 132 days of every year.
* <code>YDM</code>: … just don't.

[Wikipedia: Date format by country](https://en.wikipedia.org/wiki/Date_format_by_country)  
[RFC 3339](https://www.ietf.org/rfc/rfc3339.txt)  
[XKCD: ISO 8601](http://xkcd.com/1179/)

<small>(edited 2019-02-12)</small>
