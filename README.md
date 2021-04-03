# Among-Us-Web-Animations
 
### Some little Among Us "easter egg" animations to add to your webiste

## Screenshots 
![image](https://user-images.githubusercontent.com/66020831/113479556-1563de00-9490-11eb-92fe-ac680ecac059.png)

## Framework 
Made with Visual Studio Code, HTML and CSS

## How to use 
If you want to add this easter egg to your website, follow instructions :

<ins>Style sheet reference :</ins>   
```
<link rel="stylesheet" href="animation.css">
```  

<ins>In body, image div :</ins>   
```
<div class="amongusimg" onmousedown=sound.play()>
     <img src="https://wonder-day.com/wp-content/uploads/2020/10/wonder-day-among-us-21.png" width="250" height="250"> 
</div>
```        

</ins>Sound script :</ins> 
```
<script>
     var sound = new Audio();
     sound.src = "amogus.mp3";
</script>
```
