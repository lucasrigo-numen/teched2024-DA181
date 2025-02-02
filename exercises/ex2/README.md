# Exercise 2 - Create Data Model & Service with Joule

In this exercise, we will create a risk management application, helps organizations identify, assess, and track risks, while implementing mitigation strategies to minimize their impact.

## Exercise 2.1 Generate data model

1. Click on Guide Center and select Generate AI-Powered Development

<br>![](/exercises/ex2/images/guidecenter.png)

2. Go to Data Model & Service Creation and Click on Open Joule

<br>![](/exercises/ex2/images/openjoule.png)

3. Your digital assistant Joule is now ready to use.

<br>![](/exercises/ex2/images/joule.png)

4. Copy the below text to your joule assistant to generate the data model and services.
```
Create a risk management app with risks and mitigations. Each risk may refer to one or more mitigations. Add realistic properties to each entity, risks should include a property impact and criticality which should be an integer. Impacts should be in range of 1 to 20000 dollars. Mitigation should include a counter
```

5. You will now see the suggested data model as per the prompt given to the Joule. 

<br>![](/exercises/ex2/images/jouledatamodel1.png)

6. You can now choose to accept it and the changes are reflected in the staging files shown.

<br>![](/exercises/ex2/images/datamodel2.png)

7. Go to Project Explorer > Storyboard and you will see the newly generated data model and services.

<br>![](/exercises/ex2/images/storyboard.png)

8. You can also go to the explorer and see the files i.e schema.cds and service.cds

<br>![](/exercises/ex2/images/cdsfiles.png)

# 2.2 Add Sample Data using Joule

1. Go to guided development and type the prompt as shown below. 

```
Generate sample data. for risks and mitigations
```
`
2. Accept the data and you can see 2 csv files in the project test folder.

![alt text]({FE7255FC-AF99-4224-A56A-47DA10941159}.png)

3. Go to Data editor and review the data.


# 2.3 Add Initial Data on Data Editor

1. Open the Risks entity, then INITIAL DATA tab

![alt text](/exercises/ex2/images/risks-initial-data.png)

2. Click on Add button and fill in the fields to create a record

![alt text](/exercises/ex2/images/risks-add-record.png)


3. Open the Mitigations entity, then INITIAL DATA tab

![alt text](/exercises/ex2/images/mitigations-intial-data.png)

2. Click on Add button and fill in the fields to create a record

![alt text](/exercises/ex2/images/mitigations-add-record.png)

3. Click on the Value Help to link the new mitigation to a risk

![alt text](/exercises/ex2/images/mitigations-link-to-risk.png)




## Summary

Joule lets you create CAP-based data entities and OData services with contextual sample data with just one text prompt. 

Continue to - [Exercise 3 - Add Application Logic](../ex3/README.md)

