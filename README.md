# Ex09 Event Registration Web Application
## Date:07.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
page1
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="frame"></div>
      <img class="screenshot" src="img/screenshot-2025-10-06-185212-1.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper">sa</div>
      <p class="saveetha-engineering">
        <span class="span"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span>
        <span class="text-wrapper-2"
          >saveetha&nbsp;&nbsp;&nbsp;&nbsp; engineering<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;college<br
        /></span>
        <span class="text-wrapper-3"
          >&nbsp;&nbsp;
          <br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;REGISTRATIONS
          OPEN</span
        >
      </p>
      <div class="div">r</div>
      <img class="img" src="img/screenshot-2025-10-06-190445-1.png" />
      <p class="YOU-DON-t-GET-WHAT">
        <span class="text-wrapper-4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span class="text-wrapper-5"
          >YOU&nbsp;&nbsp;DON’T&nbsp;&nbsp;GET&nbsp;&nbsp;WHAT&nbsp;&nbsp;YOU<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          WISH&nbsp;&nbsp;FOR , YOU <br />&nbsp;&nbsp;&nbsp;&nbsp; GET&nbsp;&nbsp;
          WHAT&nbsp;&nbsp;YOU&nbsp;&nbsp;WORK&nbsp;&nbsp;FOR</span
        >
      </p>
      <img class="screenshot-2" src="img/screenshot-2025-10-06-191647-1.png" />
    </div>
  </body>
</html>

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

.android-medium {
  background-color: #57d9f9;
  overflow: hidden;
  width: 100%;
  min-width: 4950.7px;
  min-height: 5559.78px;
  position: relative;
}

.android-medium .frame {
  position: absolute;
  top: 4039px;
  left: 4211px;
  width: 100px;
  height: 100px;
  background-color: #27e4b1b5;
  transform: rotate(0.11deg);
}

.android-medium .screenshot {
  position: absolute;
  top: 104px;
  left: 668px;
  width: 1874px;
  height: 1587px;
  transform: rotate(0.11deg);
  aspect-ratio: 1.18;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 2872px;
  left: 253px;
  width: 100px;
  height: 100px;
  transform: rotate(0.11deg);
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 11705px;
  left: 1971px;
  width: 4550px;
  height: 750px;
  transform: rotate(0.11deg);
}

