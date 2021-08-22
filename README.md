

# Portfolio Page - UncertainCo.

<strong> Personal Portfolio's Templates for Clients. </strong>

---

# Getting Started

### About Me

---

- Go to **aboutme.html** page
- The title of the page is set to `Home | Portfolio` if you want edit go to `line no : 9` <head> → inside you will find ***<title\> Home | Portfolio </title\>*** change the text inside those tags

    ex : <title\> Portfolio | [Your name] </title\> 

- To Find anything in page use Command `Cntrl+F` and type text you are searching.
- Find `class="logo"` (`line no : 15`)you will redirect to corresponding Div. goto <div\> → <p\> →Change letter* **J** to **First Character of your name.**

    Same as above goto *<p\>→ <strong\>* Change it to your Full Name.

- There is nothing to change in `nav-contents.`
- Find `class="image"` (`line no : 33`) there is an img tag inside that div. <img src=" **Enter your file location with extension .jpg | .png etc.." \/>** *
- Search for `class="content reset"` (`line no : 37`) by using command `Cntrl+F`
    - Change your current profession inside <p tag. You can also add multiple like **<p\> Developer | UI / UX Designer </p\>**
    - Enter your Full Name inside <h2\> tag
- Find `class="icons"` (`line no : 40`) inside <a\> tag there is a href (attribute) replace your hyperlink ( url of the website ) in place of **#**
    - Ex : <a\> href="https: //www.linkedin.com/in/user"  </a\>
    - Do same for remaining - Replace those **#** with corresponding URLs
    - Note: Make sure you place proper URL's for corresponding icons you can check it besides, **class=" fab fa-LinkedIn-in"** which means you should give the URL of the linked-in profile
- Find `class="intro"` (`line no : 47`)
    - Replace that Dummy **Lorem ipsum**  text with a Brief intro of yours which

---

### What I Do?

- Find `class="box"` (`line no : 61, 68, 75, 82`), there are multiple instances of class="box" select first one change <h3\> inside that **class** to title of any skill you know and also change <p\> to brief about that skill or any specialization etc...
- If you want to change the icon beside that text
- [Click here](https://fontawesome.com/v5.15/icons?d=gallery&p=2)  type keyword of the icon you are searching for
- Click on **Start Using This Icon,**  copy the text having <i/> tag
    - Ex : <i\> class="fab fa-accessible-icon" </i\> 
    - replace this class with existing <i\> tag in class="box" div
- Same goes with all the divs having class="box"
- These `class=" box"` are in order, Make sure you enter the details in proper order.

---

### Recommendations

- Find `class="carousel-caption d-none d-md-block"` (`line no : 101, 109, 118`) select first one.
- inside it there is an <img\> tag change its src = "File location of the with extentsion like .jpg | .png etc..."
- Change <h5\> to their Name
- Change <p\> to the text what they thought of you and your work
- Same goes with all the divs containing `class="carousel-caption d-none d-md-block"`
- The divs are in order, make sure you arrange them in priority order
- Note : There is an additional tag <h6\> which tells what is the current position of the person Recommending, If you wish change it to change it in <h6\> <br>**Ex: <h6\> SDE at Amazon </h6\>**

---

### Footer

- Find `class="footer-contents"` (`line no : 138`) , there is a <ul\> tag consisting of some <a\> tags with **href ="#"** change that **#** with corresponding link ( url )
    - Ex : <a href="https://www.linkedin.com/in/Username"\><li\> Linked IN </li\> </a\>

 ****

- Make sure you replace those URLs by checking names in the <li\> tag
- Note: To change copyright year and name, there is an <p\> tag with `class=" copyrights"` (`line no: 147`) change year and Name.

## You're Done with the aboutme.html page

---

### Resume

---

- Go to **resume.html**
- Same as above pages change first letter and full Name (`Line no: 16,17`)
- **Education**
    - Go to `Line no:  43` replace the years, with your period of study.
    - Change the text **Lorem ipsum dolor sit amet.** with College or University Name
    - In `Line no:  45` Change the text within <h3\> with Stream of Study
        - Ex : B.tech, M.tech, Intermediate, SSC etc...
    - In `Line no: 46` change the paragraph with a short description about your experience or any achievements in college.
    - Same Goes with remaining
    - Note: Follow either increasing or decreasing order
    - Ex: From 10th to Undergraduate / Postgraduate
    - or Undergraduate to 10th but don't skip the years between
    - Make sure you enter proper academic years
- **Experience**
    - Same as Education, change the contents in Experience
    - It Starts from `Line no:  69`
    - Change the corresponding years, Names of the company you've worked in the past, any experience you want to share regarding those companies or any projects done by you.
- **Design Skills**
    - Tools and Technologies
        - Go to `Line no:  105` add technologies within those <span\>  tags
            - Ex : <span\> Adobe Premiere Pro </span\>
        - Go to `Line no: 106` rate your knowledge on that particular technology in multiples of 10 and replace percentage within <span\> tags
            - Ex : <span\> 70% </span\>
        - Go to `Line no: 108` add an id beside class="bar-outline" with the percentage you've entered above in words.
            - Ex : If you have entered 70% then add id="seventy" beside class = "bar-outline"
            - In code, it should look like this
                - <div class="bar-outline" id="seventy"\>
        - Repeat the same process with the next technologies as well
        - If you want to add or delete any extra skills
        - This is arranged in blocks which means from `Line No: 103` to `Line no: 111` its termed as a block
        - If you want to add more technologies copy-paste that block of code below (should be above `Line No:130`)
        - If you want to delete any extra technologies delete that block of code from where it's starting.
    - **Development Knowledge**
        - Same goes here follow the same procedure as above
        - replace skills and change the percentages
        - add id with its corresponding percentages
        - Adding and Deleting skills will also be the same.

---

## Footer Contents

---

- Change footer contents in this page too same as **aboutme.html** file
- Things to Change
    - Update your social media links
    - Change Copyright year and your name.
    
---

## You're Done with the resume.html page

---

### Portfolio.html

---

- Go to **portfolio.html**
- Change the first letter of your name and Full Name in `Line no: 16,17`
- In `Line No: 61` change the src to file location containing a screenshot of the project
    - Ex : src = "../images/pic.jpg"
    - Note : Make sure you add file extension i.e .jpg | .png etc...
- In `Line No: 72` same as above change the src with other project screenshot location

---

## Footer Contents

---

- Change footer contents in this page too same as **aboutme.html** file
- Things to Change
    - Update your social media links
    - Change Copyright year and your name.

## You're Done with the portfolio.html page

---

### Contact us
---
- Go to **contact.html** file
- Find `class="logo"`
    - In `Line no: 16` change letter **J to the first letter of your name**
    - In `Line no: 17` change **Jhon Doe** to your Full Name
    - There is nothing to do with `nav-contents`
- Find `class="icon_text`
    - In `Line no: 51`  Change that dummy text ( Lorem Ipsum ) to your **City**
    In `Line no: 52`, change the paragraph to a Short description like where you live in the city, any landmark or Pincode, etc...
- Find `class="icon_text`
    - In `Line no: 60` change the text to your E-mail id
    - In `Line no:  61` give any short info regarding your mail, like when you will check your emails, etc
    - Ex: Mention if you check your mail only on Saturdays etc...

 

---

## Footer Contents

---

- Change footer contents in this page too same as **aboutme.html** file
- Things to Change
    - Update your social media links
    - Change Copyright year and your name.

---

## You're Done with the contact.html page

---
