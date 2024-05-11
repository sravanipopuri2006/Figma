# Ex09 Event Registration Web Application
## Date:

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
Page-1
<div style="width: 100%; height: 100%; padding-left: 10px; padding-right: 10px; padding-top: 33px; padding-bottom: 33px; background: #FFE500; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 10px; display: inline-flex">
    <img style="width: 392px; height: 89px; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)" src="https://via.placeholder.com/392x89" />
    <div style="width: 374px; height: 174px; color: black; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">  SEC PROUDLY <br/>     PRESENTS <br/>SPORTS EVENT </div>
    <div style="width: 366px; height: 59px; background: #001BA6; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
    <div style="width: 369px; height: 50px; color: white; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">LOGIN<br/></div>
    <div style="width: 366px; height: 59px; background: #001BA6; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
    <div style="width: 370px; height: 62px; color: white; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">REGISTER</div>
</div>
//   SEC PROUDLY <br/>     PRESENTS <br/>SPORTS EVENT 
color: black;
 font-size: 48px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
---
// LOGIN<br/>
color: white;
 font-size: 48px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
---
// REGISTER
color: white;
 font-size: 48px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
```
```
Page-2
<div style="width: 100%; height: 100%; position: relative; background: #FFE500">
    <div style="width: 374px; height: 174px; left: 11px; top: 201px; position: absolute; text-align: center; color: black; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">SPORTS DAY   EVENTS</div>
    <img style="width: 392px; height: 89px; left: -7px; top: 47px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)" src="https://via.placeholder.com/392x89" />
    <div style="width: 313px; height: 390px; left: 32px; top: 357px; position: absolute; color: #001BA6; font-size: 36px; font-family: Inter; font-style: italic; font-weight: 500; word-wrap: break-word">--> CRICKET<br/>--> BADMINTON<br/>--> VOLLEY BALL<br/>--> FOOT BALL<br/>--> 100M RACE<br/>--> 500M RACE<br/>--> RELAY<br/>--> SWIMMING<br/>--> BASKET BALL</div>
</div>
// SPORTS DAY EVENTS
color: black;
 font-size: 48px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
---
// --> CRICKET<br/>--> BADMINTON<br/>--> VOLLEY BALL<br/>--> FOOT BALL<br/>--> 100M RACE<br/>--> 500M RACE<br/>--> RELAY<br/>--> SWIMMING<br/>--> BASKET BALL
color: #001BA6;
 font-size: 36px;
 font-family: Inter;
 font-style: italic;
 font-weight: 500;
 word-wrap: break-word;
```
```
`Page-3
<div style="width: 100%; height: 100%; position: relative; background: #FFE500">
    <img style="width: 392px; height: 89px; left: 3px; top: 48px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)" src="https://via.placeholder.com/392x89" />
    <div style="width: 370px; height: 75px; left: 12px; top: 151px; position: absolute; text-align: center; color: black; font-size: 30px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word"> EVENT REGISTRATION FORM</div>
    <div style="width: 358px; height: 46px; left: 12px; top: 225px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 358px; height: 46px; left: 12px; top: 463px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 185px; height: 20px; left: -7px; top: 477px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">DEPARTMENT</div>
    <div style="width: 358px; height: 46px; left: 12px; top: 643px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 358px; height: 46px; left: 12px; top: 343px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 122px; height: 19px; left: -12px; top: 356px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">AGE</div>
    <div style="width: 122px; height: 19px; left: 0px; top: 416px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">AGE</div>
    <div style="width: 358px; height: 46px; left: 12px; top: 583px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 185px; height: 20px; left: -26px; top: 595px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">E-MAIL ID</div>
    <div style="width: 358px; height: 46px; left: 12px; top: 403px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 185px; height: 20px; left: 9px; top: 416px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">REGISTER NUMBER</div>
    <div style="width: 185px; height: 20px; left: 12px; top: 655px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">EVENT TO REGISTER</div>
    <div style="width: 358px; height: 46px; left: 12px; top: 284px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 122px; height: 19px; left: 4px; top: 298px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">GENDER<br/></div>
    <div style="width: 358px; height: 46px; left: 12px; top: 523px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 185px; height: 20px; left: 0px; top: 537px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">MOBILE NUMBER</div>
    <div style="width: 122px; height: 19px; left: 16px; top: 239px; position: absolute; text-align: center; color: black; font-size: 15px; font-family: Inter; font-weight: 600; word-wrap: break-word">FULL NAME</div>
    <div style="width: 267px; height: 94px; left: 65px; top: 717px; position: absolute; background: #001BA6; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
    <div style="width: 369px; height: 50px; left: 102px; top: 731px; position: absolute; color: white; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">SUBMIT</div>
</div>
//  EVENT REGISTRATION FORM
color: black;
 font-size: 30px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
---
// DEPARTMENT
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// AGE
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// AGE
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// E-MAIL ID
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// REGISTER NUMBER
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// EVENT TO REGISTER
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// GENDER<br/>
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// MOBILE NUMBER
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// FULL NAME
color: black;
 font-size: 15px;
 font-family: Inter;
 font-weight: 600;
 word-wrap: break-word
---
// SUBMIT
color: white;
 font-size: 48px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
```
```
Page-4
<div style="width: 100%; height: 100%; position: relative; background: #FFE500">
    <img style="width: 392px; height: 89px; left: 0px; top: 47px; position: absolute; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)" src="https://via.placeholder.com/392x89" />
    <div style="width: 382px; height: 168px; left: 6px; top: 245px; position: absolute; text-align: center; color: black; font-size: 64px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">THANK YOU </div>
    <div style="width: 360px; height: 195px; left: 16px; top: 471px; position: absolute; text-align: center; color: black; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">WE ARE ALL EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORT EVENT...</div>
</div>
// THANK YOU 
color: black;
 font-size: 64px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
---
// WE ARE ALL EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORT EVENT...
color: black;
 font-size: 32px;
 font-family: Inter;
 font-style: italic;
 font-weight: 800;
 word-wrap: break-word
```


## OUTPUT:
![image](https://github.com/sravanipopuri2006/Figma/assets/139778301/dfbc7fc1-fe8e-47ea-a99a-6126dd815fcf)
![image](https://github.com/sravanipopuri2006/Figma/assets/139778301/9ab78650-9887-4193-9758-0369c2214daf)
![image](https://github.com/sravanipopuri2006/Figma/assets/139778301/ef535878-8498-4c47-ad2c-ae63bea7a619)
![image](https://github.com/sravanipopuri2006/Figma/assets/139778301/6ba62b66-d75a-4947-94a7-843f678144b3)






## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
