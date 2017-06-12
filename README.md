Job Portal with following funtionalities:

1. Home page to select looking for (i) candidate (ii) jobs
2. Log in functionality
3. List jobs from database
4. Showcase details of the job
5. Upload a resume (candidate) 
6. Apply for a job

For correct execution
1.kindly install Xampp 
2.create database of name 'portal'
3.create the mentioned tables below with the mentioned schema(else weird errors can arise)
  Table name | column name | data type | size
  login        Username      VARCHAR     255
               Password      VARCHAR     20
               Type          INT         2
               
  employees    Name          TEXT        255
               Userame       VARCHAR     255
               Email         VARCHAR     255
               Password      VARCHAR     20
               Curr_company  VARCHAR     255
               Curr_ctc      VARCHAR     20
               Curr_desg     VARCHAR     255
               Curr_location TEXT        255
               profile_pic   VARCHAR     255
               resume        BLOB     
               skills_1      VARCHAR     255
               skills_2      VARCHAR     255
               skills_3      VARCHAR     255
               desired_location TEXT     255
               desired_desg  VARCHAR     255
               desired_ctc   VARCHAR     20
               Experience    INT         10
               
employers      CompanyName   VARCHAR     255
               Userame       VARCHAR     255
               Email         VARCHAR     255
               Password      VARCHAR     20
               Location      TEXT        255
               Offered_ctc   VARCHAR     20
               Designation   VARCHAR     255
               Skill_1       VARCHAR     255
               Skill_2       VARCHAR     255
               Skill_3       VARCHAR     255
               Experience    INT         10
               
               
              
