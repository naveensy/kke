# Problem statement
### 

![linux-user-expiry](./images/Linux%20user%20expiry.png)


# Solution

### Set linux user expiry

##### Step1: Add the user
```
useradd siva
```
##### Step2: Check user details
```
chage -l siva
```

##### Step3: Add expiry as mentioned
```
chage -E 2021-04-15 siva
```
##### Step4: Check user details for validation
```
chage -l siva
```

![linux-user-validation](./images/user%20expiry%20validation.png)