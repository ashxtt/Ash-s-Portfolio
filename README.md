# Ash's-Portfolio
### Portfolia Idea
#### I have decied to go on the spooky route becasue its october. I have incorporated some gifs that goes with the theme of my website, I have also created the creators of these gifs and linked their pinterest and tumblr, where you can check them out and give them a like. 

## Project Schedule

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Project Description | complete
|Day 2| Wireframes / Priority Matrix / Timeline | complete
|Day 3| Core Application Structure (HTML, CSS, etc.) | complete
|Day 4| MVP & Bug Fixes | complete
|Day 5| Final Touches | complete
|Day 6| Present | complete

## Wireframes

![Wireframe-ash](https://user-images.githubusercontent.com/111319560/192933476-a60292e7-0467-46ec-9e9c-baab1e394a5e.png)

## Time/Priority Matrix 

#### MVP
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | 
| contact button| 1hr | 1hr | 2hr |
| Nav bar | 1hr | 1hr | 1hr |  
| Adding submit Form | 1hr | 2hr|  1.5hr | 
| flex/grid | 1hr | 3hr | 2hr|
| Responsive| 3hr | 4hr | 3.5hr |
| Total | H | 9hrs| 8.5hrs |

#### PostMVP
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | 
| Social Icons | Hr | 2Hr | 3Hr |
| button Hover | 1Hr | 1.5Hr | 2Hr |


## Images used
### I got the bat gif off of pinterest.
### here is the pinterest post where the gif was found: https://www.pinterest.com/pin/649222102539512030/
### This is their tumbler to their artwork: http://pixosprout.tumblr.com/
#### Credit for girl gif:https://www.pinterest.com/pin/756886281144124408/
#### Credit for grave gif:https://www.pinterest.com/pin/90846117468817480/ Their Tumblr:http://fuckyeah-pixels.tumblr.com/post/166229238848
#### Credit for ghost gif:https://www.pinterest.com/pin/357825132909187479/

 

## Code Snippet

#### Another code snippet is from my CSS. I am proud of myself for making the button look so nice

```
.btn{
    display: flex;
    justify-content: center;
    padding:0.40rem;
   }
   .send-btn{
    background-color: #C5C4C3;
    color: #570000;
    padding:0.40rem;
    border: 0.15rem solid black;
    border-radius: 2rem;
    box-shadow: 2px 1px #181717;
    transition: 0.4s;
   }
   .send-btn:hover{
    font-size: 30px;
    border: 0.15rem solid black;
    border-radius: 12px 12px 12px 12px;
    box-shadow: 3px 2px #181717;
   }
   ```
   ### When loading into or realoading the page the contents on the page will drop in.
   
```
const sections = document.querySelectorAll('section[id]')

function scrollActive(){
    const scrollY = window.pageYOffset

    sections.forEach(current =>{
        const sectionHeight = current.offsetHeight
        const sectionTop = current.offsetTop - 50;
        sectionId = current.getAttribute('id')

        if(scrollY > sectionTop && scrollY <= sectionTop + sectionHeight){
            document.querySelector('.navi-menu a[href*=' + sectionId + ']').classList.add('active')
        }else{
            document.querySelector('.navi-menu a[href*=' + sectionId + ']').classList.remove('active')
        }
    })
}

window.addEventListener('scroll', scrollActive)



window.sr = ScrollReveal({ reset: true });


sr.reveal('.home-data, .about-cont, .pro-cont, .contact-cont', {interval:300, delay: 400});
```

## Issues and Resolutions
### One of the issues I had as I was making my portfolia is, I wasn't able to get the page to scroll to each section as I click on the menu bar. I have not resolved that propblem yet. I have learned how to use scroll reveal. I am able to have the contents on the page drop in from different dirrections.
 
