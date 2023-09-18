#Report

## Feature Hunt

### Introduction

Put an end to the loss of valuable ideas and suggestions. Take charge of gathering, evaluating, and structuring feedback and feature proposals within your product's feedback platform to enhance your decision-making regarding product development.

Feature Hunt offers the perfect solution for this purpose. It empowers users to submit, endorse, and engage in dialogues concerning feature requests, while product administrators can efficiently categorize and prioritize these inputs to bolster their product development choices.

Technologies that the current project uses are Python, React, JavaScript, Flask, MongoDB, HTML, CSS, and Docker.

### Process Followed and difficulties faced:

- Git clone the Repository using the command: git clone https://github.com/Ashnayak/feature-hunt.git
- Run the following Commands :
    - **cd feature-hunt** 
    This command will allow you to move to the newly cloned working directory.
    
    - **npm install**
    This command will install all the React and nodeJs dependencies which will help run the program.
        
        Difficulties and Errors:
        
        1. Deprecated Dependencies will cause errors.
        
        Solution:
        
        1. For MacOS you need to install HomeBrew. This will enable you to run react and nodeJs dependencies.
        2. Now, run **npm install -force** to install all the deprecated libraries.
        3. After this still there will be a few errors. To resolve them run **npm audit fix -force.**
        
    - **pip install -r backend/requirements.txt**
        
        This command will allow you to install all the backend python dependencies. 
        Difficulties and Errors:
        
        1. Deprecated Dependencies will cause errors.
        
        Solution:
        
        1. For MacOS you need to install HomeBrew. This will enable you to run python and install all the related dependencies in a new environment without affecting the existing configurations.
        2. Now, run **pip install -r backend/requirements.txt -force** to install all the deprecated libraries.
        
    - **yarn start**
        
        Runs the frontend React app in the development mode.
        Open [http://localhost:3000](http://localhost:3000/) to view it in the browser.
        
    - **yarn start-api**
        
        Runs the Flask Backend of the app in development mode.
        
- Connecting Database
    
    Mongo Cloud has been used in this project. To access it:
    
    1. Create a new account on Mongo Cloud Atlas : https://www.mongodb.com/ 
    2. Make a Database and grab the credentials by clicking on connect
    3. Change the connection string in the following files: 
    **docker-compose.yml: DB=YOUR CONNECTION STRING
    start_server.sh: export DB=YOUR CONNECTION STRING**
    4. To use the MongoDB Shell follow the steps on : https://www.mongodb.com/docs/mongodb-shell/

### Future Scope:

Following are the proposed changes to improve the project:

- Comprehensive Installation Documentation: The aim is to thoroughly document the installation process, encompassing potential errors that may arise and their corresponding solutions. This will streamline the setup process, making it more user-friendly.
- Library Modernization: To keep the project up to date, we propose upgrading deprecated libraries with currently maintained counterparts. This proactive approach ensures long-term sustainability and compatibility.
- Dependency Adjustment: To mitigate issues stemming from deprecated libraries, the project will transition away from Node.js and React in favor of HTML, CSS, and Flask. This shift aims to enhance stability and reduce potential roadblocks.
- UI/UX Enhancement: Focusing on improving the web application's User Interface (UI) and User Experience (UX) is crucial. This will result in a more intuitive and user-friendly interface, facilitating a better grasp of the application's functionality.
- Backend Library Updates: To prevent compatibility concerns, we plan to upgrade the existing backend libraries to their latest versions, ensuring seamless operation.

These future endeavors are poised to refine the project's performance, accessibility, and overall user satisfaction, ultimately delivering a more robust and reliable solution.

### Conclusion

In conclusion, the project aims to address the critical challenge of utilizing valuable feedback and feature suggestions effectively. By implementing Feature Hunt, we seek yo provided a solution that empowers users to actively participate in the improvement of a product while enabling product administrators to make informed decisions about its development.

Looking ahead, we have outlined an ambitious roadmap for future improvements. These enhancements encompass comprehensive installation documentation, library modernization, dependency adjustment, UI/UX enhancement, and backend library updates. These strategic steps will not only improve the project's performance and stability but also enhance user satisfaction.

In summary, our project aspires to bridge the gap between user feedback and product development, and with the proposed improvements, we are committed to delivering an even more robust and user-friendly solution in the future. The journey to innovation and excellence continues.
