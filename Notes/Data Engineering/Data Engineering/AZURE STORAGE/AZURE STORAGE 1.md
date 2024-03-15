azure - storage account
gcp - cloud storage
aws - s3

## AZURE STORAGE ACCOUNT
1. scalable 
2. low cost

#### TYPES -
![[Pasted image 20240305230639.png]]

1. blob storage / adls
2. file storage
3. queues
4. azure tables

#### RESOURCE GROUP - 
1. logical separation
2. it is like a bag containing multiple things
3. resource group is free but the things inside it take charge

#### storage account name has to be unique like domain name

#### REGION - 
azure has data centers across the world , region represent that geographical locations

#### PERFORMANCE - 
standard for practice
premium for company

![[Pasted image 20240305225705.png]]

generally resource creation , storage configuration is not responsibility of data engineer 

#### ADVANCED TAB -> HIEERARCHIAL NAMESPACE
![[Pasted image 20240305233301.png]]
if enabled creates the adls (azure data lake storage) account if not blob account

###### adls vs blob (normal) - 
1. in adls folder hierarchy can be made -> like in fol1 there is fol2 & fol3 in fol2 there is fol4
2. adls is created and optimized for big data analyst
3. after doing big data analysis adls is fast and better performance

#### NETWORK CONNECTIVITY - 
1. boundaries can be set like anyone who access the account should be from specific IP address   ![[Pasted image 20240305233845.png]]
   
#### ENCRYPTION -
1. two types of encryption in azure storage
   1. at transit - when uploading the data
   2. at rest -  for the uploaded data

#### CONTAINER / BLOB STORAGE - 
1. it is like basic main drive  
2. ![[Pasted image 20240305232413.png]]




















