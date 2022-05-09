
![SR CorSo logo](https://user-images.githubusercontent.com/29462447/167288774-90a643e1-0745-4966-ab75-aa67f08060ae.png)

# ✨ [Architecture Premier League](https://www.linkedin.com/posts/prashanth-panduranga-3a18737_swissre-techsharp-architecture-activity-6910474096925454336-OTR0?utm_source=linkedin_share&utm_medium=member_desktop_web) - MyRec [![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)

## 📑 Our Problem Statement - MyRec

⁉ **Assumptions**   
* Partner Company Bigzee sells Grocery.
* Meal planner can be availed for MyRec recipes only
* 1M+ user base for the app which is increasing rapidly as well.
* App functionality is worldwide. However, ingredient shopping is currently only available in India. We would consider options based on the requirement.
* BigZee is a trusted grocery chain in India. It has its presence in most of the major cities. However, ingredients’ delivery option is dependent on the zip code of the customer.
 
🛠 **Compatible with all devices**
 
1. MyRec company wants a one place solution to organize individual user's recipes retrieved through various sources so that recipes are maintained in a single place. Subscription of the application at Basic and Premium package. Basic is only Recipe storage, Premium is   Recipe +Meal Planner + Ingredients Shopping.   
2. Personalized space to be available with Table of contents categorized as Main course, Starters, soup, salad, dessert, juice etc. )  
3. Users Shall be able to upload recipes (printed or handwritten recipes etc.) and store it with a name.
4. Users shall be able to create a cookbook and recipes attached to it. Users Shall be able to adjust the font, size, text style etc. 
5. Shall be able to import recipes from different websites or blogs and store it with a name already autofill but can be adjusted manually. Ingredients, cooking method, pictures and other parameters should be separated out and displayed. 
6. Shall be able to scan recipes and get details converted possible only if any text available in the scanned image. 
7. Write additional notes images on recipes.  
8. Any Story to Add about recipe to give additional layer through a photo/video (ex: traditional family passed recipe) 
9. Add, search, Organizing and sorting of recipes. Shall be able to Print as well. 
10. Shall be able to download recipes 
11. In built Meal planner packages with videos to be available with distinct categories (ex: Regular and Specialized) Regular package has a category to input number of days and number of recipes and a rate change dynamically. Minimum is 7 days. Special Package has many numbers of categories (example: weight loss, Protein rich, etc.) and rate is fixed as per package chosen. Each package consists of many recipes. These recipes can be moved along with personalized already available contents of user recipes.   
12. Can add and store ingredients under specific grocery name like Beverages, Cooking, Baking, Bakery, Seafood etc. 
13. App suggests meals out of the available ingredients  
14. Shall be able to shop from a company called Bigzee and make the order along with payment.  
15. Update of Usage of Ingredients for status of remaining ingredients after the order is received 
•	Shall be able to Share recipes to social media  
•	Data and meta data configurable by the Admin user 

## 🛠 Proposed System Architecture

![167287681-9a5cb7bc-7bc3-4d7c-85ba-b18b5bc52e50](https://user-images.githubusercontent.com/29462447/167397270-0bf64dca-ba00-40be-b5f4-2fcc2016fae2.png)


## 🛠 User Journey (UML diagram)
**You may need to zoom in :wink:**

![UML Diagram](https://user-images.githubusercontent.com/29462447/167288315-074241e4-7fa3-4b40-b0f3-dfd64ab8ddbe.png)

## 🛠 ER diagram

![image](https://user-images.githubusercontent.com/29462447/167288438-81099910-a787-4d66-87a6-faf5c8138c50.png)


## 🛠 Tech Stack

![image](https://user-images.githubusercontent.com/29462447/167288493-56d96ba2-0edc-465d-81bd-72f29ab50f40.png)

## 🎉 MyRec App UI Design
**Designed using [Figma](https://www.figma.com/)**

![image](https://user-images.githubusercontent.com/29462447/167288531-f5f0fa52-ede2-487a-934c-4937a3f2d9a7.png)

| **Userflow (UI design)**  | **from left to right**  |
|---------------------|-----------------------|
| ![image](https://user-images.githubusercontent.com/29462447/167290785-80ea6ef2-facb-413f-8a59-c47e0977c57d.png) | ![image](https://user-images.githubusercontent.com/29462447/167290792-9e8150d5-f68e-435d-b675-16e0f6a93c15.png) |
|  ![image](https://user-images.githubusercontent.com/29462447/167290818-ba03addf-dc37-49c9-a208-302fb429847c.png) | ![image](https://user-images.githubusercontent.com/29462447/167290827-2e41a0c5-eb9d-4c19-a35e-1cf8a2dfc7ad.png) |
|  ![image](https://user-images.githubusercontent.com/29462447/167290843-63fb1546-fdb6-4968-b0cc-4124b900e5ba.png) |  ![image](https://user-images.githubusercontent.com/29462447/167290852-7215ae67-019d-4f3d-9918-79eac66a122d.png) |
|  ![image](https://user-images.githubusercontent.com/29462447/167290859-4cc772a4-4046-4213-96b7-791f4511ed51.png) | ![image](https://user-images.githubusercontent.com/29462447/167290870-9fe1e21b-d469-4722-84bc-0e789b8d71d3.png) |
| ![image](https://user-images.githubusercontent.com/29462447/167290898-015c6f12-b035-4b5d-9ab5-f87417c42c89.png) | ![image](https://user-images.githubusercontent.com/29462447/167290904-a7c8d4ce-9dbc-45e3-afa5-a23494a152c0.png) |
| ![image](https://user-images.githubusercontent.com/29462447/167290922-260dab29-6fdb-4b3f-8500-e0650e32e688.png) | ![image](https://user-images.githubusercontent.com/29462447/167290933-b58b8d39-df8e-444a-bb38-8d331072e3ed.png) |
| ![image](https://user-images.githubusercontent.com/29462447/167290955-9af3194b-46ff-4bf9-b65d-149d049940cd.png) | ![image](https://user-images.githubusercontent.com/29462447/167290962-216383bc-9c41-45f6-9daf-ff46dd0b995b.png) |
| ![image](https://user-images.githubusercontent.com/29462447/167290981-195ee2b9-f5e0-4842-9713-5f6508fced03.png) | ![image](https://user-images.githubusercontent.com/29462447/167290993-91ab9616-1ef5-4204-beca-030b12783e79.png) |


## Wrap up!
![image](https://user-images.githubusercontent.com/29462447/167288659-933afae9-b92f-4e0c-95e5-3672912d3791.png)

## 🔗 Slides can be found [here.](https://github.com/prateekralhan/Architecture-Premier-League---MyRec/blob/main/Architecture%20Premier%20League%20-%20MyRec%20-%20SOLUTION.pdf)

## Legal Notice
© 2022 Swiss Re. All rights reserved. You may use this presentation for private or internal purposes but note that any copyright or other proprietary notices must not be removed. You are not permitted to create any modifications or derivative works of this presentation, or to use it for commercial or other public purposes, without the prior written permission of Swiss Re.
The information and opinions contained in the presentation are provided as at the date of the presentation and may change. Although the information used was taken from reliable sources, Swiss Re does not accept any responsibility for its accuracy or comprehensiveness or its updating. All liability for the accuracy and completeness of the information or for any damage or loss resulting from its use is expressly excluded. 


