# FAQs
1. [Update my shop name or my (the boss) courier description](#update-shop)
2. [Add/Update a voice for voice calls](#add-voice)
3. [Add one courier](#add-courier)
4. [Update one courier's name and description](#update-courier)
5. [Show one courier](#show-courier)
6. [Add/Update one courier's vehicle photo](#add-vehicle-photo)
7. [Deliver shippings](#deliver-shippings)
8. [Query shippings](#query)

## 1. Update my shop name, the boss's avatar and description<a id="update-shop"></a>
1. Edit  **BIO** or **First name** as new shop name
2. Edit the avatar photo
3. Edit  **Last name** as new courier description **[Optional]**
4. Run **/shop a** and updated

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
2. OR Run **/shop** => **👥Staffs**,  select one courier

## 6. Add/Update one courier's vehicle photo<a id="add-vehicle-photo"></a>
1. Show one courier
2. Click **Update the photo** and send a photo

## 7. Deliver shippings<a id="deliver-shippings"></a>
1. Share a live location to @daolebot
2. Select shippings
3. **🚀 optimize** to optimize a route **[Optional]**
4. **🔢 Sort** to sort shippings **[Optional]**
5. **🚚 Go**
6. @daolebot sends the location of the destination
7. After delivery, **Finish**
8. **➡️ Next** for next one

## 8. Query shippings<a id="query"></a>

**/query** or **/q**

```python
# search shippings on today
/query

# serach shippings on a today offset
/query n
/query 1 # tomorrow
/query -2 # the day before yesterday
/query 7 # 7 days later

# search shippings on a date
/query dd/mm/yyyy
/query 12/05/2021

# search shippings with a customer's phone
/query phone
/query 0400123456

# search shippings with a customer phone and a date
/query phone dd/mm/yyyy|today-offset
/query dd/mm/yyyy|today-offset phone

```
