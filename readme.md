 
#  Responsive Card Slider
Animated Card Slider with glassmorphism effect

In this practice we set up a basic swiper/slider component with multiple items, pagination, and navigation buttons, using the SwiperJS library. 
***
##  Branch  'dev1'

On this branch we have structured the base swiper/slider skeleton.

![screenshot](pics/screenshot1.png)

***
##  Branch 'dev2'

On this branch we styled the card slider, and give it a sleek and modern glassmorphism effect.

![screenshot](pics/screenshot2.png)

***
##  Branch 'dev3'

Lastly we added Javascript code to initialize **'SwiperJS'** and make the card slider functional.

***
##  Branch 'joint', 'QA' and 'main'

To appreciate the final result, we merged the three dev branches into 'joint', 'QA' and 'main'.

These branches contains the same changes and the browser will render it as follow:

![screenshot](pics/screenshot3.png)

***

![gif](pics/slider.gif)

***

#  Code analysis
 
##  HTML File

Here we defined a swiper/slider component with the following elements:

- A container element with the class **'swiper-container'**, which wraps the entire swiper/slider component.

- A div element with the class **'swiper-wraper'**, which contains the swiper/slider items.

- Multiple **'div'** elements with the class **'card-item swiper-slide'**, which represent individual swiper/slider items. Each item contains:

    - An **'img'** element with a profile picture

    - An  **'h2'** element with the name of the user

    - A **'p'** element with the user's profession

    - A **'button'** element with a "message label"

- A **'div'** element with the class **'swiper-pagination'**, which will display pagination indicators for the swiper/slider.

- Two **'div'** elements with the classes **'swiper-slide-button swiper-button-prev'** and **'swiper-slide-button swiper-button-next'**, which will display previous and next navigation buttons for the swiper/slider.

**SwiperJS Script**

We also included a script tag that link to the swiperJS library(version 11) from a CDN, which is commonly used for creating swiper/slider components.

***

##  CSS File
### Our CSS code was structured into four main blocks to style the cards and slider:

1-  **Global Styles ('*' selector)**
This block sets the default styles for all HTML elements, including:

- Removing default margins and padding

- Setting the box model to include padding and border

- Defining the default font family as Montserrat
***

2- **Body Styles (body selector)**
This block styles the <body> element, which is the parent container for the slider and cards. It:

- Centers the content horizontally and vertically using flexbox

- Sets the minimum height to the full viewport height

- Applies a background image and color
***

3- **Slider Wrapper Styles (.slider-wrapper selector)**
This block styles the container element that wraps the slider, which includes:

- Hiding any overflow content

- Setting a maximum width

- Defining the margin and padding for the slider wrapper
***

4- **Card List Item Styles (.card-list .card-item selector)**
This block styles the individual card items within the slider, which includes:

- Setting the height to automatic

- Defining the text color, padding, and display type

- Centering the content horizontally and setting the flex direction to column
***
Note: Each block builds upon the previous one to create a cohesive design for the cards and slider. 

The CSS code was structured in a logical and modular way, making it easy to maintain and update individual components without affecting the overall design.
***

## JS File
### Our JavaScript code is structured into three main blocks to handle the slider functionality.

Initialization The code creates a new instance of the Swiper class, passing two arguments:



-  **Code section title 5**
>
```css
Put your code here exactly as it is.
```

***

![reading...](https://media.giphy.com/media/Tf3mp01bfrrUc/giphy.gif?cid=ecf05e47wajghtrc5targr7mju7coe0avdyurnehrr1krgdt&ep=v1_gifs_search&rid=giphy.gif&ct=g "...How could I ever do so unless someone guide me?")

***