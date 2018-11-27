![CF](http://i.imgur.com/7v5ASc8.png) LAB 29
=================================================

## Component Composition

### Katherine Smith

### Links and Resources
* [Assignment 1](https://codesandbox.io/s/6lj08y725r)
* [Assignment 2](https://codesandbox.io/s/24v5r87xpn)

---
### Assignment 1
#### App Component
- Passes `<span>` tags to Stuff component
- Renders Stuff component

#### Stuff Component
- Passes `<span>` tags to Things component using children property
- Renders Things component

#### Things Component
- Renders `<span>` tags using children property

#### UML
<img src="./lab-29-assignment-1.jpg" alt="lab-29-assignment-1.jpg" width="500px">

---
### Assignment 2
#### App Component
- Passes `<span>` tags to FunctionalStuff component
- Renders FunctionalStuffStuff component
- Passes `<span>` tags to ClassStuff component
- Renders ClassStuff component

#### FunctionalStuff Component
- Passes `<span>` tags to FunctionalThings component using children property
- Renders FunctionalThings component

#### FunctionalThings Component
- Renders `<span>` tags using children property

#### ClassStuff Component
- Passes `<span>` tags to ClassThings component using children property
- Renders ClassThings component

#### ClassThings Component
- Renders `<span>` tags using children property

#### UML
<img src="./lab-29-assignment-2.jpg" alt="lab-29-assignment-2.jpg" width="500px">