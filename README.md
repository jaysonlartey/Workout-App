<div align="center">

# IWorkout App


### App Logo
![App Logo](https://github.com/user-attachments/assets/03ab2f28-cb50-468c-8c80-6343fed77285)

---

## Project Overview
The **IWorkout** app is a workout tracking and planning application designed to help users log their workouts and track progress over time. It includes features such as **login/signup**, a **home page** with user data, a **workout planner** to log and track workouts, and the ability to **view past workouts** in a weekly format.

---

## Features

### **Login/Signup**
- **Login Page**: Users are required to log in to access the app.
- **Sign In Page**: New users can sign up to create an account.
- **Backend Integration**: When users log in or sign up, the app communicates with the backend to authenticate users and store their data.

**Screenshots**:
![Login Screen](https://github.com/user-attachments/assets/1f4dfdcc-5129-4329-9025-6110959a5ebe)
![Sign In Screen](https://github.com/user-attachments/assets/23c7436d-aac1-4f9c-95f9-32d9db65d433)

### **Home Page**
- Once logged in, users are redirected to the **Home Page** which displays user information and has buttons to access the workout planner and workout viewer pages.

**Screenshot**:
![Home Page](https://github.com/user-attachments/assets/7970e951-16fe-4b1d-8b63-a786698ec4ef)

### **Workout Planner**
- Users can log workouts by selecting the date, naming the workout, and entering the number of sets and reps. The workout is then sent to the backend via a **POST** request to store in the database.

**Screenshot**:
![Workout Planner](https://github.com/user-attachments/assets/32e65ffb-5071-4e3b-8af6-cc3d99773157)

### **View Workouts**
- Users can view their logged workouts in a weekly format, with options to edit or delete workout details.

**Screenshot**:
![View Workouts](https://github.com/user-attachments/assets/a2b6c7ae-bcca-44f8-80e2-2fee1e9b8e12)

---

## Technologies Used

- **Frontend, Backend, Authentication**: 
  - Kotlin

- **API Integration**:
  - Azure OpenAI Service for AI integration

---

## Development Tasks

### **High-Priority Tasks**
1. **Creating/Using the Database**  
   - **Priority**: High  
   - **Estimated Time**: 0.5 - 1 hrs

2. **Creating the Login/Signup Pages**  
   - **Priority**: Medium  
   - **Estimated Time**: 1 - 2 hrs

3. **Creating the Home Page**  
   - **Priority**: Medium  
   - **Estimated Time**: 1 - 2 hrs

4. **Creating the Add Workout Page**  
   - **Priority**: Medium  
   - **Estimated Time**: 1 - 2 hrs

5. **Creating the View Workout Page**  
   - **Priority**: Medium  
   - **Estimated Time**: 1 - 2 hrs

### **Low-Priority Tasks**
1. **Implementing/Using the AI API**  
   - **Priority**: Low  
   - **Estimated Time**: 2 - 3 hrs

2. **Implementing User Options**  
   - **Priority**: Low  
   - **Estimated Time**: 1.5 - 2.5 hrs

---

## Database Design

### **Conceptual Design of Database**
**Screenshot**:  
![Conceptual Database Design](https://github.com/user-attachments/assets/0a9df2e4-446b-4464-867a-f403c27dc1e0)

### **Physical Design of Database**
**Screenshot**:  
![Physical Database Design](https://github.com/user-attachments/assets/22c27cb9-5754-4831-911d-3398e4535451)

---

## Layout and Design

### **App Layout**
**Screenshot**:  
![App Layout](https://github.com/user-attachments/assets/065cdb88-55aa-4400-bb9c-557b08fbb0aa)

- [Figma Layout Design](https://www.figma.com/design/3mzdCZkvPArN40DGfZJkuE/Milestone-2-proposal?node-id=0-1&node-type=canvas&t=8MJQu4OmHBfcHCTv-0)

---

## Future Enhancements

- Integration of **payment processing systems** (e.g., Stripe, PayPal) for premium users.
- **Social features** like sharing workout progress and achievements with friends.
- **Workout recommendations** using AI for personalized workout plans.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
Feel free to reach out for collaboration opportunities or feedback.

---

**GitHub Repository**:  
- [IWorkout Frontend Repository](https://github.com/yourusername/IWorkout-Frontend)
- [IWorkout Backend Repository](https://github.com/yourusername/IWorkout-Backend)
