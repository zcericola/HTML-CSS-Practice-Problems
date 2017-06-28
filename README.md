<!-- # HTML-CSS-Practice-Problems

<img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">


##Objective

Understand HTML & CSS

##Directions

* Fork this repo then clone your fork onto your local machine.
* Each level is broken up into three steps. Each step contains an image and a css file.
* The objective is to have a finished product that looks as close to the design as possible.
* Inside the index.html file you  will see the different practice problems. For example Step-1.1 would be step 1 question 1.
* Start with level 1 step 1 question 1 and work your way through the problems
* Your first step should be connecting your CSS files to the index.html
* In every level we have included the possible solution folder please only look at this as a last resort or if you are finished with all the steps and want to see how your solution compares -->

<img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">

# Project Summary

In this project you will be re-creating multiple html templates using the HTML and CSS skills you have learned so far. There will be 3 levels of difficulty, each being a template and having its own steps to get to the end solution. In each step you will be given a jpeg image that you will need to re-create. Each step will be a continuation of the previous. The goal is to get your project to look as close as you can to the design of the images provided. Good luck!

## Setup

* Clone and fork this GitHub Repo
* `cd` into the project directory

## Important Notes

* In this repo we include a folder named `base`, leave this folder alone. You will not need to change any code in this folder to complete the project.
* Each level has an `index.html` file, you will use the same `index.html` file for each of the steps in the current level.
* To see your progress right click on the `index.html` file you are currently working on and select `show in finder`. Then double click on the `index.html` file. This should open up a browser tab with what you have so far.

## Level 1 Step 1

### Summary

In this step, we will create a webpage that has the same structure and styling as the `level-1/step-1/step-1.jpg` image. We will accomplish this by adding some css styles to our webpage.

### Instructions

* Open the `level-1` folder and take a look inside. We have folders for steps one through three, a solution folder which is step-4, and an `index.html` file. You will be using the same `index.html` file for all three steps in this level.
* Now open the `step-1` folder and notice that there two items inside. There is a css file named `step-1.css` and an image named `step-1.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-1.css` file. Ok, lets start styling.
* Level 1 Step 1.1 <br>
In this step, we will position the header at the top of the page.
  * Open `step-1.css`.
  * We need to place the header on the top of the page.
  * The header automatically gets put at the top of the page because it is the first element on the HMTL file. So we don't need to add styling to the header.
* Level 1 Step 1.2 <br>
In this step, we will try to move box with a class of `content-left` to the left side of the page.
  * Open `step-1.css`.
  * Give `.content-left` a css style of `float: left` and a `padding-top: 35px`. The reason we gave the div with a class of `.content-left` a padding on top is that it will have content inside in the future.
    * <details>

      <summary> <code> Solution to Step 1.2 </code> </summary>

      ```css
      .content-left{
        width: 33.3%;
        <!-- this height is a placeholder. You will need to make some adjustments to get this container to look like the design -->
        height: 100px;
        background: #565555;
        float: left;
        padding-top: 35px;
      }
      ```

      </details>
* Level 1 Step 1.3 <br>
In this step, we are going to position the box with a class of `content-mid` to line up directly to the right of `.content-left`.
  * Open `step-1.css`.
  * Give `.content-mid` a css style of `float: left`.
    * <details>

      <summary> <code> Solution to Step 1.3 </code> </summary>

      ```css
      .content-mid {
          width: 66.3%;
          <!-- this height is a placeholder. You will need to make some adjustment to get this container to look like the design -->
          height: 100px;
          background: #B0B0B0;
          float: left;
      }
      ```

      </details>
* Level 1 Step 1.4 <br>
In this step, we will position the footer at the bottom of the page.
  * Open `step-1.css`.
  * Give `.footer` a css style of `position: absolute` and `bottom: 0`.
    * <details>

      <summary> <code> Solution to Step 1.4 </code> </summary>

      ```css
      .footer {
          width: 100%;
          height: 100px;
          background: #3A3A3A;
          position: absolute;
          bottom: 0;
      }
      ```

      </details>
* Level 1 Step 1.5
  * Now all we need to do is change the height and width on the divs so that your webpage looks as close as it can to the `step-1.jpg`.

### Solution

<details>

