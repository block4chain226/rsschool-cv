## [**Cv**](https://retouch226.github.io/rsschool-cv/cv)

---

# Ivan Paias

---

## Junior Frontend Developer

---

## Contact information:

**Phone:** +38 096 1657493
**E-mail:** retouch226@gmail.com
**Telegram:** @oboloncss
[**Instagram**](https://www.instagram.com/iv_retouch/)

---

## Briefly About Myself:

I finished a computer technologies facult. I learned C# and .net technologies. After university I am having starting my career as high-end retoucher I learned most useful retouching techniques and got a first work in 2 weeks. I am working as a retoucher by nowadays but was interesting in programming from university. My profession give me a lot of freedom and extra free time that I using to study front-end development. I love to programming, create something new by my hands, resolve a problems, then optimising it for better performance and see the result. I like to invent a good program architecture. I am always trying to learn something new to gain new skills.

## Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code, Ms Visual Studio
- Adobe Photoshop, LightRoom

---

## Code example

**Adding dynamic trash button to each film on Film site**

```
function addTrash(item) {
    const ulWatchedFilms = document.querySelector("#watched-films");
    const trashButton = document.createElement("button");
    trashButton.classList = ".trash";
    var lidelete;
    const li = ulWatchedFilms.querySelectorAll("li")
    const itemPoints = item + "...";
    console.log(itemPoints);
    li.forEach((itemLi) => {
      if (itemLi.textContent == item || itemLi.textContent.length > 21) {
        lidelete = itemLi;
        itemLi.parentNode.append(trashButton);
      }
    });
    trashButton.addEventListener("click", (e) => {
      e.preventDefault();
      const i = movieDB.movies.indexOf(item);
      movieDB.movies.splice(i, 1);
      console.log(movieDB.movies);
      trashButton.parentNode.remove();
    });
  }
```

---

## Languages

- English B1
- Ukrainian - Native
- Russian - Intermediate
