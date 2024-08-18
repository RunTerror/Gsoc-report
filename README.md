# Beacon (CCExtractor)

## Google Summer of Code '24

- **Name:** Abhishek Bansal
- **Email:** [bansalabhishek7411@gmail.com](mailto:bansalabhishek7411@gmail.com)
- **GitHub Username:** [RunTerror](https://github.com/RunTerror)
- **LinkedIn:** [Abhishek Bansal](https://www.linkedin.com/in/abhishek-bansal-123456789/) 
- **University:** Institute of Engineering and Technology, Lucknow, Uttar Pradesh
- **Organization:** CCExtractor
- **Project Title:** Beacon
- **Project Link:** [Beacon Repository](https://github.com/CCExtractor/beacon)


## Table of Contents

1. [My Project Work](#my-project-work)
2. [Work Track](#work-track)
3. [Personal Note](#personal-note)

## My Project Work

### Auth Screens

Users can authenticate using Google OAuth or via email verification with a four-digit code sent to their email.

<p>
  <img width="200" src="https://github.com/user-attachments/assets/19bb49c0-0346-416e-b28d-1541185552b0" alt="Auth Screen 1">
  <img width="200" src="https://github.com/user-attachments/assets/18a5c323-4929-4c0f-afa0-3c01a62378a4" alt="Auth Screen 2">
  <img width="200" src="https://github.com/user-attachments/assets/030bfb21-d36a-42ff-8926-114ade282fdc" alt="Auth Screen 3">
</p>


### Home Screen

https://github.com/user-attachments/assets/d1c25722-3f00-46c3-8be2-8ee5620c2179
<div style="display: flex; gap: 10px;">
  <img width="200" src="https://github.com/user-attachments/assets/0cc28c81-d6ac-440c-ab50-2b706171be18" alt="Screenshot 1">
  <img width="200" src="https://github.com/user-attachments/assets/da016ef3-75ca-4ffd-9d60-ec58117afaf8" alt="Screenshot 2">
</div>


### Group Screen


https://github.com/user-attachments/assets/421abd68-20d7-42b7-88cd-b545bb68bf8e

<div style="display: flex; gap: 10px;">
  <img width="200" src="https://github.com/user-attachments/assets/451e8d15-5147-463d-b4c0-b8843ed1f847" alt="Screenshot 1">
  <img width="200" src="https://github.com/user-attachments/assets/430af009-7693-4797-b253-9297b712a9b3" alt="Screenshot 2">
  <img width="200" src="https://github.com/user-attachments/assets/fc052bee-02cd-4620-8489-44c9854ee96b" alt="Screenshot 3">
  <img width="200" src="https://github.com/user-attachments/assets/52494642-88d3-4ca5-a316-eb06e0449ba4" alt="Screenshot 4">
  <img width="200" src="https://github.com/user-attachments/assets/88002820-cd6e-495f-9967-ec92ef732672" alt="Screenshot 5">
  <img width="200" src="https://github.com/user-attachments/assets/419926b7-4512-4703-9a1b-08ce6e1176b7" alt="Screenshot 6">
  <img width="200" src="https://github.com/user-attachments/assets/c4eac045-2972-44ff-ae71-369cfeab85b3" alt="Screenshot 7">
</div>


### Hike Screen

https://github.com/user-attachments/assets/1080fcb7-de6e-4d8f-a52a-eb43f9bb686f


https://github.com/user-attachments/assets/e2a4daaa-121f-492f-b209-59b7ae7fb373


https://github.com/user-attachments/assets/7416a0d0-37c9-445b-a50e-9f9cc8c773ec



<div style="display: flex; gap: 10px;">
  <img width="150" src="https://github.com/user-attachments/assets/c4cb2b4f-0bbc-4638-aab3-d0957fc0fab8" alt="Screenshot 1">
  <img width="150" src="https://github.com/user-attachments/assets/f27d0fa9-09fb-4ba5-8956-1ab5ac96f985" alt="Screenshot 2">
  <img width="150" src="https://github.com/user-attachments/assets/7f198da2-f520-4557-9943-92238a755554" alt="Screenshot 3">
  <img width="150" src="https://github.com/user-attachments/assets/4b977827-e387-43b6-8f13-41195588f231" alt="Screenshot 4">
  <img width="150" src="https://github.com/user-attachments/assets/0643c2b4-281c-4f8d-8fab-f511cdbf20f6" alt="Screenshot 5">
</div>




## Work Track

## Backend work

Objective: To enhance the Beacon backend with new mutations and subscriptions for beacon management and real-time updates.

| Name of the Task                  | Description                                                                                          | Link to Work                                                                                                                                                     |
|----------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Query and mutations             | Added mutations and subscriptions for beacon filtering, rescheduling, and deletion.                 | [PR #380](https://github.com/CCExtractor/beacon-backend/pull/380)                                                                                              |
| Real-Time Updates               | Enabled real-time updates for groups and beacons through subscriptions.                             | [PR #381](https://github.com/CCExtractor/beacon-backend/pull/381)                                                                                              |


## Frontend work

Objective: To enhance the frontend by structuring the app, migrating screens to BLoC, and managing beacon functionalities.

| Name of the Task                       | Description                                                                                             | Link to Work                                                                                                                               |
|---------------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| App Routing and Folder Structuring    | Divided the app into data, domain, and presentation layers and used App Router for navigation.          | [PR #237](https://github.com/CCExtractor/beacon/pull/237)                                                                                  |
| Home and Group Screens Module Migration | Migrated home and group screens to BLoC, introducing separate Cubit files for each module.              | [PR #238](https://github.com/CCExtractor/beacon/pull/238/files)                                                                                                                     |
| Beacon Management                     | Implemented beacon deletion, rescheduling, and filter options.                                         | [Hike Cubit Code](https://github.com/CCExtractor/beacon/blob/36e489cf10c7058e94aeca11af720567966a370f/lib/presentation/hike/cubit/location_cubit/location_cubit.dart) |






## Personal Note

As GSoC'24 draws to a close, I want to express my heartfelt gratitude to my mentor, **Akshat Tripath** and **Aadi Bajpai**, for his unwavering guidance and support throughout the project. Working on [Beacon](https://github.com/CCExtractor/beacon) has been an incredibly rewarding experience, and I'm excited to continue contributing to **CCExtractor** and the broader open-source community. Let's keep the momentum going! 🚀