<summary> <code>level-1/step-1/step-1.css</code> </summary>

```css
.header {
    width: 100%;
    height: 100px;
    background: #D8D8D8;
}

.content-left {
    width: 33.3%;
    height: 76vh;
    padding-top: 35px;
    float: left;
    background: #565555;
}

.content-mid {
    width: 66.66%;
    height: 76vh;
    float: left;
    background: #B0B0B0;
}

.footer {
    width: 100%;
    height: 100px;
    background: #3A3A3A;
    position: absolute;
    bottom: 0;
}
```

</details>

## Level 1 Step 2

### Summary

In this step, we will create a webpage that has the same structure and styling as the `level-1/step-2/step-2.jpg` image. We will accomplish this by adding more css styles to our webpage.

### Instructions

* Now open the `step-2` folder and notice that there two items inside. There is a css file named `step-2.css` and an image named `step-2.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-2.css` file. Ok, lets start styling.
* Level 1 Step 2.1 <br>
In this step, we will add the first box in the content-left container.
  * Open `step-2.css`.
  * Give the `.profile-image-container` a height and a width so you can see it on the webpage.
  * Give the `.profile-image-container` a margin of auto.
  * Now that the div with the `.profile-image-container` class is centered you can go in and change the height and width to match the `step-2.jpg`.
    * <details>

      <summary> <code> Solution to Step 2.1 </code> </summary>

      ```css
      .profile-image-container {
          width: 80%;
          height: 180px;
          margin: auto;
          background: #96F0F2;
      }
      ```

      </details>
* Level 1 Step 2.2 <br>
In this step, we will add the second box in the content-left container.
  * Open `step-2.css`.
  * Give the div with a class of `.profile-links-container` a height and a width so you can see the element on the webpage.
  * Now lets try to give the div with a class of `.profile-links-container` a margin top, left and right all at the same time using the short-hand version. Like this `margin: 20px auto;`.
  * Now that the div with the `.profile-links-container` class is centered you can go in and change the height and width to match the `step-2.jpg`.
    * <details>

      <summary> <code> Solution to Step 2.2 </code> </summary>

      ```css
      .profile-links-container {
          width: 80%;
          height: 300px;
          margin: 20px auto;
          background: #12F3F7;
      }
      ```

      </details>
* Level 1 Step 2.3 <br>
In this step, we will add the rectangle in the header and position in correctly to the left side of the webpage.
  * Open `step-2.css`.
  * Give the div with a class of `.logo-container` a height and a width so you can see the element on the webpage.
  * Now we need to move the element over to the left like you see in `step-2.jpg`. So lets make it float left by using `float: left`.
  * Now the element is too close to the top-left corner. So lets give it a `margin-top` and a `margin-left`. Like this `margin-top: 20px` and `margin-left: 10px`.
  * The last thing we need to do is fix the height and the width to make our webpage look as close as we can to `step-2.jpg`.
    * <details>

      <summary> <code> Solution to Step 2.3 </code> </summary>

      ```css
      .logo-container {
          width: 26%;
          height: 60px;
          float: left;
          margin-left: 30px;
          margin-top: 20px;
          background: #4F4949;
      }
      ```

      </details>
* Level 1 Step 2.4 <br>
In this step, we will add the square in the header and position in correctly to the right side of the webpage.
  * Open `step-2.css`.
  * Give the div with a class of `.menu-container` a height and a width so you can see the element on the webpage.
  * Now we need to move the element over to the right like you see in `step-2.jpg`. So lets make it float right by using `float: right`.
  * Now the element is too close to the top-right corner. So lets give it a `margin-top` and a `margin-right`. Like this `margin-top: 20px` and `margin-right: 30px`.
  * The last thing we need to do is fix the height and the width to make our webpage look as close as we can to `step-2.jpg`.
    * <details>

      <summary> <code> Solution to Step 2.4 </code> </summary>

      ```css
      .menu-container {
          width: 60px;
          height: 60px;
          float: right;
          margin-right: 10px;
          margin-top: 20px;
          background: #4F4949;
      }
      ```

      </details>

### Solution

<details>

<summary> <code>level-1/step-2/step-2.css</code> </summary>

