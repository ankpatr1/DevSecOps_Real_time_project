                                                  *currently this project is inprogress.* 

                                                      **Devops Real time project :**
  
  **Pre-req :** 
  things we need to have before starting this project :
  
  -> AWS account ( free for 1st 6 months )
  -> programmatic access and aws configured wth CLI 
  -> python3 installed.
  -> Docker and kubectl installed or not ?
  -> code editor (VS or any ide is fine )

**lets start the project** 

**Need to set up**

create **AWS account**  : creating ER2 AND s3 we are using , lambda etc services .

-> we need to give programmming access and we need to confugred : 
                   **go aws portal create access
                   -> iam role 
                   > there you can find this or if its not avaliable** the create this key .
                   
-> then open the terminal 
             > type **"aws configure"** 
             > provide details as per requirement and connect.
             
-> varify connection you can type : 
                 **aws IAM list-users 
                 > it provide list of you using or active account . 
                 > if you see the details then you are in aws .**
                 
-> check **python version**.

-> create **docker file** we need **docker installed > docker -- version mine is 20** so check once .

-> run **"kubctl version"** in the terminal and check pods and nodes are ready or not .


