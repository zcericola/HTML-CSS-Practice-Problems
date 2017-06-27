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

In this step, we will create a webpage that has the same structure and styling as the `step-1.jpg` image. We will accomplish this by adding some css styles to our webpage.

### Instructions

* Open the `level-1` folder and take a look inside. We have folders for steps one through three, a solution folder which is step-4, and an `index.html` file. You will be using the same `index.html` file for all three steps in this level.
* Now open the `step-1` folder and notice that there two items inside. There is a css file named `step-1.css` and an image named `step-1.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-1.css` file. Ok, lets start styling.
* Level 1 Step 1.1
In this step, we will position the header at the top of the page.
  * Open `step-1.css`.
  * We need to place the header on the top of the page.
  * The header automatically gets put at the top of the page because it is the first element on the HMTL file. So we don't need to add styling to the header.
* Level 1 Step 1.2
In this step, we will try to move box named content left to the left side of the page.
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
* Level 1 Step 1.3
In this step, we are going to position the box called content-mid to the left side of the page.
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
* Level 1 Step 1.4
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

<summary> <code>step-1.css</code> </summary>

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

In this step, we will create a webpage that has the same structure and styling as the `step-2.jpg` image. We will accomplish this by adding more css styles to our webpage.

### Instructions

* Now open the `step-2` folder and notice that there two items inside. There is a css file named `step-2.css` and an image named `step-2.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-2.css` file. Ok, lets start styling.
* Level 1 Step 2.1
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
* Level 1 Step 2.2
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
* Level 1 Step 2.3
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
* Level 1 Step 2.4
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

<summary> <code>step-2.css</code> </summary>

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

In this step, we will update our webpage so that it has the same structure and styling as the `step-3.jpg` image. We will accomplish this by adding more css styles to our webpage.

### Instructions
* Now open the `step-3` folder and notice that there two items inside. There is a css file named `step-3.css` and an image named `step-3.jpg`. The image in this folder is what you will try to re-create. We will accomplish this by adding some styling in the `step-3.css` file and an p tag element in the `index.html` file. Ok, lets begin.
* Level 1 Step 3.1
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
* Level 1 Step 3.2
  * Open `index.html`.
  * Look for the div with a class of `content`. It is inside the `content-left` div. Once you've found it insert a p tag inside the div and add some text inside.
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
* Level 1 Step 3.3
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
* Level 1 Step 3.4
  * Open `step-3.css`.
  * Give the element with a class of `content- container` a width of 80%. Like this `width: 80%`.
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

<summary> <code>step-1.css</code> </summary>

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




## Copyright

© DevMountain LLC, 2016. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.
