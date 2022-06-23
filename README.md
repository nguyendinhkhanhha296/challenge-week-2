# challenge-week-2
Bootcamp challenge week 2

![My edit](/02-Challenge/Assets/images/2022-06-23-02-39-nguyendinhkhanhha296.github.io.png)
![My edit](https://github.com/nguyendinhkhanhha296/challenge-week-2/blob/main/02-Challenge/Assets/images/screencapture-nguyendinhkhanhha296-github-io-challenge-week-2-2022-06-23-02_46_16.png)
![My edit](https://github.com/nguyendinhkhanhha296/challenge-week-2/blob/main/02-Challenge/Assets/images/screencapture-nguyendinhkhanhha296-github-io-challenge-week-2-2022-06-23-02_47_13.png)

## The Process

### HTML file: 
#### Add some comment:
```
<!-- Header -->

<!-- employee photo -->

<!-- About me section -->

<!-- Work section -->

<!--CSS grid of images-->

<!-- Contact me section -->

<!--List item elements-->

``` 

### CSS file:
#### Add some comment:
```
/* apply styles to <header> */

/*apply style to image*/

/*Add employees photo*/

/*Work section style*/

/*Contact me section style*/

 /*Code for media query*/
 
 ```
  
#### Resize the page to 981px and 768px to view the site on different styles:

```
@media screen and (max-width: 981px) {
    header {
      padding-bottom: 10px;
      justify-content: center;
    }
  
    header h1 {
      width: 100%;
      text-align: center;
    }
  
    header nav ul {
      margin-top: 20px;
      width: 100%;
      justify-content: center;
      flex-direction: row;
      line-height: 1.5;
    }
  
    header nav ul li a {
      font-size: 16px;
      font-weight: bold;
    }
    

    .id-photo {
      background-size: cover;
      display:-webkit-box;
    }

    

    .image {
      height: 125px;
      width: 100px;
    }
     
    
    .id-photo h2 {      
      font-size: 25px;
      margin-top: 180px;
      position:absolute;
      right: 20px;
      } 

    .intro p{
        width: 100%;
      }
      
    .flex-row { 
      width: 180px;
      }

    #section-title {
      width: 100%;
      text-align: right;
      font-size: 35px;
    }

    .border1 {      
      height: 130px;     
    }

    .border2{
    height: 650px;     
    }  

    .container{
      width: 100%;
    }
    
    figcaption{
      margin-left: 5px;
      font-size: 8px;
  }
    
    .border3{
      height: 170px;
      }

    .contact-info ul {     
      width: 100%;
      justify-content: left;
      flex-direction: column;      
      }
  
    .contact-info ul li a {
      font-size: 18px;
      line-height: 2;  
      font-weight: bold;
    }
  }

  @media screen and (max-width: 768px) {
    header {
      background-color: #ffffff;
    }
  
  header h1 {
      font-size: 60px;
    }
  
  header nav {
      margin: 7px 0;
    }
  
  header nav ul li a {
      font-weight: lighter;
      font-size: 2.3vw;
    }
     
.id-photo h2 {
    font-style: italic;
    font-size: 25px; 
    background-color:rgb(0, 0, 0);
  }

  .intro p{
    text-align: justify;
    }

  .general {
    display:flow-root; 
    width: 90%;
  }
   
#section-title {
    font-size: 30px;
    color: var(--body-color);
    text-align: left;
  }
  
.border1 {
    display:none;
  }

.intro p{
  width: 90%;
}
  
.border2 {
    display: none;
  }

#contact-me {
  background-color: rgb(5, 72, 5);
  border-style: dashed;
  border-radius: 30px;
}
  
.border3 {
    display: none;
  }
  
.contact-info ul {
    margin-left: 50px;
    }
  
.contact-info ul li a {
    font-size: 16px;
    }
    .contact-info a {
      display: none;
    }
    
    #contact-me:hover a {
       display:initial;    
    }

```
### URL
* https://github.com/nguyendinhkhanhha296/challenge-week-2
* https://nguyendinhkhanhha296.github.io/challenge-week-2/
