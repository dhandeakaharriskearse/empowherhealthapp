# Baddies in Tech Women's Rights Buildathon 2024 - *EmpowHer Health App*

Submitted by:
* **Girsea Martinez** - Project Manager
* **Shalia Johnson** - UI/UX Designer
* **Tyanna Shaye** - Marketing Lead
* **Toni-Lee Maitland** - Frontend Developer
* **Dhandeaka Harris-Kearse** - Backend Developer

**EmpowHer Health** is an app to empower women to take control of their reproductive health through syncing nutritional and fitness habits to their monthly cycles. EmpowHer will feature tools to allow users to log their meals, workouts, cycle, and any symptoms. Additionally, it will provide suggestions tailored to each users’ menstrual cycles.
EmpowHer will also feature an AI component that allows the users to ask specific questions related to their reproductive health. This component will empower users to prepare effectively for doctors’ appointments allowing them to better advocate for themselves. Our goal is to provide women with the ultimate toolkit to help understand and optimize their reproductive health.

Time spent: **X** hours spent in total

## Key Features

The following functionality is completed:

- [ ] **Menstrual Cycle / Pregnancy tracker**
- [X] **Calendar**
- [ ] **Nutrition Diary**
- [X] **GPT feature - provides insight on health related questions**

The following **stretch goal** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

The following **stretch goal** features are not implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Technical Documentation

### Tools and Technologies:
- **Programming Languages**: Kotlin, JavaScript
- **Frontend Framework**: React Native
- **Backend Framework**: Ktor
- **Database**: File-based storage (for demonstration purposes)
- **HTTP Client**: OkHttp
- **Testing Framework**: Jest (for React Native), JUnit (for Kotlin)
- **Deployment**: Manual deployment to local or cloud servers

### Methodology:
We followed an Agile development methodology with iterations lasting two weeks each. During each iteration, we planned the features to be implemented, developed them, conducted testing, and reviewed the work completed. Daily stand-up meetings were held to discuss progress, obstacles, and plan the day's work. Continuous integration and continuous deployment (CI/CD) pipelines were set up to automate the build, test, and deployment process.

### Architecture:
The system follows a client-server architecture, with the React Native frontend communicating with the Kotlin backend via HTTP requests. The frontend handles the user interface and user interactions, while the backend manages data storage, business logic, and external integrations. No specific diagrams are provided, but the architecture can be visualized as a client-server model, with communication flowing between the frontend and backend components.

### Challenges and Bugs:
- **Challenges**: Integrating React Native with Kotlin backend posed initial challenges due to differences in language and ecosystem. Handling asynchronous communication between frontend and backend required careful coordination.
- **Backend Implementation**: Due to time constraints, the backend could not be fully implemented during the initial phase of the project. This delayed the development process and impacted the overall functionality of the application.
- **Bug Fixing**: Despite efforts to address bugs and issues during development, some critical bugs remained unresolved due to the incomplete backend implementation. These bugs affected data synchronization and API request handling.
- **Future Plans**: The backend will be fully implemented in the final project iteration to address the existing challenges and bugs. This will involve completing the CRUD operations, enhancing data validation, and improving error handling to ensure robust functionality.

### Testing:
- **Unit Testing**: Both frontend (React Native components and utilities) and backend (Kotlin classes and functions) were extensively unit tested using Jest and JUnit, respectively.
- **Integration Testing**: Integration testing, which verifies the interaction between frontend and backend components, has not yet been completed due to time constraints. This phase of testing will be prioritized in the final project iteration to ensure proper data exchange and functionality across the entire system.

### Deployment:
- The project was deployed manually to local development environments for testing and to cloud servers (e.g., AWS, Google Cloud Platform) for production.
- Deployment involved packaging the frontend and backend components separately and configuring the necessary server environment (e.g., setting up databases, configuring networking).
- No deployment automation or scripts were used in this project, but CI/CD pipelines could be implemented for automated deployment in a production environment.

### Performance:
- Performance metrics such as response times, scalability, and resource utilization were not extensively measured in this project due to its small scale and limited deployment.
- However, efforts were made to optimize code and minimize unnecessary data transfers between frontend and backend to ensure efficient operation.

### Security:
- Basic security measures were implemented to protect user data and prevent unauthorized access. These measures included input validation, secure communication protocols (HTTPS), and authentication/authorization mechanisms (JWT, OAuth) where applicable.

## Notes

### Bridging the Frontend and the Backend
[React Native Bridge with Kotlin](https://proandroiddev.com/react-native-bridge-with-kotlin-b2afde2f70b)
[Writing a Native Module for React Native Using Kotlin](https://www.callstack.com/blog/writing-a-native-module-for-react-native-using-kotlin)
