# Product Page Deign
Language Uses: HTML, CSS, JAVASCRIPT
## ScreenShots
![img1](https://github.com/user-attachments/assets/702fc873-1a44-40ac-8d0c-b65cea54205d)
![img2](https://github.com/user-attachments/assets/06c2875c-8f25-47d7-9544-27565cd1fa90)
![img3](https://github.com/user-attachments/assets/05f82fc7-02de-4abf-91fe-d2ed56386619)

JavaScript Code For User Interaction 👨‍💻
```javascript
let productimg= document.getElementById("productimg");
let btn= document.getElementsByClassName("btn");

btn[0].onclick = function() {
    productimg.src= "images/image1.png";
    for(bt of btn){
        bt.classList.remove("active");
    }
    this.classList.add("active");
}

btn[1].onclick = function() {
    productimg.src= "images/image2.png";
    for(bt of btn){
        bt.classList.remove("active");
    }
    this.classList.add("active");
}

btn[2].onclick = function() {
    productimg.src= "images/image3.png";
    for(bt of btn){
        bt.classList.remove("active");
    }
    this.classList.add("active");
}
```
## Check Out The Website 👇

Visit The Website🌐 [Product Page Design](https://shayanshahdeveloper.github.io/Project-3-Product-Page-Design/)

## Developed By Shayan Shah
Social media Handles 👉
[Linkdin](https://www.linkedin.com/in/shayan-shah-b31439296/)


