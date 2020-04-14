# CSS final Assignment using the alternate template provided.

The purpose of this project was to style a site that is used as a ToDo list for people looking to keep better organized.

## Layout

1. I used a two column layout for the site with flex box and a 2 column layout on the ToDo list using grid

For the main content I used row reverse to put the ToDo list at the left side as it is the main content of the site.

```css
main {
    display: flex;
    flex-direction: row-reverse;
}
```
For the ToDO list I used grid with a gap of 1px on all sides of the list items. (sometimes changed to 10px on the left and right when there is room) A repeating pattern of 2 columns with each column taking 50% of the available space.
```css
#toDoList {
    display: grid;
    grid-gap: 1px;
    grid-template-columns: repeat(2, 1fr);
}
```

1. The site is kept smaller as its primary use is for quick lits additions and removals to stay on top of tasks.

1. You do not want to be looking around a 1400px or larger site to find what you need when you just want to check "laundry" off your list. So most of the content was kept under 1000px with the main focus of the list taking up much less.