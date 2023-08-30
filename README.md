# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
The challenge was designed to build a testimonial page in which i made use of HTML and CSS

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](C:\Users\OLUWAFEMI\Desktop\FREECOD\testimonials-grid-section-main\Screenshot (4).png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1 Initialize your project as a public repository on [GitHub](https://github.com/). Creating a repo will make it easier to share your code with the community if you need help. If you're not sure how to do this
2. Configure your repository to publish your code to a web address. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, and we provide some recommendations below.
3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.
4. Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.
5. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox
- CSS Grid


### What I learned

I learnt the effective way to make use of Grid and also how to succesfully deploy to repositories

To see how you can add code snippets, see below:

```html
 <div class="data-container" id="image-kira">
                <figure class="image-data">
                    <img src="../images/image-kira.jpg" alt="image-kira">
                    <figcaption class="data-side">
                        <h4>Kira Whittle</h4>
                        <p>Verified Graduate</p>
                    </figcaption>
                </figure>
                <article class="text-box">
                    <p class="bold">Such a life-changing experience. Highly recommended!</p>
                    <blockquote>
                        <p class="block-text">
                            Before joining the bootcamp, I’ve never written a line of code. I needed some structure from 
                            professionals who can help me learn programming step by step. I was encouraged to enroll by a former 
                            student of theirs who can only say wonderful things about the program. The entire curriculum and staff 
                            did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team 
                            project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial 
                            could ever have. In fact, I’ve often referred to it during interviews as an example of my developent 
                            experience. It certainly helped me land a job as a full-stack developer after receiving multiple offers. 100% recommend! 
                        </p>
                    </blockquote>
                </article>
            </div>
        </div>
    </div>
```
```css
.grid{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-auto-rows: auto;
    gap: 1rem;
    align-content: center;
    justify-content: center;
    padding: 100px auto;
}
```

### Continued development

I plan to continue learning more concept of grid and layout 


### Useful resources

- [Grid](https://www.youtube.com/watch?v=EaWj2AWI5Es) - This helped me for Grid reason. I really liked this pattern and will use it going forward.
- [Github](https://www.youtube.com/watch?v=CvUiKWv2-C0) - This is an amazing article which helped me finally understand Github. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)




