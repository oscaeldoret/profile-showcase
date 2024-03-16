## Welcome to the Profile Showcase Repository! <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/oscaeldoret/test-demo?style=social&logo=github&logoColor=orange">

This repository is designed for beginners and students from Moi University, who want to make their first open-source contribution. By contributing to this repository, you can add your profile image and data, which will be displayed on the README page once your PR is approved.

## Prerequisites

To contribute to this project, you need to have:

- A GitHub account
- A code editor of your choice (we recommend [VS Code])
- A terminal or command-line interface
- Basic knowledge of Git and Markdown


## How to Contribute:

 - **Fork this Repository**: Click on the 'Fork' button at the top right corner of this repository. This will create a copy of this repository in your account.

 - **Clone the Repository**: Now, clone the forked repository to your machine. You can do this using the following command:
   ```
   git clone https://github.com/oscaeldoret/profile-showcase.git

-  **Navigate to the Repository**: Change your directory to the cloned repository:
    
    ```
    cd profile-showcase 

- **Create a new branch for your modifications**:
   ```
   git checkout -b new-user-name-profile`  

    
 -  **Add your Profile Image**:
    
    -   Navigate to `static/images/`.
    -   Add your profile image .Accepted files are png and jpg, should be Square and minimum size 544x544 pixels.
    - Name the file yourname.jpg/png
    -   You can either drag and drop your image into this folder or use the following command:
        
    ``` cp /path-to-your-image.jpg static/images/`


 -  **To resize your image**:
  -  Choose your image,
  -   On your browser go to `resizepic.com`
  - The first page you will get is this "Static/images/First-Step1.png" ![Alt text](/static\ScreenShots\First-Step1.png?raw=true "Resizepic.com First Page")
  - Tap the choose a file option and navigate to the location of your image i.e ![Alt text](static\ScreenShots\Second-Step.png?raw=true "Resizepic.com Second Page")
  - Now type in your desired dimensions of your image in the spaces as shown ![Alt text](static\ScreenShots\Third-Step.png?raw=true "Resizepic.com Last Step")
  - 

        
 -  **Add your Profile Data**:
    
    -   Navigate to `content/profiles/`.
    -   Create a new `.md` file with your name (e.g., `firstname-lastname.md`).
    -   

 - Add your profile data in the following format:
          
           
           `---
           name: 'Your Name'
           image: 'your-image-name.jpg'
           location: 'your home town ' 
           bio: 'A short bio about yourself'
           institution: ' Your college details '
           organisation: ' your company name'
           ---`

        
6.  **Commit and Push**:
    

    
    `git add .
    git commit -m "Added <your-name> profile"
    git push origin master` 
    
7.  **Create a Pull Request (PR)**:
    
    -   Go to your repository on GitHub.
    -   Click on the 'Compare & pull request' button.
    -   Review your changes and submit the pull request.
    
    
    
8.  **Wait for PR Review**: Once your PR is submitted, it will be reviewed. If everything looks good, your PR will be merged, and your profile will be displayed on the README page!

| ![Mathew Kamau](static/images/mathewkamau.jpg) | ![George Bush](static/images/bush.jpg) | ![John Otieno](static/images/john-otienoh.jpg) | ![Supriyo Saha](static/images/supriyo.jpg) |
|---|---|---|---|
| **Mathew Kamau**<br>Constantly exploring the boundaries of technology and imagination. | **George Bush**<br>A passionate software engineer trying to create a dent through technology. | **Sayak Mukherjee**<br>Engineering Student and a passionate developer. | **Supriyo Saha**<br>An average nerd who loves to mess around with inspect elements. |
