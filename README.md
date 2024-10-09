# S.O.M.E

Service Organization and Management Environment

## Development

### Frontend

Start the frontend using `npm run dev`. The development server will be accessible on a certain port mentioned on the
commandline.

The frontend configured a proxy which allowed to access the backend server. The configuration could be found in
`vite.config.ts`. The important part is the port the backend server is configured to listen to.

### Backend

The backend server is currently listening to port `8080` (see `application.properties@server.port`).

## Resources

- [Project Template for Spring-Boot with Vue](https://github.com/jonashackt/spring-boot-vuejs)