```css
.logo-container {
    width: 26%;
    height: 60px;
    float: left;
    margin-left: 30px;
    margin-top: 20px;
    background: #4F4949;
}

.menu-container {
    width: 60px;
    height: 60px;
    float: right;
    margin-right: 10px;
    margin-top: 20px;
    background: #4F4949;
}

.profile-image-container {
    width: 80%;
    height: 180px;
    margin: auto;
    background: #96F0F2;
}

.profile-links-container {
    width: 80%;
    height: 300px;
    margin: 20px auto;
    background: #12F3F7;
}
```

</details>

## Level 1 Step 3

### Summary

In this step, we will update our webpage so that it has the same structure and styling as the `level-1/step-3/step-3.jpg` image. We will accomplish this by adding more css styles to our webpage.

### Instructions

* Now open the `step-3` folder and notice that there two items inside. There is a css file named `step-3.css` and an image named `step-3.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-3.css` file. We will also need to add a `<p></p>` tag element in the `index.html` file located in the level-1 folder. Ok, lets begin.
* Level 1 Step 3.1 <br>
In this step we will start making the content in the `.mid-content` div by adding a header to it.
  * Open `step-3.css`.
  * Lets give the element with a class of `.content-mid-header` a height of 100px. Like this `height: 100px`.
  * Now our element is showing on the webpage. Good Job!
    * <details>

      <summary> <code> Solution to Step 3.1 </code> </summary>

      ```css
      .content-mid-header {
          background: #444;
          height: 100px;
      }
      ```

      </details>
* Level 1 Step 3.2 <br>
In this step we will add some text inside of our `.content-left` div.
  * Open `index.html`.
  * Look for the div with a class of `.content`. It is inside the `.content-left` div. Once you've found it insert a p tag inside the div and add some text inside.
    * <details>

      <summary> <code> Solution to Step 3.2 </code> </summary>

      ```html
      <div class="content">
          <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, </p>
      </div>
      ```

      </details>
* Level 1 Step 3.3 <br>
In this step, we will fix the alignment and positioning of the text we added in the previous step.
  * Open `step-3.css`
  * Now we can see our text is not in the correct spacing. Let's fix that by adding some padding. Like this `padding: 50px`.
  * We should also fix the way the text is aligned. For that lets add `text-align: center`.
  * Lastly our div seems to look a little short. Giving it a height should fix that. Try this `height: 275px`. Looking a lot better. Let's continue!
    * <details>

      <summary> <code> Solution to Step 3.3 </code> </summary>

      ```css
      .content {
        padding: 50px;
        text-align: center;
        height: 275px;
      }
      ```

      </details>
* Level 1 Step 3.4 <br>
In this step, we will changing the size of the container that is housing the content we added in the previous two steps.
  * Open `step-3.css`.
  * Give the element with a class of `content-container` a width of 80%. Like this `width: 80%`.
  * We can also see in the image that this div has to be centered and moved down a bit. Lets accomplish that by giving it some margin. Like this `margin: 40px auto`.
    * <details>

      <summary> <code> Solution to Step 3.4 </code> </summary>

      ```css
      .content-container {
        background: #D8D8D8;
        width: 80%;
        margin: 40px auto;
      }
      ```

      </details>
  * Wow! That looks pretty good. Congratulations you have finished level-1!

### Solution

<details>

<summary> <code>level-1/step-3/step-3.css</code> </summary>

```css
.content-mid-header {
    height: 100px;
    background: #444;
}

.content-container {
    width: 80%;
    margin: 40px auto;
    background: #D8D8D8;
}

.content {
    height: 275px;
    padding: 50px;
    text-align: center;
}
```

</details>

## Level 2 Step 1

### Summary

In this step, we will also be re-creating an image that will be provided to you. We will accomplish this by adding some css styles to our webpage. Good luck!

### Instructions

