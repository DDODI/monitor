# monitor
The core Monitor backend and API server for DDODI

## components

1. Supervisor for harvesters
- Runs harvesters regularly, 
- Once the jobs are done, triggers git to do version control
- Log data harvest events: dataset gets updated, new dataset added

2. API endpoint
Expose data as API for front-end


