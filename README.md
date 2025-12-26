# Ex08 Event Registration Web Application
## Date:26.12.2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
home page

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="image" src="img/image-1.png" />
      <img class="sec-image" src="img/sec-image-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Pongal Fest 25-26</div>
      <div class="div"></div>
      <div class="login">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Login</div>
      <div class="rectangle-2"></div>
      <div class="register">&nbsp;&nbsp; Register</div>
      <div class="designed-by">
        Designed by:<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SABARINATHAN A<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;25005972
      </div>
    </div>
  </body>
</html>

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
style.css

.frame {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 1311px;
  min-height: 1791px;
  position: relative;
}

.frame .image {
  position: absolute;
  top: 326px;
  left: 488px;
  width: 334px;
  height: 334px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .sec-image {
  position: absolute;
  top: 35px;
  left: 42px;
  width: 1227px;
  height: 247px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.frame .text-on-a-path {
  position: absolute;
  top: 1164px;
  left: 1992px;
  width: 1075px;
  height: 200px;
}

.frame .rectangle {
  position: absolute;
  top: 811px;
  left: 218px;
  width: 907px;
  height: 160px;
  background-color: #bdbdbd;
}

.frame .text-wrapper {
  position: absolute;
  top: 824px;
  right: 186px;
  width: 880px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 90px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 1104px;
  left: 431px;
  width: 503px;
  height: 129px;
  background-color: #0b07ff;
}

.frame .login {
  position: absolute;
  top: 1104px;
  left: 431px;
  width: 449px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #fff6f6;
  font-size: 90px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-2 {
  position: absolute;
  top: 1358px;
  left: 431px;
  width: 503px;
  height: 133px;
  background-color: #0400ff;
}

.frame .register {
  position: absolute;
  top: 1358px;
  left: 454px;
  width: 480px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #fef9f9;
  font-size: 90px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .designed-by {
  position: absolute;
  top: 1616px;
  left: 863px;
  width: 464px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

second page

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="rectangle" src="img/rectangle-1.png" />
      <div class="div"></div>
      <p class="pongal-pot-ceremony">
        →Pongal Pot Ceremony<br /><br />→Kabaddi<br /><br />→Rope Pulling (Tug of War)<br /><br />→Folk Dance<br /><br />→Kolam
        Competitions<br /><br />→Sing a Song<br /><br />→Make Your Pongal
      </p>
      <div class="text-wrapper">Special Events</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 1288px;
  min-height: 1829px;
  position: relative;
}

.frame .rectangle {
  position: absolute;
  top: 37px;
  left: 32px;
  width: 1196px;
  height: 1767px;
  object-fit: cover;
}
.frame .div {
  position: absolute;
  top: 178px;
  left: 121px;
  width: 1018px;
  height: 214px;
  background-color: #f1e61f;
}

.frame .pongal-pot-ceremony {
  position: absolute;
  top: 529px;
  left: 198px;
  width: 843px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 60px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
.frame .text-wrapper {
  position: absolute;
  top: 223px;
  left: 198px;
  width: 843px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #663483;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

last page

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="rectangle"></div>
      <div class="text-wrapper">e</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Registration Form</div>
       <img class="union" src="img/union.svg" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">REG.NO</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-4">MOB.NO</div>
      <div class="text-wrapper-5">SUBMIT</div>
      <div class="text-wrapper-6">NAME</div>
      <div class="text"></div>
      <div class="text-wrapper-7">YEAR</div>
      <div class="text-wrapper-8">DEPT</div>
      <div class="rectangle-6"></div>
    </div>
  </body>
</html>

golbal.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 1280px;
  min-height: 1859px;
  position: relative;
}

.frame .rectangle {
  position: absolute;
  top: 41px;
  left: 72px;
  width: 1164px;
  height: 1790px;
  background-color: #eb9d9d;
}

.frame .text-wrapper {
  position: absolute;
  top: 245px;
  left: 267px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 170px;
  left: 172px;
  width: 889px;
  height: 191px;
  background-color: #f35c5c;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 204px;
  left: 193px;
  width: 944px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .union {
  position: absolute;
  top: 510px;
  left: 193px;
  width: 330px;
  height: 121px;
}

.frame .rectangle-2 {
  position: absolute;
  top: 710px;
  left: 193px;
  width: 330px;
  height: 119px;
  background-color: #d9d9d9;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 737px;
  left: 238px;
  width: 247px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #301717;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-3 {
  position: absolute;
  top: 925px;
  left: 193px;
  width: 330px;
  height: 124px;
  background-color: #d9d9d9;
}

.frame .rectangle-4 {
  position: absolute;
  top: 1128px;
  left: 193px;
  width: 330px;
  height: 129px;
  background-color: #d9d9d9;
}

.frame .rectangle-5 {
  position: absolute;
  top: 1338px;
  left: 190px;
  width: 330px;
  height: 129px;
  background-color: #d9d9d9;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 1364px;
  left: 232px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #201111;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 1564px;
  left: 520px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 538px;
  left: 232px;
  width: 385px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #1b1414;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text {
  position: absolute;
  top: 985px;
  left: 263px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 948px;
  left: 267px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #1c1010;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-8 {
  position: absolute;
  top: 1155px;
  left: 273px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #241313;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-6 {
  position: absolute;
  top: 1546px;
  left: 443px;
  width: 407px;
  height: 114px;
  background-color: #cd1010;
}

```


## OUTPUT:

home page

![alt text](<Screenshot (60).png>)

second page

![alt text](<Screenshot (61).png>)

last page

![alt text](<Screenshot (62).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