* Open the `level-2` folder and take a look inside. We have folders for two steps, a solution folder which is name `step-3-possible-solution`, and an `index.html` file. You will be using the same `index.html` file for both steps in this level.
* Now open the `step-1` folder and notice that there two items inside. There is a css file named `step-1.css` and an image named `level-2-step-1.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-1.css` file. Ok, lets start styling.
* Level 2 Step 1.1 <br>
In this step, we will be giving the div with a class of `.main-top-section` a position property that will allow its future child elements to change their position according to it.
  * Open `step-1.css`.
  * Give `.main-top-section` a position property of relative. Like this `position: relative`.
  * The reason we do this is that future children elements that will use a position of absolute will refer to the first parent with a set position. So we set a position on `.main-top-section` to have it be the parent being referred to.
    * <details>

      <summary> <code> Solution to Step 1.1 </code> </summary>

      ```css
      .main-top-section {
          width: 100%;
          height: 375px;
          background: #F7F1E7;
          position: relative;
      }
      ```

      </details>
* Level 2 Step 1.2 <br>
In this step, we will be positioning the small menu box in the left hand side of the `level-2-step-1.jpg` image.
  * Open `step-1.css`.
  * Let's start by giving `.menu` a display of inline-block. Like this `display: inline-block`. This will make it display side-by-side.
  * Next lets give `.menu` a position of absolute. Like this `position: absolute`. This will give you the option to position the `.menu` element according to the first ancestor that has a position. That ancestor will be the `.main-top-section` because we gave it a position of relative in the previous step.
  * Now we have the ability to give the `.menu` div a top, right, bottom, and left css property.
  * Lets give `.menu` a left position of 10px and a top position of 10px. Like this `left: 10x` and `top: 10px`.
  * Now the `.menu` element is in the correct position. But the other two elements are stacked on top. Let's fix that!
  * Let's give `.logo` a display of inline-block. Like this `display: inline-block`.
  * Let's also give the element with a class of `.sign-in` a display of inline-block as well.
  * Now let's give `.sign-in` a position of absolute, and a top and right property to position it correctly. Like this `position: absolute`, `top: 10px`, and `right: 10px`.
  * That looks better!
    * <details>

      <summary> <code> Solution to Step 1.2 </code> </summary>

      ```css
      .menu {
          width: 100px;
          height: 40px;
          background: #536A63;
          display: inline-block;
          position: absolute;
          left: 10px;
          top: 10px;
      }

      .logo {
          width: 300px;
          height: 40px;
          margin-top: 10px;
          background: #536A63;
          display: inline-block;
      }

      .sign-in {
          width: 100px;
          height: 40px;
          background: #536A63;
          display: inline-block;
          position: absolute;
          right: 10px;
          top: 10px;
      }
      ```

      </details>
* Level 2 Step 1.3 <br>
In this step, we will position the last green element overhanging below its parent element.
  * Open `step-1.css`.
  * Now how are we going to move the element towards the bottom in reference to its parent? Position absolute of course! So lets give the element with a class name of `.bottom-container` a position of absolute. Like this `position: absolute`.
  * Lastly let's give it a bottom and left properties. The bottom property will need to be a negative pixel value so that it is overhangs. Like this `bottom: -30px` and `left: 22%`;
  * Looking good!
    * <details>

      <summary> <code> Solution to Step 1.3 </code> </summary>

      ```css
      .bottom-container {
          width: 60%;
          height: 60px;
          position: absolute;
          bottom: -30px;
          left: 22%;
          background: #536A63;
      }
      ```

      </details>

### Solution

<details>

<summary> <code>level-2/step-1/level-1-step-3.css</code> </summary>

```css
.main-top-section {
    width: 100%;
    height: 375px;
    background: #F7F1E7;
    position: relative;
}

.top-header {
    width: 100%;
    height: 70px;
    text-align: center;
    background: #D8D8D8;
}

.menu {
    width: 100px;
    height: 40px;
    display: inline-block;
    position: absolute;
    left: 10px;
    top: 10px;
    background: #536A63;
}

.logo {
    width: 300px;
    height: 40px;
    display: inline-block;
    margin-top: 10px;
    background: #536A63;
}

.sign-in {
    width: 100px;
    height: 40px;
    display: inline-block;
    position: absolute;
    right: 10px;
    top: 10px;
    background: #536A63;
}

.bottom-container {
    width: 60%;
    height: 60px;
    position: absolute;
    bottom: -30px;
    left: 22%;
    background: #536A63;
}
```

</details>

## Level 2 Step 2

### Summary

In this step, we will also be re-creating an image that will be provided to you. We will accomplish this by adding some css styles to our webpage. Good luck!

