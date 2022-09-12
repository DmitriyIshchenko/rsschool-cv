# Dmitriy Ishcnenko

## Contacts

* **Email:** to.dmitriy.ishchenko@gmail.com
* **Telegram:** https://t.me/DmitryIshchenko
* **Discord:** dmitriy.ishchenko#9612

## About me

I love seeing the results of my work in the form of beautiful websites, so I decided to become a frontend developer. I hope to work on some big cool projects one day!

## Skills

* JavaScript
* HTML
* CSS/SASS
* Git

## Code example

```
function formatDuration (seconds) {
  if(seconds === 0) return 'now';

  const intervals = {
    year: 60 * 60 * 24 * 365,
    day: 60 * 60 * 24,
    hour: 60 * 60,
    minute: 60,
    second: 1
  }
  const res = Object.entries(intervals).map(([name, duration]) => {
    const value = Math.floor(seconds / duration);
    seconds -= value * duration;
    return value > 0 ? `${value} ${value > 1 ? name+'s': name}` : '';
  })
  .filter(str => str);
  
  if(res.length === 1) return res[0];
  if(res.length === 2) return res.join(' and ');
  return `${res.slice(0, -1).join(', ')} and ${res.slice(-1)}`
}
```

## Experience

I have no commercial experience, but here are some of my learning projects:

* Todo list: https://to-do-list-ishchenko.netlify.app/

## Education

* Voronezh State University, Faculty of Computer Sciences
* [The Complete JavaScript Course by Jonas Schmedtmann](https://www.udemy.com/course/the-complete-javascript-course/)
* [Build Responsive Real-World Websites with HTML and CSS by Jonas Schmedtmann](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/)

## Languages

* English - A2
* Russian - Native
* Ukranian - Native