# <img src="https://docs.goshippo.com/images/Logo.png" width="30" alt="Shippo logo"> Shippo Java SDK demo

* Collect shipping rates offered by the carriers configured in your Shippo account
* Use a selected rate (this code looks for the lowest rate) to request a label
* Download the label for use in shipping your package

## Running the code

Before you run this code, you will need to have performed the below steps:
1. Install a recent version of Java (this sample was written using JDK11)
2. [Create a Shippo Account](https://apps.goshippo.com/join)
3. [Generate a Shippo API Token](https://support.goshippo.com/hc/en-us/articles/360026412791-Managing-Your-API-Tokens-in-Shippo#:~:text=Generate%20a%20Token,-To%20generate%20a&text=To%20generate%20a%20Test%20Token,and%20purchase%20test%20shipping%20labels.). Since this is a sample app, it is recommended that you generate a test token rather than a production (i.e., paid) token.
4. Create an app.properties file at app/src/main/resources/app.properties with an `apiKey` property with your token as its value:
``` txt
  apiKey=shippo_test_0123456789abcdef0123456789abcdef01234567                     
```
5. Run the sample!
```shell
gradle run
```