### Instructions

* Now open the `step-2` folder in level-2 and notice that there two items inside. There is a css file named `step-2.css` and an image named `level-2-step-2.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-2.css` file. Let's go!
* Level 2 Step 2.1 <br>
In this step, we will be using a css property to align items in the center of the webpage.
  * Open `step-2.css`.
  * Give the element with the class name of `main-bottom-section` a property of text-align with a value of center. Like this `text-align: center`.
    * <details>

      <summary> <code>level-2/step-1/level-1-step-3.css</code> </summary>

      ```css
      .main-bottom-section {
          margin-top: 65px;
          text-align: center;
      }
      ```

      </details>
* Level 2 Step 2.2 <br>
In this step, we will be adding a width, height and display property to make the small square containers look like the `level-2-step-2.jpg` image.
  * In the `level-2-step-2.jpg` image you can see there are three different types of boxes in the bottom container. The small square, the rectangle, and the big square.
  * Lets give each of these their corresponding height and width.
  * Open `step-2.css`.
  * Starting with the small squares which have a class name of `.item`, lets give them a height and a width. Like this `height: 200px` and `width: 40%`.
  * But our items are not lined up correctly. Lets give them a property so they display side-by-side. Like this `display: inline-block`.
  * Looks perfect!
    * <details>

      <summary> <code>level-2/step-1/level-1-step-3.css</code> </summary>

      ```css
      .item {
          display: inline-block;
          height: 200px;
          width: 40%;
          background: #DED6D3;
          margin-bottom: 30px;
      }
      ```

      </details>
* Level 2 Step 2.3 <br>
In this step, we will be adding a width, height and a margin property to make the rectangle container look like the `level-2-step-2.jpg` image.
  * Open `step-2.css`.
  * Now lets focus on the rectangle element with a class of `.full-width-item`. Let's give this element a width and height. Like this `width: 80%` and `height: 200px`.
  * Now the element is the right size but too close to the surrounding elements. Lets fix that by giving `.full-width-item` a css property of margin with the correct value. Like this `margin 0 auto 30px`. When you give an element a margin property with 3 values it takes the first value as the margin-top the two middle values as the left and right margins and the last value as the bottom-margin.
    * <details>

      <summary> <code>level-2/step-2/level-2-step-2.css</code> </summary>

      ```css
      .full-width-item {
          width: 80%;
          height: 200px;
          margin:0 auto 30px;
          background: #DED6D3;
      }
      ```

      </details>
* Level 2 Step 2.4 <br>
In this step, we will add a height, width and a margin to make the big square look like the `level-2-step-2.jpg` image.
  * Open `step-2.css`.
  * On the element with a class name of `.large-item` let's give it a height and with property. Like this `height: 500px` and `width: 80%`.
  * Again too close to the surrounding elements lets give it some margin. Like this `margin: 0, auto, 30px`.
  * Nice! Congratulations you've finished level-2.
    * <details>

      <summary> <code>level-2/step-2/level-2-step-2.css</code> </summary>

      ```css
      .large-item {
          width: 80%;
          height: 500px;
          margin:0 auto 30px;
          background: #DED6D3;
      }
      ```

      </details>

### Solution

<details>

<summary> <code>level-2/step-2/level-2-step-2.css</code> </summary>

```css
.main-bottom-section {
    margin-top: 65px;
    text-align: center;

}

.item {
    display: inline-block;
    height: 200px;
    width: 40%;
    background: #DED6D3;
    margin-bottom: 30px;
}

.full-width-item {
    width: 80%;
    height: 200px;
    margin:0 auto 30px;
    background: #DED6D3;
}

.large-item {
    width: 80%;
    height: 500px;
    margin:0 auto 30px;
    background: #DED6D3;
}
```

</details>

## Level 3 Step 1

### Summary

In this step, we will be adding the images and logos to the layout designs that we made in the previous two levels. We'll be combining them to create a one big design. Have fun!

### Instructions

