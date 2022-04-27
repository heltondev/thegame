## The Game

### **Instructions**
If you are using Linux OS, go to **_package.json_** file and remove SET from the start under scripts
```JSON
"scripts": {
    "start": "HTTPS=true && react-scripts start",
```
Otherwise, if are using Windows include SET HTTPS by replace "start" for the following code

```JSON
"scripts": {
    "start": "SET HTTPS=true && react-scripts start",
```

### **Get Started**

1. Run `npm i` from the root folder of the project
2. Run `npm run start`
3. Navigate to [http://localhost:3000](http://localhost:3000)