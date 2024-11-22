# RoomPlay

## folder structure
```
    RoomPlay/
    ├── client/         # Frontend (React)
    ├── server/         # Backend (Node.js)
    ├── firebase/       # Firebase setup
    ├── .gitignore      # Add files to exclude from Git
    ├── package.json    # Main package file for managing scripts and dependencies
```

## Steps :
1- ```
        cd Roomplay
        npm init -y
        npx creat-react-app client
    ```

2- 
```
        mkdir server
        cd server
        npm init -y
        npm install express socket.io cors
```
3-  ```cd ..
    npm install concurrently nodemon
    ```

4- ```
    npm install firebase
    ```

3- Create the firebase/ folder for firebase configuration(for now leave it)