* Open the `level-3` folder and take a look inside. We have an `img` folder, folders for three steps, a solution folder which is named `step-4-possible-solution`, and an `index.html` file. You will be using the same `index.html` file for all three steps in this level.
* Check out what's inside the `img` folder. You will be using these images and icons in your webpage.
* Now open the `step-1` folder and notice that there two items inside. There is a css file named `step-1.css` and an image named `level-3-step-1.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-1.css` file. Ok, lets start styling.
* Level 3 Step 1.1 <br>
In this step, we will be adding a background image to the `main-top-section`.
  * Open `step-1.css`.
  * Give the element with a class of `.main-top-section` a background property with a value pointing to the `Background.png` image inside the `img` folder. Like this `background: url("../img/Background.png") no-repeat`. First you set the background to `url()`. Then you used `..` to go up one directory, then `/img` to enter the `img` folder, then `/Background.png` to select the background image file. Then adding `no-repeat` to the back of the url will make the image not repeat. By default the image will repeat to cover the whole page.
  * Next let's give the background image a property of `background-size` with a value of `cover`. Like this `background-size: cover`.
  * Looks great! On to the next step.
    * <details>

      <summary> <code>level-2/step-2/level-2-step-2.css</code> </summary>

      ```css
      .main-top-section {
          width: 100%;
          height: 530px;
          position: relative;
          background: url("../img/Background.png") no-repeat;
          background-size: cover;
      }
      ```

      </details>
* Level 3 Step 1.2 <br>
In this step, we will be adding the src path on each of the images in the top half of the webpage.
  * Open `index.html`.
  * Find the `<img>` tag with a class of `menu-icon`.
  * Give it a src path that will point to `MENU.png` in the `img/icons` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="menu-icon" src="../img/icons/MENU.png" alt="menu icon">
      ```

      </details>
  * Find the `<img>` tag with a class of `logo-icon`.
  * Give it a src path that will point to `dev-shop.png` in the `img/icons` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="logo-icon" src="../img/icons/dev-shop.png" alt="logo icon">
      ```

      </details>
  * Find the `<img>` tag with a class of `sign-in-icon`.
  * Give it a src path that will point to `Sign_In.png` in the `img/icons` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="sign-in-icon" src="../img/icons/Sign_In.png" alt="sign in  icon">
      ```

      </details>
  * Find the `<img>` tag with a class of `shop-icon`.
  * Give it a src path that will point to `Shop_Deals.png` in the `img/icons` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="shop-icon" src="../img/icons/Shop_Deals.png" alt="shop icon">
      ```

      </details>

### Solution

<details>

<summary> <code>level-3/index.html</code> </summary>

```html
<section class="main-top-section">
    <header class="top-header">

        <div class="menu">
            <!-- Step-1.2 add the path to the menu image on the src attribute -->
            <img class="menu-icon" src="../img/icons/MENU.png" alt="menu icon">
        </div>
        <div class="logo">
            <!-- Step-1.3 add the path to the dev-shop image on the src attribute -->
            <img class="logo-icon" src="../img/icons/dev-shop.png" alt="logo icon">
        </div>
        <div class="sign-in">
            <!-- Step-1.4 add the path to the sign-in image on the src attribute -->
            <img class="sign-in-icon" src="../img/icons/Sign_In.png" alt="sign in icon">
        </div>
    </header>

    <div class="bottom-container">
        <!-- Step-1.5 add the path to shop-deals image on the src attribute -->
        <img class="shop-icon" src="../img/icons/Shop_Deals.png" alt="shop icon">
    </div>
</section>
```

</details>

## Level 3 Step 2

### Summary

In this step, we will continue to add the images and logos to the layout designs that we made in the previous two levels. We'll be combining them to create a one big design. Good luck!

### Instructions

