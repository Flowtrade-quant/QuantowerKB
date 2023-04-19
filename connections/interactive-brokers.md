# Interactive brokers

## Page 1

### Connection to Interactive Brokers <a href="#connection-to-interactive-brokers" id="connection-to-interactive-brokers"></a>

Follow the steps in this guide to connect the Flowtrade platform to the Interactive Brokers. The manual contains a detailed description, which will allow you to correctly configure the connection.

* ​

#### Data Limitations <a href="#data-limitations" id="data-limitations"></a>

Interactive Brokers places the following limitations on real-time and historical data accessible to 3rd party applications

* **Pacing Violations** – TWS limits the number of requests for data. If too many requests for data occur in a short period of time, you may see error messages indicating “Pacing Violation”. If this happens you may need to wait a few minutes before trying to load data again.
* **Real-Time Quotes** – TWS does impose limits on the number of active tickers (typically around 100). Additional booster packs can be purchased from IB to work around this issue: [Booster Packs](https://www.interactivebrokers.com/en/index.php?f=14193).
* **Delayed Data Not Supported** – TWS does not provide access to delayed historical data and quotes.

For more details on these limitations see [IB Data Limitations](https://interactivebrokers.github.io/tws-api/historical\_limitations.html#gsc.tab=0).

* IB does not currently offer full depth market data for futures.
* Market data updates are not frequent; therefore, we do not recommend using IB data (instead we recommend using dxFeed or Iqfeed as market data provider).

#### Necessary steps for a successful connection to Flowtrade <a href="#necessary-steps-for-a-successful-connection-to-quantower" id="necessary-steps-for-a-successful-connection-to-quantower"></a>

* ​**Download** and install Flowtrade trading platform (if you haven’t it yet) of an appropriate version (32 bit or 64 bit), and make sure that your PC complies with the **minimum requirements**
* To connect to IB, you need to have (or create) a [**demo**](https://www.interactivebrokers.co.uk/en/index.php?f=1286) or [**real account**](https://www.interactivebrokers.com/en/home.php) by clicking the appropriate links on the Interactive Brokers official website.

​![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MhwSMtTgBnH1z\_\_YvkG%2F-MhwTqv3y9BctkElAg6Y%2Fimage.png?alt=media\&token=ff706c07-3a86-4730-94a1-3e0355a9fcb9)​

* Download and install IB Software — [**TWS (Trader Workstation)**](https://www.interactivebrokers.co.uk/en/index.php?f=14099#tws-software) or [**IB Gateway**](https://www.interactivebrokers.co.uk/en/index.php?f=16454) on their website.

The difference between IB Gateway and TWS is that IB Gateway has a lighter and less sophisticated graphical user interface (GUI) than TWS.![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MhwSMtTgBnH1z\_\_YvkG%2F-MhwUvUxkAuMasyX6wfe%2Fimage.png?alt=media\&token=b4764e57-43c8-4ac6-a882-18739da1bf64)Download Trader Workstation (TWS) or IB Gateway

#### How to connect to Interactive Brokers using TWS platform <a href="#how-to-connect-to-interactive-brokers-using-tws-platform" id="how-to-connect-to-interactive-brokers-using-tws-platform"></a>

* Launch TWS and enter your **Username** and **Password** into it, that you received from the broker and click on **Log In** button.

​![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MhwSMtTgBnH1z\_\_YvkG%2F-MhwX0FdsE5FPFYs3Er6%2Fimage.png?alt=media\&token=fc141be5-ec25-42bd-9489-01ebe0243964)​

* Once you are logged in, open the additional settings in TWS: **Configure**. Select **API** section - > **Settings** and check to **Enable ActiveX and Socket Clients** box as well uncheck **Read-Only API**

​![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MhwSMtTgBnH1z\_\_YvkG%2F-Mhw\_W1-ZW0Pd2auJSvX%2Fimage.png?alt=media\&token=22212e3e-22f3-4fc6-b37c-0bcb7edda91d)Diactivate Read-Only API and check Socket Clients in TWS platform

* Select **API** section - > **Precautions** and activate all checkboxes.

​![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MhwSMtTgBnH1z\_\_YvkG%2F-MhwaHekpZaLUBTIe0yD%2Fimage.png?alt=media\&token=6958d117-dea0-41df-9750-aeac25c7781e)​

* Next, check that the TWS platform is selected in the connection settings in the Flowtrade platform.

​![](https://1977910382-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-MhwSMtTgBnH1z\_\_YvkG%2F-MhwbN\_\_qYq7TleJbIO1%2Fimage.png?alt=media\&token=98111fdb-3d20-4135-b294-4a8ee2f24fab)​
