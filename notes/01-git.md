# Git

html basic prompt = !
Emoji prompt = "windows+period"

copy line = shift alt (down, up)

PADDING IS INTERNAL
MARGIN IS EXTERNAL
BORDER MOSTLY WORKS LIKE PADDING BUT VISIBLE

display:flex
align-items center

let primarycolor =--(blahhhhh)

:root{
    --dark: #hexcolor
    --light: #hexpurple
}

D FLEX BOX, THEN SET WIDTHS OF EACH ITEM

day 3
building w bootstrap
when using bootstrap, start with their code, then overwrite, it matters with flow top bottom

ROWS AND COLUMNS MUST EXIST WITHIN CONTAINER

container uses about 90% of screen
container-fluid is 100%

make rows sections
make columns divs

display:flex
flex-wrap:wrap

you can split a row into 12 columns

if less than 12 and you want to even its justify-content-around or another justify-content class

"gap" instead of Justify-content around

"col-(1 through 12)" in order to set the column width

"class col 3 (color)"
{
m = margin

mt = margin top

mb = margin bottom

ms = margin start 

p = padding

ps = padding start

pe = padding end

py is padding on y axis, top bottom

px is padding on x axis, left-right

fs is font size

btn is button
btn-primary is blue
i class for image
text-danger is red tex
text-light
text-alignment
text-start moves it back to the left side
text-end moves it to the right side

object-fit contain keeps a photo in a stock size while shrinking and growing with width and height

object-position (top, start, end, bottom)

background-image creates the background as a photo

background-size: cover fills the backgroundspace

background-position moves the position of the photo

text rgba and it can change opacity

hue-rotate changes color
}

sizes = lg large, md medium, sm small

have one column with no size infix, have a base col size

class "d-none" = no display

.section.row
.col.6
row


SPAN is an inline element

JUSTIFY CONTENT IS LEFT RIGHT

ALIGN ITEMS IS UP DOWN

col-12 col-md-6 = on medium and smaller screens, on larger screens it will be 12



in display flex you can reorder by placing order-first  on the column 

order-last also works

order 1-5


DAY 4

flex-end: Items align to the right side of the container.
center: Items align at the center of the container.
space-between: Items display with equal spacing between them.
space-around: Items display with equal spacing around them.

align-items

flex-start: Items align to the top of the container.
flex-end: Items align to the bottom of the container.
center: Items align at the vertical center of the container.
baseline: Items display at the baseline of the container.
stretch: Items are stretched to fit the container.

align-self

(accepts same as align-items)

flex-direction

row: Items are placed the same as the text direction.
row-reverse: Items are placed opposite to the text direction.
column: Items are placed top to bottom.
column-reverse: Items are placed bottom to top.

flex-wrap

nowrap: Every item is fit to a single line.
wrap: Items wrap around to additional lines.
wrap-reverse: Items wrap around to additional lines in reverse.

order

(order can go into negative numbers to move an object 
from where it is to where it should be)

FIGMA NOTES

Control G makes all elements above 

when you get a figma or a mockup try to break up row column and container

"outline the grid system"

red for container

yellow for row

green for column

use header, name footer to denote a three-part body, use header1, header2,
body1, body2 for a multiple

container will have a little margin, container-fluid will fill

"think mobile first"

for mobile col-md-6

