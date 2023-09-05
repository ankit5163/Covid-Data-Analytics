# Covid-Data-Analytics
This is a Data analysis project. In this, we have created a dashboard using the concepts of MsExcel on business analyics platform PowerBi.

Step 1: Visualise the sheet.

Step 2: Delete the null values or false values

Step 3: In the Boolean features, 1 means "yes" and 2 means "no". values as 97 and 99 are missing data means "no report"
        Sex: 1 for female and 2 for male.
        Covid test findings. Values 1-3 mean that the patient was diagnosed (+ve). 4 or higher means that the patient  was diagnosed (-ve).
        If the patient died indicate the date of death, and 9999-99-99 otherwise (i have changed this to no report).

Step 4: Before applying the above changes create a reference sheet so that your original data set is not affected

Step 5: Add a column as " Age group = IF([AGE]<20,"Teenager",if([AGE]>=20 && [AGE]<50,"Adult",if([AGE]>=50,"Senior citizen","Adult"))) "
                        " Died = if([DATE_DIED]="9999-99-99" ,"No report", "Yes") "
                        " States = SWITCH(RANDBETWEEN(1,28),1,"Andhra Pradesh",2,"Arunachal Pradesh",3,"Assam",4,"Bihar",5,"Chhattisgarh",6,"Goa",7,"Gujarat",8,"Haryana",9,"Himachal 
                          Pradesh",10, "Jharkhand",11,"Karnataka",12,"Kerala",13,"Madhya Pradesh",14,"Maharashtra",15,"Manipur",16,"Meghalaya",17,"Mizoram",18,"Nagaland",19,"Odisha",20,
                          "Punjab",21,"Rajasthan",22,"Sikkim",23,"Tamil Nadu",24,"Telangana",25,"Tripura",26,"Uttar Pradesh",27,"Uttarakhand",28,"West Bengal") "
                          
Step 6:Add graphs according to your choice to create visuals!!

And here you GO!!!
![image](https://github.com/ankit5163/Covid-Data-Analytics/assets/85782912/3754ce8b-1b88-45d3-a842-4584d0bc2f6e)

![image](https://github.com/ankit5163/Covid-Data-Analytics/assets/85782912/9ae21a27-172f-4a98-9ae0-b66274d5d447)


