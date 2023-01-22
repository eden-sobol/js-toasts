# js-toasts
a javascript library for creating toasts (pop up notifications) on your website

there is two functions:
toastify.add() and toastify.remove()

add takes these arguments:
toastify.add(id,toastText,delay,x,y,padding,width,height,textColor,backgroundColor,border,borderRadius,orientation)
all args including type

id sets the id of the toast after creation -> string
toastText sets the text on the toast -> string
delay sets how long it takes (milliseconds) -> int
x sets position on x axis relative to orientation -> int
y sets position on y axis relative to orientation -> int
padding sets the padding from the border to text -> int
width sets width of toast (not including border) -> int
height sets height of toast (not including border) -> int
textColor sets the color of the text -> string
backgroundColor sets the color of the background -> string
border sets the border of the toast -> string
borderRadius sets radius of the border -> string (include px)
orientation sets what orientation the toast is (topleft, topright, bottomleft, bottomright) -> string

toastify.remove(id,delay,orientation)
id sets the id to remove -> string
delay sets the delay to remove it -> int
orientation sets the orientation for animation (left, right) -> string
