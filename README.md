# online-payment-system
Basic online-payment system for .Net users.
First you need to have account at Iyzico.
Then, you have to enter your private api key and secret key at Iyzico/Merchant Settings to StoreApp.Web > Controllers > OrderController.cs file.
To test your app, you should use test user datas. You can find these datas in "https://github.com/iyzico/iyzipay-dotnet".
To skip these part, directly use these datas: 
"paymentCard.CardHolderName = "John Doe";
paymentCard.CardNumber = "5528790000000008";
paymentCard.ExpireMonth = "12";
paymentCard.ExpireYear = "2030";
paymentCard.Cvc = "123";"
Finally you have to ready to go!

# Requirements
One of the runtime environment is required from below
* .NET Framework 8

# Installation

For now you'll need to install following libraries:

* To install Iyzipay, run the following command in the Package Manager Console
```
Install-Package Iyzipay
```
 Or you can download the latest .dll from:  https://github.com/iyzico/iyzipay-dotnet/releases/latest
 
For .NET Framework:
* Newtonsoft.Json 13.0.2 from http://www.newtonsoft.com/json#

For .NET Standard 2.1:
* Newtonsoft.Json 11.0.2 from http://www.newtonsoft.com/json#
