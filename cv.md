# Darya Nebogina

## Contact information
* Phone: +7 950 757 6306
* GitHub: [darianebogina](https://github.com/darianebogina)
* Discord: daria_nebogina

## About me
I graduated from Voronezh State University with a degree in mathematics and computer science in 2024. I'm currently pursuing a Master's degree in Information Systems and Technology.  
My goal is to find an interesting job in IT sphere. I'm passionate about frontend development with a goal to contribute to team-driven projects and continuously expand my technical knowledge

## Skills
* JavaScript
* HTML, CSS
* Git
* React

## Code example
```javascript
function cakes(recipe, available) {
  let keysRecipe = Object.keys(recipe);
  let keysAvailable = Object.keys(available);
  let cakes = [];
  for (i = 0; i < keysRecipe.length; i += 1) {
    if (!keysAvailable.includes(keysRecipe[i])) {
      return 0;
    }
    else {
      if (recipe[keysRecipe[i]] <= available[keysRecipe[i]]) {
        cakes.push(available[keysRecipe[i]] / recipe[keysRecipe[i]]);
      }
      else {
        return 0;
      }
    }
  }
  return Math.floor(Math.min(...cakes));
}
```

## Work experience
* Autumn 2024  
RSSchool Progect: [Christmas Shop](https://rolling-scopes-school.github.io/darianebogina-JSFE2024Q4/christmas-shop/main.html)   
Designed and built two main pages (homepage and gift listing page) from scratch usingHTML5, CSS, and JavaScript.


## Education
* Master's Degree, Voronezh State University – (2024 – Present)  
Information Systems and Technologies

* Bachelor's Degree, Voronezh State University – (2020 – 2024)  
Mathematics and Computer Science

## Languages
* English A2-B1