---
description: >-
  !!For all NEW users. Make sure to sign the 2 agreements upon first login into
  rTrader Pro. These are mandatory!! -
---

# Rithmic / Trading combines&#x20;

## Connection to Rithmic

Rithmic technology provides access for trading futures and options on CME, CBOT, NYMEX and other exchanges. Full market depth, reliable data and great execution are main features of Rithmic.To connect Flow trade to a broker that uses Rithmic technology, it is sufficient to have (or create a new) account.

* **​**[**Connection for Existed Accounts**](https://help.quantower.com/quantower/connections/connection-to-rithmic#connection-for-existed-accounts)**​**
* **​**[**Connection for New Accounts**](https://help.quantower.com/quantower/connections/connection-to-rithmic#connection-for-new-accounts)**​**
* **​**[**How to activate Market by Order (MBO) data**](https://help.quantower.com/quantower/connections/connection-to-rithmic#how-to-activate-market-by-order-mbo-data)**​**
* **​**[**Problems during the connection to Rithmic**](https://help.quantower.com/quantower/connections/connection-to-rithmic#problems-during-the-connection-to-rithmic)**​**

#### Connection for Existed Accounts <a href="#connection-for-existed-accounts" id="connection-for-existed-accounts"></a>

* **​**[**Download and install R Trader Pro**](http://yyy3.rithmic.com/?page\_id=16) from Rithmic official website.
* Open connection manager, select **Rithmic** and specify the type of connection (**Demo / Real**).
* Click on **Connection Settings** and **activate Use RTrader** option to avoid additonal fees for subscription to market data. If necessary, trader can change the server. By default, the Rithmic Paper Chicago server is set for demo accounts and the Rithmic Aurora Chicago server is set for real accounts.
* Enter your login and password and click **Connect.**

![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-Lur9mOkqzf5E-qoRjQS%2F-LurewzBWTrEo9dUR4qa%2FRithmic%20connection.png?alt=media\&token=04cf1016-7042-4690-a7b4-223adf399e85)Enter login data for connection to Rithmic Starting from May 1, the [CME exchange сhanged the rules for determining a professional market participant](http://yyy3.rithmic.com/?p=1069), and as a result, increased the fee for the market data. In order to correctly define the professional participant, Rithmic has changed the connection parameters in their platform, as well as in API for platforms such as Flowtrade .To avoid additional fees for subscription to market data, a trader needs to login through the R Trader Pro platform and activate the setting in Flow Trade, which is called **Use RTrader**. hActivate Use RTrader option to avoid additional fees for subscription to market data

<figure><img src="../.gitbook/assets/Rithmic plugin (1).gif" alt=""><figcaption></figcaption></figure>

#### Creating a New Accounts and further connection <a href="#creating-a-new-accounts-and-further-connection" id="creating-a-new-accounts-and-further-connection"></a>

* **​**[**Create a new demo**](https://rithmic.com/demo.html#sign-up) or open a real account with any broker supporting Rithmic technology, accept agreements, and start using our platform.
* To register [**Rithmic Demo**](https://rithmic.com/demo.html#sign-up) go to their official website ​
* Fill in all the required fields
* Accept _**"Market Data Subscription Agreement"**_ and _"**Market Data Self-Certification"**_
* Account will be activated within 30-60 minutes.

### **How to activate Market by Order (MBO) data** <a href="#how-to-activate-market-by-order-mbo-data" id="how-to-activate-market-by-order-mbo-data"></a>

**Market by Order (MBO) data** shows the order size of an individual position inside the level2 data for a certain price. To activate the displaying of this data, open the Connection settings and tick on "**Enable 'Market by Order' (MBO) mode**".![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2F1YbinFeQpJqyr4HCTdQv%2Fimage.png?alt=media\&token=3f05dad2-4fa1-444a-8ef5-4ac1537e5ba9)Enable Market by Order MBO data for Rithmic in Quantower platformAfter activation, you can see this data in the DOM Trader panel.Open **Settings** in the DOM trader panel -> **Columns** -> **Bids/Ask** (if you use split mode or **Bids** and **Asks** as single columns) -> **Size coloring scheme** -> **MBO.** Also, you can set **Filter orders more than (MBO)** if you want to see orders with a certain size.![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2FsT0uSmlAvRZ0CkvJUVlv%2Fimage.png?alt=media\&token=093bfb88-a517-4e2a-8c61-2c7a97f19b9a)Activating MBO data in Flow Trade platform![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2FLDRd5hwwr8KhItL2wzeA%2FMBO%20vs%20MBP.png?alt=media\&token=288de9b2-f654-4470-a812-2f99ea99b1f5)Visual comparison between Market by Oder (MBO) and Market by Price (MBP)

### **Problems during the connection to Rithmic** <a href="#problems-during-the-connection-to-rithmic" id="problems-during-the-connection-to-rithmic"></a>

#### **Market Data Connection Closed (Broken)** <a href="#market-data-connection-closed-broken" id="market-data-connection-closed-broken"></a>

Sometimes, when connecting to the Rithmic, you may see the error **"**_**Market Data Connection Closed (Broken)".**_ Below we will describe possible reasons and solutions. This error message is most commonly encountered by _**new Rithmic users for various reasons**_ and is not within the control of the Flowtrade platform.![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-M6Jg2Juc\_FoNhGc1Ssw%2F-M6JscrXrApLQZCZO49v%2FConnections%20error%20with%20Rithmic.png?alt=media\&token=b214f165-4bd0-4f66-ad06-1008ec93fd72)Rithmic error "Market Data Connection Closed" in FlowTrade![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2F1yTv7wyacAGNP63MTDrp%2Fimage.png?alt=media\&token=c0676ebc-937e-42df-be4a-bd775cb3c74e)Rithmic error "Market Data Connection Broken" in Flowtrade

**Connection to Rithmic can be done in two ways:**

* directly, without using RTrader Pro platform. This approach allows only one platform to be connected.

![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2FY35XU5vUfBFqSwVxHfBK%2Fimage.png?alt=media\&token=78aa103e-7760-48e0-bcae-73751b6b20e7)

* through their RTrader Pro platform. This connection uses Plugin Mode and **allows you to connect multiple platforms at the same time (!)**

![](../.gitbook/assets/flw1.PNG)Use Rithmic plugin mode for multiple access More often such error occurs for the following reasons:

* You didn't accept agreements "_Market Data Subscription Agreement"_ and _"Market Data Self-Certification"_ during the registration on Rithmic's website or in R Trader platform. _We recommend connecting through **R Trader** or **R Trader Pro** platforms to check your account.**Solution:** accept agreements in RTrader Pro platform_
* A new account was created less than an hour ago. Usually, the **full activation of a new account takes from 30 minutes to 1 hour**._**Solution:**_ _open RTrader Pro platform and connect with your login. If the connection is successful, then your account is active in Rithmic system_
* Make sure that your login matches the Demo or Real connection_**Solution:**_ try both connection options in Flow Trade

![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2F9N00ZoECbpyt54M2mJdX%2Fimage.png?alt=media\&token=781237c3-54c4-432e-9780-28b45e3710fa)

* If Flowtrade was connected to Rithmic before via the RTrader Plugin (i.e. the checkbox Use RTrader is active), and at the moment the RTrader Pro platform is not connected or the **Allow Plugins** option is not active there, then Flowtrade will not be able to connect._**Solution (several different options, not step-by-step):**1) start RTrader Pro platform with **Allow Plugins** mode and connect again to your account in Quantower2) try to connect to Rithmic as a direct connection: close RTrader Pro platform, disable **Use Rtrader** option in Flowtrade settings and restart Flowtrade. After start Flowtrade again and connect to your account as a direct connection_

![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2F528gGqEvJPDxqUMm5hXv%2Fimage.png?alt=media\&token=d05cbdd8-cd46-41ba-97ad-3101e0a3eb48)Plugin Mode in RTrader Pro is disabled but active in Flowtrade

* In the case of a direct connection (without RTrader Plugin mode), you cannot use the same login on different platforms at the same time. The connection can be only one login on one platform (!).When trying to connect with one login on different platforms, it can log out from the first platform (which was connected), but the login on the second platform will not be successfully connected (on which we are trying to log in)._**Solution:** use RTrader Plugin mode for multiple connections or close all platforms and connect via Flowtrade as direct connection (without Rtrader plugin mode)_

![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-LD6FsRvQ3jgwJIg6O7r%2Fuploads%2FzpPqjPiumTpsXz3hRB69%2Fimage.png?alt=media\&token=25b9c366-4bf3-4dc7-8996-244fe3559143)

* The error can be encountered because the Rithmic server is unavailable to be connected to. This error commonly can be encountered over the weekend. In this case, it is best to wait until Sunday evening to see if you can connect to determine if this is the problem or there is some other problem.
* Rithmic demo accounts are limited to 14 days per exchange guidelines on providing live, streaming data. If you have used a Rithmic demo previously you will _not_ be able to login with a new Rithmic demo Username.
* If you are unable to connect within a few days, you need to contact your broker about this issue.

If you enable Use RTrader plugin in Connection Settings and still can not connect to Rithmic, please check that you have more than 1 active session for Market data.![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MVpDkGRg7ydps6P-wo7%2F-MVpDupYeGV9ept79aHB%2Fimage.png?alt=media\&token=9266e9ef-cbdb-457b-b11c-47efcc3da4a8)

#### No Level2 data for some symbols <a href="#no-level2-data-for-some-symbols" id="no-level2-data-for-some-symbols"></a>

This problem can be due to the fact that you do not have a subscription to this Level2 data. To check this, launch the **RTrader Pro platform** and open the **Order Book** panel.If you don't have Bid/Ask values in the RTrader platform, you need to subscribe to this data via Rithmic's support. After that, you will see level2 data in our platform as well.![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MexaGeG8Hdw8btLk6zp%2F-MexnRcJ4uJZhtBT7Pxv%2Fimage.png?alt=media\&token=e5187191-6845-4f47-bb46-cae6537a0fe7)

#### ERROR: Only Admins Can Place Trades <a href="#error-only-admins-can-place-trades" id="error-only-admins-can-place-trades"></a>

This means that the Evaluation account has been failed and has been disabled.It either means you have reached your Trailing Threshold Drawdown or that you have held a trade past 4:59 PM ET.To resolve this issue, please contact support team of your Prop Trading company
