# TUTORIAL FOR RUN ON THE SMARTPHONE

### RUN THE CLIENT WITH THE FOLLOWING COMMAND
```
npm run dev -- --host
```
### THEN SELECT THE IP ADDRESS (WITHOUT PORT) CORRESPONDING TO THE LAST ELEMENT THAT IS RETURNED
```
VITE v5.0.8  ready in 174 ms

➜  Local:   http://localhost:5173/
➜  Network: http://192.168.56.1:5173/
➜  Network: http://192.168.73.212:5173/  ➜ Select this IP, without port (192.168.73.212)
➜  press h + enter to show help
```

### NOW SUBSTITUTE THE OBTAINED IP IN COSTANTS.JSX FILE (IN THIS EXAMPLE IS 192.168.73.212)
``` javascript
const HTTP_AND_IP_ADDRESS_AND_PORT = "http://192.168.73.212:3001";
```

### NOW FROM THE SMARTPHONE, OPEN GOOGLE CHROME AND DIGITS ON THE SEARCHBAR
```
chrome://flags/ 
```
### SEARCH ON THE RESULTING PAGE
```
Insecure origins treated as secure
```
### NOW INSERT THE PREVIOUS URL (IN THIS EXAMPLE http://192.168.73.212:5173/) IN THE INPUT FIELD AND SWITCH TO ENABLE. AFTER THAT, ACCONSENT TO RELAUNCH CHROME TO APPLY THE CHANGES.

### NOW RUN BOTH CLIENT AND SERVER

### USE THE PREVIOUS URL (IN THIS EXAMPLE http://192.168.73.212:5173/) TO RUN ON THE SMARTPHONE
