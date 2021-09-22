# How to make a simple anonymous chat app in redis:

## Chat with your friends anonymously

### STEP 1: OPEN 2 Terminals

### STEP 2: Run redis-cli to check if it is working 

### STEP 3: Go to upstash to use a remote redis server: : https://upstash.com/

### STEP 3: Create a redis database and connect both the sides

### STEP 4: Copy the command which is given in the upstash website, to connect the remote server :

```bash
redis-cli -u redis://bdff23be171a4f9eafb8be42a7ed9f1a@usw1-neutral-lynx-31383.upstash.io:31383
```
  
### STEP 5: Simply create a channel and subscribe 

```bash
SUBSCRIBE devnest
```

### STEP 6: Then write to chat:

```bash
 PUBLISH devsnest message
```