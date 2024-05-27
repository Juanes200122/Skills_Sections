# Skills_Sections ⭐⭐⭐⭐☆

![Banner](image/cap-counter.PNG)
<p align="center" style="color: white;">
    <img src="https://profile-counter.glitch.me/Juanes200122/count.svg" />
</p>


<p>
    <a href="https://www.linkedin.com/in/juan-estaban-ar%C3%A9valo-056bab240/" target="_blank" rel="Linkedin">
      <img src="https://img.shields.io/badge/-@JuanEsteban-0077B5?style=flat-square&amp;labelColor=0077B5&amp;logo=LinkedIn&amp;link=https://www.linkedin.com/in/juan-estaban-ar%C3%A9valo-056bab240/" alt="LinkedIn Badge">
    </a> 
    <a href="https://www.instagram.com/jeacsi.official_022?igsh=MWJ6MHRwcnhoZXVxbQ==" target="_blank" rel="Instagram">
      <img src="https://img.shields.io/badge/-@jeacsi.official_022-purple?style=flat&logo=instagram&logoColor=white&link=https://www.instagram.com/jeacsi.official_022?igsh=MWJ6MHRwcnhoZXVxbQ==" alt="Instagram Badge">
    </a>
</p>
<p>Se a desarrollado una animación de contadores utilizando JavaScript puro, que se ejecuta al cargar la página. Esta animación permite incrementar los valores de los contadores de forma gradual hasta alcanzar un objetivo predefinido, ofreciendo una experiencia visual atractiva y dinámica.</p>

<p>Visualizar trabajo en 
    <a href="https://codepen.io/Juan-Esteban-Ar-valo/pen/rNgMrOP" target="_blank">
        <img src="https://img.shields.io/badge/-CodePen-000000?style=flat&logo=codepen" alt="CodePen">
    </a>
</p>


```bash
    git clone https://github.com/Juanes200122/Skills_Sections.git
    cd Skills_Sections
```
<div align="right">
    
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
![CodePen](https://img.shields.io/badge/-CodePen-000000?style=flat&logo=codepen)

</div>

## <b> Funcionalidad</b>
<img align="right" src="image/cap-countainer.gif" width="400"/>

```JS
document.addEventListener('DOMContentLoaded', () => {
    const counters = document.querySelectorAll('.counter h3');
    const speed = 1200;

    counters.forEach(counter => {
        const updateCount = () => {
            const target = +counter.getAttribute('data-target');
            const count = +counter.innerText;
            const increment = target / speed;

            if (count < target) {
                counter.innerText = Math.ceil(count + increment);
                setTimeout(updateCount, 1);
            } else {
                counter.innerText = target;
            }
        };

        updateCount();
    });
});
```

</br>

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width ="25"><b> Skills</b>
  - 💻 &nbsp;
    ![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)
  - 🌐 &nbsp;
    ![HTML5](https://img.shields.io/badge/-HTML5-333333?style=flat&logo=HTML5)
    ![CSS](https://img.shields.io/badge/-CSS-333333?style=flat&logo=CSS3&logoColor=1572B6)
