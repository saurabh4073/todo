# Todo List App

Welcome to Todo List App! This tool helps you keep track of tasks and items to buy, allowing you to generate lists that can be marked as done or removed. You can share lists with other users, granting read-only or modification rights. A special feature of the app is the ability to create a list using AI by simply writing what you want to do in the list name, making task management easier and more efficient.

## Installation
1. Clone the repository:
``` 
    git clone https://github.com/saurabh4073/todo.git
```

2. Required Changes: <br>
    1. Update the database credentials in db.js file.
    2. In client folder add .env file and add OpenAI key for it ass follows-
    ```
    REACT_APP_OPEN_API_KEY = "<Your key>"
    ```  
    3. Run each migration file-
    ```
    node migration_01.js
    ```
    ```
    node migration_02.js
    ```
    and so on.

3. Install Dependencies:<br>
```
    npm install
```
open in browser the following link:
```
    http://localhost:3000
```

## Contributions
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/3. AmazingFeature)
4. Commit your Changes (git commit -m 'Add some AmazingFeature')
5. Push to the Branch (git push origin feature/AmazingFeature)
6. Open a Pull Request

## Working with Screenshots

Login Page-
![Screenshot 2024-05-07 222318](https://github.com/saurabh4073/todo/assets/49804941/feafe0d9-94bb-4ebf-86d2-18d960ae3b40)

After Login for Jill User-
![Screenshot 2024-05-07 222333](https://github.com/saurabh4073/todo/assets/49804941/720fad12-2d09-412e-b05c-e6db752cd90b)

Add List for Jill-
![Screenshot 2024-05-07 222349](https://github.com/saurabh4073/todo/assets/49804941/b25895b6-bf44-4398-bd0b-f37096b57665)

Add Normal List for Jill-
![Screenshot 2024-05-07 222408](https://github.com/saurabh4073/todo/assets/49804941/8b39adc9-afd1-43bf-bbb2-73b460229cee)

Added tasks for jill-
![Screenshot 2024-05-07 222434](https://github.com/saurabh4073/todo/assets/49804941/295a7a01-a81e-4ee3-85d1-4d7ae125406f)

Completed A task-
![Screenshot 2024-05-07 222446](https://github.com/saurabh4073/todo/assets/49804941/9e061333-f932-4c9a-b2d6-60fbc5a41700)

Marked a task for deletion-
![Screenshot 2024-05-07 222458](https://github.com/saurabh4073/todo/assets/49804941/b1052996-61ec-4e76-b706-1f966b808c61)

Add List for Jill-
![Screenshot 2024-05-07 222514](https://github.com/saurabh4073/todo/assets/49804941/f876bddb-1dfe-4cbd-aa48-b7806ef2f21f)

Add List using AI-
![Screenshot 2024-05-07 222530](https://github.com/saurabh4073/todo/assets/49804941/3ec5a0fc-8370-46d0-ada2-545003cbb7ef)

Share list with Jack in read mode-
![Screenshot 2024-05-07 222554](https://github.com/saurabh4073/todo/assets/49804941/c1d777b6-6cdc-4007-b743-101bc35f772f)

Share List with jack in modify mode-
![Screenshot 2024-05-07 222614](https://github.com/saurabh4073/todo/assets/49804941/4385ec7e-8654-4c91-a70a-d876661ec0ca)

After login for Jack-
![Screenshot 2024-05-07 222645](https://github.com/saurabh4073/todo/assets/49804941/5bb487b0-a311-46e9-8989-ad916899b852)

## Acknowledgments
This project was done under the guidance of Prof. Sthapit from Arizona state University

