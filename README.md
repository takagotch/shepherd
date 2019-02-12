### shepherd
---
https://github.com/shipshapecode/shepherd

```
npm install shepherd.js --save
yarn add shepherd.js
```

```js
let tour = new Shepherd.Tour({
  defaultStepOptions: {
    classes: 'shadow-md bg-purple-dark',
    scrollTo: true
  }
});

tour.addStep('example', {
  title: 'Example Shepherd',
  text: 'Creating a Shepherd is easy too! Just create ...',
  attachTo: '.hero-example bottom',
  advanceOn: '.docs-link click'
});

tour.start();
```

```
```

