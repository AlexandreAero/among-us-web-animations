<h1 align="center">among-us-web-animations</h1>

![GitHub last commit](https://img.shields.io/github/last-commit/alexandreaero/Among-Us-Web-Animations)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/alexandreaero/Among-Us-Web-Animations)
![Lines of code](https://img.shields.io/tokei/lines/github/alexandreaero/Among-Us-Web-Animations)

![tenor](https://user-images.githubusercontent.com/66020831/114184307-fa3c1700-9944-11eb-9d0f-2dfa4d5317df.gif)

### Some little Among Us "easter egg" animations to add to your website

## Screenshot 
![image](https://user-images.githubusercontent.com/66020831/113479556-1563de00-9490-11eb-92fe-ac680ecac059.png)

## Usage
If you want to add this easter egg to your website, follow the instructions:

1. Style sheet reference
```html
<link rel="stylesheet" href="style.css">
```  

2. In body, image div
```html
<div class="amongus-img-1" onmousedown=sound.play()>
     <img src="https://wonder-day.com/wp-content/uploads/2020/10/wonder-day-among-us-21.png" width="250" height="250"> 
</div>
```        

3. Sound script
```html
<script>
     const sound = new Audio();
     sound.src = "amogus.mp3";
</script>
```
