HOW TO RUN?

Open TERMINAL and inside the server file, write "npm run dev" (same for the client file now). This is because, in order to fill the graphics and make the application work, you need first to run the server, to populate the DB.

NOTE!!: If the TERMINAL gives this error: Port already exists, then run these 2 commands: outside the Aplicatie folder: (this is because you are using the same port in multiple places)
netstat -ano | findstr :1337
taskkill /PID 1337 /F
