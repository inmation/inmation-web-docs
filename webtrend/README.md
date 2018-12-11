# Introducing inmation:webtrend

inmation has been working on an exiting new project - **inmation:webtrend**. **WebTrend** is a *trend display application* with the charts data directly coming from the system:inmation. System:inmation and the WebTrend is a powerful combination, allowing the end user to track, compare and spot the abnormalities that are crucial for continues operations, in close to the real event time. Giving that extra edge for swift decision making.

![WebTrend](./webtrend.png "WebTrend")

___

## 1. Features

WebTrend offers users a neat interface and extensive functionality. Most important features are as follows:

### Web application

inmation:system DataStudio already offered a RealTimeTrend display, the main differences between DataStudio RealTimeTrend display and the WebTrend is that WebTrend is a web application, while the RealTimeTrend is hosted in the DataStudio. This allows to access WebTrend separately from the DataStudio.

### Speed

Trends between system:inmation and the WebTrend are streamed by the system:inmation Web API (Application Programming Interface), which is hosted in a Windows Service. It can be used by any external application as an interface to system:inmation, using the HTTP or WebSocket Interface. This architecture allows a very fast data streaming to the WebTrend.

### Actual values

Actual values are the last know values of the item, they are displayed on the right bottom corner of the WebTrend screen.

### User friendly

WebTrend interface is easy to use and has a fresh modern look and feel. Features such as color picking from the wide variety colour pallet just adds an extra pleasant touch.

### Live

Live trend streaming is an option to play the selected trends. When play button is pressed the actual values are incoming with a 10 second delay and are directly displayed on your screen as a number value and as a trend.

### KPI model

On the left side of the WebTrend inmation KPI model is displayed. Which KPIs are displayed in the KPI model can be tailored in the DataStudio, by adding items and pens or removing them.

### Tag Table

A tag table is a table with items from the system:inmation DataStudio I/O model. Tag table can be created by adding a new dataholder item in DataStudio I/O model. Once the dataholder is created, add name, description and item path, click apply and the newly created tag table should be visible in your WebTrend KPI model, selected pens can be added to the trend.

### Share options

Your tailored view can be shared through a share option. To share click on **`</>`**, which is on the top right corner of the screen. Share settings allows the user to choose whether or not he wishes to share the view with a KPI Model, Include Credentials, enable Visual KPI usage or share Actual Values.

![Share](./share.png "Share")

___

## 2. DataStudio and the WebTrend

Newest version of DataStudio supports the WebTrend. To open a WebTrend in the DataStudio choose item in the I/O model ,right mouse click on the selected item and choose add items to WebTrend. WebTrend will be displayed in the display section of the DataStudio.

## 3. Visual KPI and WebTrend

The users of Visual KPI can benefit from the WebTrend too, as it can be embedded into Visual KPI dashboard.

## 4. Configurations

What do you need in order to use WebTrend? The only requirement is inmation Web API version 1.46 or higher.
