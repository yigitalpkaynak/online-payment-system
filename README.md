# online-payment-system
Basic online-payment system for .Net users.
First you need to have account at Iyzico.
Then, you have to enter your private api key and secret key at Iyzico/Merchant Settings to StoreApp.Web > Controllers > OrderController.cs file.
To test your app, you should use test user datas. 
You can find these datas in "https://github.com/iyzico/iyzipay-dotnet".
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

* ![Ekran görüntüsü 2024-05-26 112211](https://github.com/yigitalpkaynak/online-payment-system/assets/71692297/6dcf302e-54cc-4cda-8483-bb06c5084805)
![Ekran görüntüsü 2024-05-26 112225](https://github.com/yigitalpkaynak/online-payment-system/assets/71692297/b10d5246-801b-465a-b8ab-c74a9090088a)
![Ekran görüntüsü 2024-05-26 112354](https://github.com/yigitalpkaynak/online-payment-system/assets/71692297/81baa9f8-6f47-4c6b-bcdf-e3b8f390520e)
![Ekran görüntüsü 2024-05-26 112415](https://github.com/yigitalpkaynak/online-payment-system/assets/71692297/311415b1-78dc-440e-924e-8efb3030171d)
![Ekran görüntüsü 2024-05-26 112524](https://github.com/yigitalpkaynak/online-payment-system/assets/71692297/1560247e-b982-4d0d-8aef-b8447fb685ae)

