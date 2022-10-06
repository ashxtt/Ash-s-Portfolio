# Ash's-Portfolio

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


## Additional Libraries Used

 

## Code Snippet

 
### scrollActive function use so when clicking on the nav links will take you to that part of the page
```
const sections = document.querySelectorAll('section[id]')

function scrollActive(){
    const scrollY = window.pageYOffset

    sections.forEach(current =>{
        const sectionHeight = current.offsetHeight
        const sectionTop = current.offsetTop - 50;
        sectionId = current.getAttribute('id')

        if(scrollY > sectionTop && scrollY <= sectionTop + sectionHeight){
            document.querySelector('.nav__menu a[href*=' + sectionId + ']').classList.add('active')
        }else{
            document.querySelector('.nav__menu a[href*=' + sectionId + ']').classList.remove('active')
        }
    })
}
```

## Issues and Resolutions
### Had trouble linking my github and linkdeln to social Icons with resolve soon
 
