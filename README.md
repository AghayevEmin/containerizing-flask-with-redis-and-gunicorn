for starting the flask application run 
```
docker-compose up -d
```
-d means detached

the app runs on port 127.0.0.1:5000

there're 2 ways to check if the app is working 
1. run ``` curl 127.0.0.1:5000 ```
2. go to your favorite browser and type ``` localhost:5000 ``` or ``` 127.0.0.1:5000 ``` in search bar.
if the app works properly visitor.html will be shown and counter will add +1 at each page refresh  

![image](https://user-images.githubusercontent.com/51789521/135723355-a5db791e-82e6-48d4-8bcb-fa6423211c75.png)
