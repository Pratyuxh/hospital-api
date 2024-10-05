# Hospital API

#### Setup the Project

1. Clone or Download the Repo.
2. `cd hospital-api` goto the Repo using Terminal.
3. Run `mongod` to start the MongoDB Database.
4. Run `npm start` to ignite the project.
5. Use **Postman** to test the api.

#### Routes
1. **Register a Doctor:** `[POST]: /api/v1/doctors/register`
2. **Login for Doctor:** `[POST]: /api/v1/doctors/login`
3. **Register a patient:** `[POST]: /api/v1/patients/register`
4. **Create Patient report:** `[POST]: /api/v1/patients/:id/create_report`
5. **Fetch All Reports of a Patient** `[GET]: /api/v1/patients/:id/all_reports`
