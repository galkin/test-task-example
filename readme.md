# Node.js Engineer coding task

The goal is to test the Node.js skills.

### Project structure

- [app](./app) is place where you will write your Node.js app
- [db](./db) has Dockerfile and sql fixtures
- [docker-compose.yml](./docker-compose.yml) use `docker-compose up` for setup DB and test Dockerfile for your app.

### Data model

```typescript
interface User {
    id: string;
    first_name: string;
    last_name: string;
    email: string; // for internal use, hidden in REST API
    avatar?: string;
    online: boolean; // used for filtering
    created_at: Date; // for internal use, hidden in REST API
    updated_at: Date; // for internal use, hidden in REST API. Set current time on update
}
```

### Task

Design and implement REST API endpoints:
- [ ] get list of users
- [ ] get specific user
- [ ] change user's avatar and online status

DevOps practises:
- [ ] Use environment variables for configuration
- [ ] add ignore files
- [ ] implement Dockerfile for Node.js app

**During task You can use any npm packages and google solution**
