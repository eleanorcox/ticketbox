# Ticketbox: A Vue app for a ticket-buying website

This is project to learn the basics of Vue. The code follows the 'Learn Vue.js' course on Codecademy, and is split into three lessons: 'Vue Data', 'Vue Forms' and 'Styling Elements with Vue'. Below are the end-of-lesson reviews, explaining what was covered in each lesson.

## Vue Data
In this lesson, we learned four different techniques for displaying and updating dynamic data in our Vue apps. Here’s a brief recap of the Vue app options object properties we covered and the use cases for each:
- `data` - used for storing known dynamic values
- `computed` - used for computing dynamic values based on known dynamic values - can additionally specify a setter by specifying get and set functions - the setter will update other dynamic values when the computed value changes
- `watch` - used for performing functionality when a specified dynamic value changes
- `methods` - used for storing instance methods to be used throughout the app

## Vue Forms
Congratulations, you now know how to bind HTML forms to Vue data and listen to events in Vue! Let’s review the major takeaways from this lesson:
- Form fields can be bound to Vue data using the `v-model` directive - how `v-model` is used depends on the type of field it is being added to
- Form event handlers can be added using `v-on:submit` and `v-on:reset`. Alternative shorthand for these is `@submit` and `@reset`.
- Modifiers can be used to add functionality to directives - most importantly preventing page reload on form submission using `v-on:submit.prevent` and cleaning up form field values using `.number` and `.trim`. We can also use `.lazy`, which only updates data values when `change` events are triggered (e.g. a user clicks away from a form field, instead of after every keystroke)
- Form validation can be implemented by setting the value of the `disabled` attribute on a `<button>` to the value of a computed property using `v-bind`

## Styling Elements with Vue
Congratulations on completing this lesson! In this lesson, we covered a number of different techniques for dynamically styling Vue elements.

We learned how to dynamically add inline styles using `v-bind:style` with a style object or an array of style objects. We then learned how to dynamically add classes using `v-bind:class` with a class object or an array of class objects and class name strings.

It may seem like any one of these techniques would be sufficient for dynamically styling a front-end app — and that’s true! As you continue learning about Vue, you will see advantages and use cases for each technique.

The important thing to take away at this stage in your learning journey is that you should aim to use the technique that keeps your code the most readable and leaves your app with the least repetitive code.