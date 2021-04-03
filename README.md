# Among-Us-Web-Animations

![GitHub last commit](https://img.shields.io/github/last-commit/alexandreaero/Among-Us-Web-Animations)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/alexandreaero/Among-Us-Web-Animations)
![Lines of code](https://img.shields.io/tokei/lines/github/alexandreaero/Among-Us-Web-Animations)

### Some little Among Us "easter egg" animations to add to your webiste

## Screenshot 
![image](https://user-images.githubusercontent.com/66020831/113479556-1563de00-9490-11eb-92fe-ac680ecac059.png)

## Framework 
Made with ``Visual Studio Code``, ``HTML`` and ``CSS``

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

<ins>Sound script :</ins> 
```
<script>
     var sound = new Audio();
     sound.src = "amogus.mp3";
</script>
```

But if you just want to test it out without adding it to your website, head to this [file](https://raw.githubusercontent.com/AlexandreAero/Among-Us-Web-Animations/main/animation.html) with this other [file](https://github.com/AlexandreAero/Among-Us-Web-Animations/blob/main/animation.css)