* Level 3 Step 2.1 <br>
In this step, we will be adding the src path on each of the images in the bottom half of the webpage.
  * Open `index.html`.
  * Find the `<img>` tag with a class of `item-image` that is inside the div with both classes `item tops`.
  * Give it a src path that will point to `Tops.png` in the `img` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="item-image" src="../img/Tops.png" alt="tops">
      ```

      </details>
  * Find the `<img>` tag with a class of `item-image` that is inside the div with both classes `item bottoms`.
  * Give it a src path that will point to `bottoms.png` in the `img` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="item-image" src="../img/bottoms.png" alt="tops">
      ```

      </details>
  * Find the `<img>` tag with a class of `item-image` that is inside the div with both classes `full-width-item accessories`.
  * Give it a src path that will point to `accessories.png` in the `img` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="item-image" src="../img/accessories.png" alt="tops">
      ```

      </details>
  * Find the `<img>` tag with a class of `item-image` that is inside the div with a class of `large-item`.
  * Give it a src path that will point to `collection.png` in the `img` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="item-image" src="../img/collection.png" alt="tops">
      ```

      </details>
  * Find the `<img>` tag with a class of `item-image` that is inside the div with both classes `item kicks`.
  * Give it a src path that will point to `kicks.png` in the `img` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="item-image" src="../img/kicks.png" alt="tops">
      ```

      </details>
  * Find the `<img>` tag with a class of `item-image` that is inside the div with both classes `item hats`. C
  * Give it a src path that will point to `hats.png` in the `img` folder.
    * <details>

      <summary> <code>Correct src path</code> </summary>

      ```html
      <img class="item-image" src="../img/hats.png" alt="tops">
      ```

      </details>
      *


### Solution

<details>

<summary> <code>level-3/index.html</code> </summary>

```html
<section class="main-top-section">
    <header class="top-header">

        <div class="menu">
            <!-- Step-1.2 add the path to the menu image on the src attribute -->
            <img class="menu-icon" src="../img/icons/MENU.png" alt="menu icon">
        </div>
        <div class="logo">
            <!-- Step-1.3 add the path to the dev-shop image on the src attribute -->
            <img class="logo-icon" src="../img/icons/dev-shop.png" alt="logo icon">
        </div>
        <div class="sign-in">
            <!-- Step-1.4 add the path to the sign-in image on the src attribute -->
            <img class="sign-in-icon" src="../img/icons/Sign_In.png" alt="sign in icon">
        </div>
    </header>

    <div class="bottom-container">
        <!-- Step-1.5 add the path to shop-deals image on the src attribute -->
        <img class="shop-icon" src="../img/icons/Shop_Deals.png" alt="shop icon">
    </div>
</section>
```

</details>

## Level 3 Step 3

## Summary

In this step, we will be giving our page a little taste of responsiveness. We will be making our images stop growing at a certain screen width. Lets begin!

## Instructions

* Open `index.html`.
* Inside the `<head></head>` uncomment the link to `step-3.css`, and comment out the links to `step-1.css` and `step-2.css`.
* Now open the `step-3` folder. There is a css file named `step-3.css`. In this css file is where we will try to add media queries to make our webpage responsive.
* Scroll to the bottom of the page and look at the syntax for creating a media query. There are some missing pieces but we'll fill them in step by step.
* Inside the parenthesis `@media(  inside here  )` is where we will specify the mix or max width the query will start. We will also include the pixel at which the query will start.
Like this `@media(min-width: 900px)`. This means that starting at a minimum width of 900px the following css styles will be activated.
* Now inside there are three css declaration blocks `.item`, `.full-width-item`, and `.large-item`. Inside each of these set a width property with a pixel value.
* After completing the previous step go to your webpage in the browser and make the browser window width as small as you can and then increase it little by little. The images should stop growing at a width of over 900px.
* Great Job! You just made an amazing looking webpage. Congratulations you have finished this project.
  * <details>

    <summary> <code>level-3/step-3/step-3.css</code> </summary>

    ```css
    @media(min-width: 900px) {
        .item {
            width:400px;
        }
        .full-width-item {
            width: 800px;
        }
        .large-item {
            width: 800px;
        }
    }
    ```

    </details>

### Solution

<details>

<summary> <code>level-3/index.html</code> </summary>

```html
<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <title>level-3</title>
    <link rel="stylesheet" href="../base/base.css">

    <meta author="Ben Callis">
    <!-- STEP 1 CSS FILE **** STEP 1 CSS FILE *** STEP 1 CSS FILE -->
    <!-- <link rel="stylesheet" href="step-1/step-1.css"> -->

    <!-- STEP 2 CSS FILE **** STEP 2 CSS FILE *** STEP 2 CSS FILE -->
    <!-- <link rel="stylesheet" href="step-2/step-2.css"> -->

    <!--&lt;!&ndash; STEP 3 CSS FILE WHEN YOU GET THIS FAR COMMENT OUT step-2.css and step-1.css AND JUST WORK OF THIS FILE &ndash;&gt;-->
    <link rel="stylesheet" href="step-3/step-3.css">


