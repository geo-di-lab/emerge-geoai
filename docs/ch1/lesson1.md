# Get Google Earth Engine

```{note}
We recommend using an `@gmail.com` address instead of an institutional .org or .edu email address. This is because Google Cloud may have different options based on your institutional email's settings. Thus, we found that Gmail may be the best for working with Google Earth Engine for educational purposes.
```

1. Go to <a href="https://console.cloud.google.com/earth-engine" target="_blank" rel="noopener noreferrer">console.cloud.google.com/earth-engine</a> and sign into your Google account if you're not already signed in. Click {guilabel}`Register` under "Register your Cloud project."
![Welcome to Earth Engine page](gee_1.png)

2. Click {guilabel}`Create project`
![Create a project page](gee_2.png)

3. Enter a name like "emerge-lessons" and click {guilabel}`Create`. This name is your project ID. If you are using a .edu or an organizational email, this page may look different and you may have other options or limitations.
![New project page](gee_3.png)
```{important}
Make note of your project ID! There may be some numbers after what you typed, like emerge-lessons-359891
```

4. Click {guilabel}`Get started` under "See if you are eligible for noncommercial use."
![Google Cloud configuration page](gee_4.png)

5. Complete the series of short questions as follows:

> For "Select your organization type" choose "Earth Engine trainer or trainee" and click {guilabel}`next`.

> For "Check noncommercial eligibility" choose "Participant" for the first question and then write the date you are starting the lessons, as well as the date you expect to finish. If you are not sure yet, you can put "09/01/2026." If you end up needing more time, you can update this. Click {guilabel}`Check eligibility`

> It should say {fa}`circle-info` **Based on your answers, you are eligible for noncommercial Earth Engine use.** 

> Click {guilabel}`Next` to go to **Choose your plan**. Under "Please select a quota tier," you can select **Community**.

> For "Describe your work," under "Will you use Earth Engine for any of the following? *" choose "Classroom or education" and click {guilabel}`OK`. Then click {guilabel}`Next`

> Your screen should look like below:
![Earth Engine registration page](gee_5.png)

6. In the pop-up that appears, click {guilabel}`Enable` to enable the Earth Engine API.
![Enable required APIs](gee_6.png)

7. You should see the page below. You can now close this tab.
![Configuration page saying Cloud project is registered](gee_7.png)

You have now created your cloud project and enabled the API! Move to the next section to start running Google Earth Engine in Google Colab.