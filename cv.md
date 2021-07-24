# Evgeny Kovalev
## Contacts
* **[Telegram](https://telegram.me/wwwtyz)**
* **[Email](mailto:wwwtyz@tut.by)**
* **Phone +375259969912**

## About me
* Prone to learn
* Diligent
* Gain experience
* Ability to prioritize
* Good communication skills.
## Skills
* #### Human languages
1. **Russian** - *native
1. **Belorussian** - *native*
1. **English** - **Pre-Intermediate*
* #### Programming languages
1. **HTML** *beginer*
1. **CSS** *beginer*
1. **JavaScript** *beginer*
* #### IDE
1. **VS Code**
* #### Version cotnrol system
1. **Git**
## Code sample
```
function getRandomElement(arr) {
  let randIndex = Math.floor(Math.random() * arr.length);
  return arr[randIndex];
}

let button = document.querySelector('.button');
let phrase = document.querySelector('.phrase');
let advice = document.querySelector('.advice');
let image = document.querySelector('.image');

button.addEventListener('click', function () {
  let randomElement = getRandomElement(phrases);
  smoothly(phrase, 'textContent', randomElement.text)
  smoothly(image, 'src', randomElement.image)

  if (randomElement.text.length > 40) {
    advice.style.fontSize = '33px';
  } else {
    advice.style.fontSize = '42px';
  }
});
for (let i=0;i<=2;i=i+1){
  smoothly(phrase, 'textContent', phrases[i].text);
  smoothly(image, 'src', phrases[i].image)
}
```
## Work Experience
* **RS School** 2021q3 (2021-present time)
* **MIP** *Design engineer watter supply and wastewater treatment systems* (2014-2021)
## Education
* **RS School** 2021q3 (2021-present time)
* [BNTU](https://bntu.by/faculties/fes/deanery) *Faculty of Power Engineering* (2009-2014)
