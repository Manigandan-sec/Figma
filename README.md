# Ex08 Event Registration Web Application
## Date: 24-12-2025

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
page 1.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="logo" src="img/logo-1.png" />
      <img class="SEC-logo" src="img/SEC-logo-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Cybersecurity fest(2.O)</div>
      <div class="div"></div>
      <div class="sign-up">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Sign Up</div>
      <div class="rectangle-2"></div>
      <div class="sign-in">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Sign In</div>
    </div>
  </body>
</html>

page 1.css

.android-medium {
  background-color: #0088ff;
  width: 100%;
  min-width: 443px;
  min-height: 837px;
  position: relative;
}

.android-medium .logo {
  position: absolute;
  top: 10px;
  left: 0;
  width: 443px;
  height: 96px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .SEC-logo {
  position: absolute;
  top: 125px;
  left: 88px;
  width: 268px;
  height: 273px;
  aspect-ratio: 0.98;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 432px;
  left: 28px;
  width: 388px;
  height: 81px;
  background-color: #d37373;
  border-radius: 200px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 450px;
  left: 44px;
  width: 342px;
  font-family: "Abril Fatface-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 552px;
  left: 103px;
  width: 235px;
  height: 72px;
  background-color: #1bf225;
}

.android-medium .sign-up {
  top: 564px;
  width: 224px;
  position: absolute;
  left: 103px;
  font-family: "Abril Fatface-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 660px;
  left: 103px;
  width: 235px;
  height: 68px;
  background-color: #1cdb39;
}

.android-medium .sign-in {
  top: 660px;
  width: 235px;
  position: absolute;
  left: 103px;
  font-family: "Abril Fatface-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

page 2.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="ellipse"></div>
      <div class="div"></div>
      <div class="text-wrapper">Panel Discussions</div>
      <img class="rectangle" src="img/rectangle-4.svg" />
      <div class="text-wrapper-2">Available events:</div>
      <div class="ellipse-2"></div>
      <div class="text-wrapper-3">Hackathon</div>
      <div class="ellipse-3"></div>
      <div class="text-wrapper-4">awareness training</div>
      <div class="ellipse-4"></div>
      <div class="virtual-reality">&nbsp;&nbsp;&nbsp;&nbsp;Virtual Reality</div>
      <div class="ellipse-5"></div>
      <div class="trivia-night">&nbsp;&nbsp;&nbsp;&nbsp; Trivia Night</div>
      <div class="phishing-simulations">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Phishing&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        ...Simulations...
      </div>
    </div>
  </body>
</html>


page 2.css

.android-medium {
  background-color: #0088ff;
  overflow: hidden;
  width: 100%;
  min-width: 444px;
  min-height: 839px;
  position: relative;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 348px;
  left: -354px;
  width: 292px;
  height: 70px;
}

.android-medium .ellipse {
  top: 603px;
  left: 77px;
  width: 292px;
  height: 77px;
  border-radius: 146px / 38.5px;
  position: absolute;
  background-color: #4f378a;
}

.android-medium .div {
  top: 736px;
  left: 77px;
  width: 292px;
  height: 72px;
  border-radius: 146px / 36px;
  position: absolute;
  background-color: #4f378a;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 758px;
  left: 113px;
  width: 245px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 31px;
  left: 64px;
  width: 318px;
  height: 63px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 43px;
  left: 98px;
  width: 271px;
  font-family: "Abril Fatface-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-2 {
  top: 153px;
  left: 77px;
  width: 281px;
  height: 59px;
  border-radius: 140.5px / 29.5px;
  position: absolute;
  background-color: #4f378a;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 166px;
  left: 145px;
  width: 250px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-3 {
  top: 254px;
  left: 77px;
  width: 286px;
  height: 61px;
  border-radius: 143px / 30.5px;
  position: absolute;
  background-color: #4f378a;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 274px;
  left: 94px;
  width: 271px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-4 {
  top: 356px;
  left: 77px;
  width: 286px;
  height: 70px;
  border-radius: 143px / 35px;
  position: absolute;
  background-color: #4f378a;
}

.android-medium .virtual-reality {
  position: absolute;
  top: 384px;
  left: 99px;
  width: 242px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-5 {
  top: 465px;
  left: 76px;
  width: 287px;
  height: 68px;
  border-radius: 143.5px / 34px;
  position: absolute;
  background-color: #4f378a;
}

.android-medium .trivia-night {
  position: absolute;
  top: 488px;
  left: 100px;
  width: 271px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .phishing-simulations {
  position: absolute;
  top: 610px;
  left: 127px;
  width: 227px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}


page 3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="image" src="img/image-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-2">NAME</div>
      <div class="text-wrapper-3">MOBILE NUMBER</div>
      <div class="text-wrapper-4">REGISTER NUMBER</div>
      <div class="rectangle-5"></div>
      <div class="SUBMIT"><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SUBMIT:</div>
      <p class="e-MAIL">
        <span class="span">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span> <span class="text-wrapper-5">E - MAIL</span>
      </p>
    </div>
  </body>
</html>

page 3.css

.android-medium {
  background-color: #0088ff;
  overflow: hidden;
  width: 100%;
  min-width: 444px;
  min-height: 839px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 444px;
  height: 839px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 22px;
  left: 21px;
  width: 395px;
  height: 63px;
  background-color: #009951;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 39px;
  left: 39px;
  width: 377px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 122px;
  left: 21px;
  width: 233px;
  height: 66px;
  background-color: #3f80ea;
  border-radius: 200px;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 211px;
  left: 222px;
  width: 222px;
  height: 68px;
  background-color: #3271d7;
  border-radius: 200px;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 314px;
  left: 0;
  width: 222px;
  height: 67px;
  background-color: #3271d7;
  border-radius: 200px;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 420px;
  left: 222px;
  width: 222px;
  height: 72px;
  background-color: #3271d7;
  border-radius: 200px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 151px;
  left: 80px;
  width: 139px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 229px;
  left: 250px;
  width: 178px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 322px;
  left: 15px;
  width: 204px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 754px;
  left: 111px;
  width: 213px;
  height: 57px;
  background-color: #8f0b09;
}

.android-medium .SUBMIT {
  position: absolute;
  top: 750px;
  left: 117px;
  width: 181px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .e-MAIL {
  position: absolute;
  top: 445px;
  left: 228px;
  width: 228px;
  font-family: "Aclonica-Regular", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .span {
  color: #ffffff;
}

.android-medium .text-wrapper-5 {
  color: #181717;
}

```

## OUTPUT:
![alt text](<Screenshot (74).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
