# React Notes  
## Creating First React App  
>npm create vite@latest
>
![image](https://github.com/user-attachments/assets/2700cc00-a83a-4be3-b9e8-6ad41adc9d2c)  
### Select Framework(in our case React)  
![image](https://github.com/user-attachments/assets/6fbbfb92-66de-4eda-94ab-b62872432fc3)  
### Here are last few commands to start our project:  
>cd my-react-app
>
>npm install
>
>npm run dev
>
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

