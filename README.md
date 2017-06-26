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

Create a webpage that has the same structure and styling as the `step-1.jpg` image.

### Instructions

* Level 1 Step 1.1
  * We need to place the header on the top of the page.
  * The header automatically gets put at the top of the page because it is the first element on the HMTL file. So we don't need to change the header.

* Level 1 Step 1.2
  * Open `step-1.css`
  * Give `.content-left` a css style of `float: left`.
  * <details>

    <summary> <code> Solution to Step 1.2 </code> </summary>

    ```css
    .content-left{
      width: 33.3%;
      <!-- this height is a placeholder. You will need to make some adjustments to get this container to look like the design -->
      height: 100px;
      background: #565555;
      float: left;
    }
    ```

    </details>


* Level 1 Step 1.3
  * Open `step-1.css`
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
  * Open `step-1.css`
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

## Solution

<details>

<summary> <code>Solution</code> </summary>

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

## Copyright

© DevMountain LLC, 2016. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.
