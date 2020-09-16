# A Simple Task Management App (API)

Note: Bootstrapped with Nestjs CLI, so please ensure you have it installed.

### Local Setup
1. Install `@nest/cli` globally from npm using `npm install -g @nest/cli`
2. Clone this repo
3. Cd in to cloned repo and `npm install` or `yarn install` to install all dependencies
4. Start local server using `npm start:dev` or `yarn start:dev`

### Supported Operations: 
1. Fetch all tasks `GET /tasks`
2. Create a task `POST /tasks`
3. Get a particular task `GET /tasks/:id`
4. Delete a task `DELETE /tasks/:id`
5. Update the status of a task `PATCH /tasks/:id/status`
6. Filter by search term `GET /tasks?search=yoursearchquery`
7. Filter by status `GET /tasks?status=OPEN`

### TODO
1. ~~Search/Filter functionality~~
2. Validation
3. Integration with a DB