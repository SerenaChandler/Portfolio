# Personal Portfolio

## Languages Used
-Html was used to write out all of the text on the page, as well as attach the images.
-Css was used to apply effects to the page, and adjust the HTML

## Summary of the assignment
This weeks assignment was to construct a portfolio. I kept mine pretty similar to the example funtionionally, but took some creative liberties design wise. I have links at the top of the page to navigate
the portfolio, which can take a viewer to a different area on the page. The areas are split into about me, a place to put my work, a section with a list of ways to contact me, and a spot for my resume,
whenever I actually get one.

## code snippet (example of media query)
```CSS


@media screen and (max-width: 768px) {
    

    header {
        display: flex;
        flex-direction: column;
        
        font-family: fantasy;
        background: linear-gradient(rgb(255, 255, 255),rgb(245, 193, 255));
        font-size: 70px;
        color: rgb(255, 198, 247);
        -webkit-text-stroke-width: 2px;
        -webkit-text-stroke-color: black;
        border: solid 5px rgb(255, 255, 255);
        min-width: 500px;
    }

    .nav-link {
        text-decoration: underline;
        
        
    }

.selfie {
    width: auto;
    height: auto;
}

    .text-pic {
        margin-right: 100px;
        display: flex;
        flex-direction: column;
        padding-bottom: 5px;
    }
    
    .work {
        min-width: 500px;
       
    }

    .about-me {
        min-width: 500px;
    }
    
    .surf-image, .surf {
        max-height: 300px;
        max-width: 300px;
        
        
    }

    .surf-text {
        text-align: center;
        position: absolute;
        top: 40%;
        left: 10%;
        font-size: 50px;  
    }

    .surf {
        position: relative;
        right: 105px;
    }  
}
```

## My Links
[Github](https://github.com/SerenaChandler)