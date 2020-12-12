# Assignment_1_code_refactor

## User Story
summary here 

## Link to deployed project
https://daveymanuel.github.io/Assignment_1_code_refactor/

## 1st commit
HTML

Line 13 and 25 - changed div to nav
-In style.css changed div selector to nav

Line 11 and 26 - changed div to header 

Line 7 - Created a descriptive title for webpage "Horiseon Social Solution Services, Inc."

Line 28 and 50 - changed div to section

Line 29, 35, 36, 42, 43, and 49 - Changed divs to article

Line 36 and 43 - deleted IDs because class was sufficient and no ids were used in CSS sheet

Line 51 and 73 - changed div to section

Line 74 and 79 - changed div to footer

Line 52, 58, 59, 65, 66, and 72 - changed divs to article 

Line 6 - added type to link tag

## 2nd commit
HTML

Added descriptive alt attributes to all images in HTML

## 3rd commit
CSS

Consolidated redundant h2 styles under the section named benefits

Consolidated reduntant img styles under content section

Consolidated reduntant article styles under content section

Consolidated reduntant img styles under benefits section

Added single quotes to 'Calibri' font-family under .content article

## 4th commit
CSS

Consolidated redundant h3 styles under benefits section

Consolidated redundant article styles under benefits section

Added single quotes to 'Calibri' font family under .benefits 

Added single quotes to 'Calibri' font family under nav

Moved font-size style under the body instead of under seperate p selector

Deleted multiple selectors from nav bar because there is only one nav tag, one ul tag, and one li tag in the whole HTML document. Example: .header nav became just nav, .header nav ul became just ul, and .header nav ul li became just li.

## 5th commit
CSS

Moved content styling ahead of benefits styling to match the flow of our HTML

Moved styling for .content img to both classes .float-left and .float-right because they were describing the same element

Started to comment my stylesheet

HTML

Re-added IDs to the three article elements in the content section because I realized I needed them in order for our anchor tags to function correctly.