NOTES:
This extension uses simple style sheet to force CJK (2E80-FFFF) using Microsoft YaHei
and the rest range of unicode using "Open Sans".

Chrome browser uses three types of style sheets by the following rule, where the number 3
has the highest priority:
1. User agent (Chrome browser) default style sheet
2. User (Chrome extension) style sheet
3. Webpage itself style sheet

All above style sheets support !important to ignore subsequent rules

This extension does not use JavaScript, instead, uses simple CSS file to improve
page loading/rendering performance


Known issues:
1. u8 icon fonts are not able to render properly
