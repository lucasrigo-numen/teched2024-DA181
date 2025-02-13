# Exercise 7 - Run your application 

In this exercise, we will configure the run configuration and set the database as SAP HANA Cloud, run the application and also see the SAP HANA Database explorer. 


## Exercise 7.1  Create a run configuration

1. Go to run configuration and click on the project launch.json and select SAP HANA Cloud as database. Then select the HDI container which was created in the [Exercise 6 - Bind your application to an HDI Container ](exercises/ex6/)

<br>![](/exercises/ex7/images/runconfig.png)

2. Select the OData option, and select live data and select API_BUSINESS_PARTNER service as API_BUSINESS_PARTNER in Exercise 3.

**Note: if you're working with SAP Business Accelerator Hub, please follow [ex.7.1](./ex7.1/README.md)**

<br>![](/exercises/ex7/images/odata.png)

3. Run the Application and this will automatically open a new tab in the browser. 

<br>![](/exercises/ex7/images/fioripreview.png)

## Exercise 7.2  Check the service details and explore the application

1. Click on RiskApplication and click on go which shows the data.

<br>![](/exercises/ex7/images/riskapp.png)

2. you can edit the entry and assign a business partner id into a certain risk.

<br>![](/exercises/ex7/images/addbpid.png)

## Summary

You now have successfully built a full stack application with SAP HANA Cloud as database and Cloud Application Programming Model ( CAP ) with Fiori representation.

Check this [Exercise 8 - Inteligent SQL Assistant Console in Business Application Studios (BAS)  ](../ex8/README.md)



