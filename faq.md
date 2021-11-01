# FAQs
1. [Update my shop name or my (the boss) courier description](#update-shop)
2. [Add/Update a voice for voice calls](#add-voice)
3. [Add one courier](#add-courier)
4. [Update one courier's name and description](#update-courier)
5. [Show one courier](#show-courier)
6. [Add/Update one courier's vehicle photo](#add-vehicle-photo)
7. [Deliver shippings](#deliver-shippings)
8. [What is a day-offset from today?](#day-offset)
9. [Query shippings](#query)

## 1. Update my shop name or my (the boss) courier description<a id="update-shop"></a>
1. Edit  **BIO** or **First name** as new shop name
2. Edit  **Last name** as new courier description **[Optional]**
3. Run **/shop** and updated

## 2. Add/Update a voice for voice calls<a id="add-voice"></a>
1. Send a voice to @daolebot

## 3. Add one courier<a id="add-courier"></a>
1. Edit **First name** as the courier's name
1. Edit **Last name** as the courier's description **[Optional]**
2. Share the courier's contact to @daolebot

## 4. Update one courier's name and description<a id="update-courier"></a>
do **Add one courier** again

## 5. Show one courier<a id="show-courier"></a>
1. Share one courier's contact to @daolebot
2. Run **/shop** => **👥Staffs**,  select one courier

## 6. Add/Update one courier's vehicle photo<a id="add-vehicle-photo"></a>
1. Show one courier
2. Click **Update the photo** and send a photo

## 7. Deliver shippings<a id="deliver-shippings"></a>
1. Share a live location to @daolebot
2. Select shippings
3. Click **🚀🚀Optimize** to optimize routes **[Optional]**
4. Click **🧭 Easy Sort** to sort shippings **[Optional]**
5. Click **🚀 Go** and select one shipping
6. Click **Start**

## 8. What is a day-offset from today?<a id="day-offset"></a>
A day-offset is a integer number that is of days from today
`1 is tomorrow 0 is today, -1 is yesterday`

## 9. Query shippings<a id="query"></a>

```python
# search shippings on today
/query
# serach shippings on a date from day-offset
/query day-offset
/query 1 # tomorrow
/query -2 # the day before yesterday
# search shippings on a date
/query date-string
/query 12/05/2021
# search shippings with a customer's phone
/query phone
/query 0400123456
# search shippings with a customer phone and a date
/query phone date-string|day-offset
/query date-string|day-offset phone

```