</head>
<body>

<main class="main-wrapper">
    <!-- Step-1.1 add a background image that take up the entire width of container -->
    <section class="main-top-section">
        <header class="top-header">

            <div class="menu">
                <!-- Step-1.2 add the path to the menu image on the src attribute -->
                <img class="menu-icon" src="./img/icons/MENU.png" alt="menu icon">
            </div>
            <div class="logo">
                <!-- Step-1.3 add the path to the dev-shop image on the src attribute -->
                <img class="logo-icon" src="./img/icons/dev-shop.png" alt="logo icon">
            </div>
            <div class="sign-in">
                <!-- Step-1.4 add the path to the sign-in image  on the src attribute -->
                <img class="sign-in-icon" src="./img/icons/Sign_In.png" alt="sign in  icon">
            </div>
        </header>

        <div class="bottom-container">
            <!-- Step-1.5 add the path to shop-deals image on the src attribute -->
            <img class="shop-icon" src="./img/icons/Shop_Deals.png" alt="shop icon">
        </div>
    </section>

    <section class="main-bottom-section">

        <div class="item tops">

            <!-- Step-2.1 add the path to tops image on the src attribute -->
            <img class="item-image" src="./img/Tops.png" alt="tops">

        </div>
        <div class="item bottoms">

            <!-- Step-2.2 add the path to bottoms image on the src attribute -->
            <img class="item-image" src="./img/bottoms.png" alt="tops">

        </div>

        <div class="full-width-item accessories">

            <!-- Step-2.3 add the path to accessories image on the src attribute -->
            <img class="item-image" src="./img/accessories.png" alt="tops">

        </div>

        <div class="large-item">

            <!-- Step-2.4 add the path to collection image on the src attribute -->
            <img class="item-image" src="./img/collection.png" alt="tops">

        </div>

        <div class="item kicks">

            <!-- Step-2.5 add the path to kicks image on the src attribute -->
            <img class="item-image" src="./img/kicks.png" alt="tops">

        </div>
        <div class="item hats">

            <!-- Step-2.6 add the path to hats image on the src attribute -->
            <img class="item-image" src="./img/hats.png" alt="tops">

        </div>

    </section>

</main>
</body>
</html>
```

</details>

<details>

<summary> <code>level-3/step-3/step-3.css</code> </summary>

```css

.main-top-section {
    width: 100%;
    height: 530px;
    position: relative;
    background: url("../img/Background.png") no-repeat;
    background-size: cover;

}


.top-header {
    width: 100%;
    padding-top: 10px;
    height: 70px;
    text-align: center;

}


.menu {
    width: 100px;
    height: 40px;
    display: inline-block;
    position: absolute;
    left: 10px;
    top: 20px;

}

.menu-icon {
    width: 60%;

}

.logo {
    width: 300px;
    height: 40px;
    display: inline-block;
    margin-top: 10px;

}

.logo-icon {
    width: 75%;
}

.sign-in {
    width: 100px;
    height: 40px;
    display: inline-block;
    position: absolute;
    right: 10px;
    top: 30px;

}

.sign-in-icon {
    width: 60%;
}


.bottom-container {
    width: 100%;
    height: 60px;
    position: absolute;
    text-align: center;
    bottom: -30px;

}


.shop-icon {
    width: 350px;
}


.main-bottom-section {
    margin-top: 65px;
    text-align: center;

}

.item {
    display: inline-block;
    width: 40%;
    background: #D6CFC9;
    margin-bottom: 20px;
    padding-top: 20px;
    cursor: pointer;
}

.item-image {
    width: 100%;
    display: block;
}

.full-width-item {
    width: 80%;
    margin:0 auto 20px;
    cursor: pointer;

}


.large-item {
    width: 80%;
    margin:0 auto 20px;
    cursor: pointer;

}

@media(min-width: 900px) {
    .item {
        width:400px;
    }
    .full-width-item {
        width: 800px;
    }
    .large-item {
        width: 800px;
    }
}
```

</details>















## Copyright

© DevMountain LLC, 2016. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.
