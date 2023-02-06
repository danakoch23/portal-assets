# Summary

The Page "App Subscription Management" is accessible via the top main menu for app providers.

The main focus / scope of the page is to enable app providers to manage their app subscriptions (active as well as requests)

The page includes following functions

* search
* filter
* trigger subscription activation

<br>
<br>

# Function

### Management Board
<img width="1000" alt="image" src="https://user-images.githubusercontent.com/94133633/211654882-cc1cf144-28bb-4957-abe4-85a63c0c3166.png">

<br>
<br>

### Activate Subscription Request
<img width="737" alt="image" src="https://user-images.githubusercontent.com/94133633/211658765-b946494f-c458-486d-827a-771c0a0d463d.png">

<br>
<br>

### Function: View Subscriptions (Requests and Active)

=> Requests: https://portal-backend.dev.demo.catena-x.net/api/Apps/provided/subscription-status?page=0&size=15&statusId=PENDING
=> Active: https://portal-backend.dev.demo.catena-x.net/api/Apps/provided/subscription-status?page=0&size=15&statusId=ACTIVE

<br>
<br>

### Function: Sorting

=> By Customer A-Z: https://portal-backend.dev.demo.catena-x.net/api/Apps/provided/subscription-status?page=0&size=15&sorting=CompanyNameDesc
=> By Offer: https://portal-backend.dev.demo.catena-x.net/api/Apps/provided/subscription-status?page=0&size=15&sorting=OfferIdAsc

<br>
<br>