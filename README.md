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
   git clone https://github.com/oscaeldoret/test-demo.git`

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
