# API Integration

## API Server Build

1. Explain the different between a query string parameter and a path parameter.

   - A path parameter is parth of the url path, like an id. It defines the resources location.

2. What would our API URL with a path id parameter be given the following information:

   1. Domain: http://our-site.com
   2. v3
   3. model name: stuff
   4. id: things

      - http://our-site.com/v3/stuff?id=things

3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

   - User initiates an API call telling the server to do something. The app then uses an API call to tell the server to do something.

## API Server Build

1. Describe how you would use middleware to implement basic and bearer auth.

   - Any protected routes need to go through the middleware.

2. Describe the handshake necessary to implement OAuth.

   - The access token will allow the app to access the user data.

3. Describe how Role Based Access Control works to a non-technical friend.

   - RBAC is used to givepermissions to specific people based on their roles.