.android-medium .text-wrapper {
  position: absolute;
  top: 2442px;
  left: 394px;
  transform: rotate(0.11deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .saveetha-engineering {
  position: absolute;
  top: 2676px;
  left: 343px;
  width: 4520px;
  transform: rotate(0.11deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .span {
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
}

.android-medium .text-wrapper-2 {
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
}

.android-medium .text-wrapper-3 {
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
}

.android-medium .div {
  position: absolute;
  top: 3746px;
  left: 240px;
  width: 4570px;
  transform: rotate(0.11deg);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 4087px;
  left: 1144px;
  width: 3619px;
  height: 1410px;
  transform: rotate(0.11deg);
  aspect-ratio: 2.57;
  object-fit: cover;
}

.android-medium .YOU-DON-t-GET-WHAT {
  position: absolute;
  top: 288px;
  left: 2426px;
  width: 2343px;
  transform: rotate(0.11deg);
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-4 {
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
}

.android-medium .text-wrapper-5 {
  font-family: "Irish Grover-Regular", Helvetica;
}

.android-medium .screenshot-2 {
  position: absolute;
  top: 1245px;
  left: 2668px;
  width: 1977px;
  height: 1304px;
  transform: rotate(0.11deg);
  aspect-ratio: 1.52;
  object-fit: cover;
}
page 2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <p class="REGISTRATION-PROCESS">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; REGISTRATION&nbsp;&nbsp; PROCESS<br />NOTE: ENTER&nbsp;&nbsp;
        VALID&nbsp;&nbsp;AND&nbsp;&nbsp;UPDATED<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        DETAILS
      </p>
      <img class="screenshot" src="img/screenshot-2025-10-06-192218-1.png" />
      <div class="ENTER-YOUR-NAME">
        ENTER&nbsp;&nbsp;YOUR&nbsp;&nbsp;NAME:<br /><br />ENTER&nbsp;&nbsp;YOUR&nbsp;&nbsp;REFERENCE&nbsp;&nbsp;NUMBER:<br /><br />ENTER&nbsp;&nbsp;YOUR&nbsp;&nbsp;DEPARTMENT:<br /><br />ENTER&nbsp;&nbsp;WHICH&nbsp;&nbsp;YEAR&nbsp;&nbsp;YOU&nbsp;&nbsp;BELONG&nbsp;&nbsp;TO:<br /><br />ENTER&nbsp;&nbsp;YOUR&nbsp;&nbsp;EMAIL&nbsp;&nbsp;ID:<br /><br />ENTER&nbsp;&nbsp;YOUR&nbsp;&nbsp;PHONE&nbsp;&nbsp;NUMBER:
      </div>
    </div>
  </body>
</html>

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

.android-medium {
  background-color: #ec4242;
  width: 100%;
  min-width: 3100px;
  min-height: 5701px;
  position: relative;
}

.android-medium .REGISTRATION-PROCESS {
  position: absolute;
  top: 271px;
  left: 130px;
  width: 2730px;
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #290303;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .screenshot {
  position: absolute;
  top: 1021px;
  left: 220px;
  width: 2640px;
  height: 1060px;
  aspect-ratio: 2.49;
  object-fit: cover;
}

.android-medium .ENTER-YOUR-NAME {
  position: absolute;
  top: 2881px;
  left: 250px;
  width: 2500px;
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #facd47;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

page 3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="screenshot" src="img/screenshot-2025-10-06-193613-1.png" />
      <p class="DANCE-COMPETITION">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DANCE&nbsp;&nbsp;COMPETITION<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MUSIC&nbsp;&nbsp;COMPETITION<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        ARTS&nbsp;&nbsp;COMPETITION<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RUNNING&nbsp;&nbsp;COMPETITION<br />&nbsp;&nbsp;
        <br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DEBATE&nbsp;&nbsp;COMPETITION<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        CODING&nbsp;&nbsp;COMPETITION<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SPEECH&nbsp;&nbsp;COMPETITION<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        MATHEMATICS&nbsp;&nbsp;COMPETITION<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        GENERAL&nbsp;&nbsp;KNOWLEDGE&nbsp;&nbsp;QUIZ
      </p>
    </div>
  </body>
</html>

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

.android-medium {
  background-color: #f7cc1d;
  width: 100%;
  min-width: 2942.13px;
  min-height: 5664.79px;
  display: flex;
  flex-direction: column;
  gap: 643.9px;
}

.android-medium .screenshot {
  margin-left: 324.8px;
  width: 2201px;
  height: 1220px;
  margin-top: 609.7px;
  transform: rotate(-0.25deg);
  aspect-ratio: 1.8;
  object-fit: cover;
}

.android-medium .DANCE-COMPETITION {
  margin-left: 241.0px;
  width: 2416px;
  height: 2697px;
  transform: rotate(-0.25deg);
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #000000;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

page 4

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="screenshot" src="img/screenshot-2025-10-06-194717-1.png" />
      <p class="THANK-YOU-FOR">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;THANK&nbsp;&nbsp;
        YOU&nbsp;&nbsp;
        <br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FOR&nbsp;&nbsp;REGISTERING&nbsp;&nbsp;
        WITH<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SAVEETHA&nbsp;&nbsp;
        EVENTS&nbsp;&nbsp;&nbsp;&nbsp; CLUB<br /><br /><br /><br /><br />CONTACT&nbsp;&nbsp;OUR&nbsp;&nbsp;
        EMAIL&nbsp;&nbsp;FOR&nbsp;&nbsp; ANY<br /><br />
        QUERIES:SAVEETHA@GMAIL.COM
      </p>
    </div>
  </body>
</html>

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

.android-medium {
  background-color: #d269a8;
  width: 100%;
  min-width: 3103px;
  min-height: 5316px;
  display: flex;
  flex-direction: column;
  gap: 632px;
}

.android-medium .screenshot {
  margin-left: 298px;
  width: 2583px;
  height: 2013px;
  margin-top: 501px;
  aspect-ratio: 1.28;
  object-fit: cover;
}

.android-medium .THANK-YOU-FOR {
  margin-left: 394px;
  width: 2371px;
  height: 1838px;
  font-family: "Inter-ExtraBold Italic", Helvetica;
  font-weight: 800;
  font-style: italic;
  color: #5333c5;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}

```
## OUTPUT:
![alt text](<Screenshot 2025-10-06 195448.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
