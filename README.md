# Desk.com Canvas Dependent
A Desk.com canvas app that creates dependent list fields based on list field. It takes all the list field values and splits them on the `::` separator. Those values are then converted into a hierarchy and depending on which value is select it would show another list field with the child values.

![Preview](https://api.monosnap.com/rpc/file/download?id=D7Pup9gdls5v1OIk7Ram8Be06d0cwb)

## Installation Steps
### Deploy the Application
The first step to install this application is to deploy the source code to your Heroku account. Simply click this button and the application will be deployed.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Create the Integration URL
Now that you have the application on Heroku, go ahead and create the integration URL. You'll need specify the `field` param with the name of the custom list field you want the app to use.

![Integration URL](https://api.monosnap.com/rpc/file/download?id=L55bM4Fpbcqs1LWxB5yETn6CN6KxSA)

### Add it to your Case Layout
The last step is to display your canvas application on your case layout. Don't forget to select some users you'd like to show the application to as well as change the height of the canvas based on the height of the list field options.

*Gotcha:* You might want to add other fields in the canvas app beneath the list fields because the list field options will get cut off if the canvas app isn't big enough.

![Case Layout](https://api.monosnap.com/rpc/file/download?id=InLu33nbjB6TvXMs9davrdDMMudwiJ)
