# React Notes  
## Creating First React App  
>npm create vite@latest
>
![image](https://github.com/user-attachments/assets/2700cc00-a83a-4be3-b9e8-6ad41adc9d2c)  
### Select Framework(in our case React)  
![image](https://github.com/user-attachments/assets/6fbbfb92-66de-4eda-94ab-b62872432fc3)  
### Here are last few commands to start our project:  
`cd my-react-app`  

`npm install`  

`npm run dev`  

## Creating A Card Component  
Firstly, just create a new file/Component (e.g. Card.jsx).    //jsx means JavaScript Xml which allows us to use js variables inside html tags. 
React component names must always begin with a capital letter.  

![image](https://github.com/user-attachments/assets/695f0518-42cc-4ff3-909c-8d48e3766b24)  

Now create a function with the same name as Component name:  

![image](https://github.com/user-attachments/assets/52eef825-59f8-46a8-9f68-3a9eaa97f330)  

## Style React Components With CSS  

### 1. External  

> Directly in index.css file:
> 

![image](https://github.com/user-attachments/assets/1bfb28d4-890a-407e-842d-ca6f8d0d59ba)
![image](https://github.com/user-attachments/assets/22c8c235-44f4-49d1-ad0f-7d0cbdcca6f6)  

### 2. Modules  

> By Creating css file for each component(e.g. Button.module.css)
>

![image](https://github.com/user-attachments/assets/0ea6262c-d8ee-4e98-afdd-d7e57f08eb5c)
![image](https://github.com/user-attachments/assets/d194db3b-6653-4fda-bab8-04ad509dbdc6)  

### 3. Inline  

> Directly inside .js file
>

![image](https://github.com/user-attachments/assets/897a3f84-b78f-4a5d-907b-d0ffee65fe72)  

## Props  
> Read only properties that are shared between components.
> A parent component can send data to child components.
>
> `<Component key = value>`
>
![image](https://github.com/user-attachments/assets/123ad8db-69df-42a4-9680-e1b939f063c6)  
![image](https://github.com/user-attachments/assets/7b4de3a5-2a40-4c82-a0a7-85cbd25e3d0a)

## Conditional Rendering  
>   Allow us to control whats get rendered in our application based on certain condition(basically if-else)

![image](https://github.com/user-attachments/assets/d1519792-299a-46af-a718-f598e017e7dc)  

This is nothing just conditional statements(if-else)
and can also be written as  

![image](https://github.com/user-attachments/assets/13039c83-6be5-4888-8f27-a4a6e9a4c19f)  

## Render Lists  

![image](https://github.com/user-attachments/assets/87f8ea6f-396b-4d5f-b8e4-fb3b3456fdf3)  

>A list of objects

![image](https://github.com/user-attachments/assets/85dfd542-8151-4dd8-a38e-d9da53ffbc5c)  

>Sort List Items according to the fruits name
>
>`fruits.sort((a, b) => a.name.localeCompare(b.name))`

>Sort List items according to fruits calories
>
>`fruits.sort((a, b) => a.calories - b.calories)`

### Filter fruits under a condition  
![image](https://github.com/user-attachments/assets/aa6f0907-ad5b-4ec0-878d-1c23b80752ff)  

### We can also send this list as props  

![image](https://github.com/user-attachments/assets/0a6473ab-441e-4877-a289-abddcd018a22)  

![image](https://github.com/user-attachments/assets/86c378aa-dff3-4dc9-85d3-fadd5c729407)  


## Click Events  
>An Interaction when a user click on the specific element. 
>We can respond to clicks by passing a callback to the onClick event handler.

![image](https://github.com/user-attachments/assets/10a320e6-c6a5-4a6f-936a-30f229e5ccc8)  

![image](https://github.com/user-attachments/assets/4a417a21-5219-4f84-8b18-42f4281f3e21)

> We can send parameters with callback but we have to wrap this callback with an another function 
>
> because if we don't the callback will execute as the component renders, without clicking the button.

![image](https://github.com/user-attachments/assets/9abb19da-b58d-432c-86c0-517de105e4a7)  


> Event

![image](https://github.com/user-attachments/assets/fe9a4de8-51e1-4afb-a9c1-27269a5c071e)  

![image](https://github.com/user-attachments/assets/034fce0c-f9a1-4538-8652-17e327f79194)  

## React Hooks  

> Special functions that allows functional components to use react features without writing class components.

### useState() hook  
A react hook that allows us to create state variables and a setter function to update its value.  
[name, setName]  

![image](https://github.com/user-attachments/assets/ba90d4fa-bc37-46e3-944f-baa806145c2c)  

## Event Handler  
> Event handler used primarily with form elements. ex. <input>, <textarea>, <radio>, <select>

### onChange event handler  
> Triggers a function every time the value of the input changes.

![image](https://github.com/user-attachments/assets/024a5167-25f7-43c4-b260-dab40450435f)

![image](https://github.com/user-attachments/assets/6b0ce143-5a46-4186-969d-5fa6ee7466bc)  





