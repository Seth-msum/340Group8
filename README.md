## Pre-Reqs

#### Have IDLE (Python 3.11 IDE) installed
#### Have Visual Studio Code installed

## Building

#### Clone the repo into Visual studio code using the command line by pressing ctrl+shift+p
#### type in clone from GitHub and copy and paste the url for the repo
#### Create a new branch by using the command line and typing git: create branch
#### Using source control (ctrl+shift+g) commit & push changes

## Running

#### While in visual studio code select main.py and select run


# Inventory Tracking Application

This application will provide store employees and customers with information about available products.

## Description

This application will be used primarily by large stores that have a large variety and quantity of goods that they sell, but it will still be useful for smaller stores if they were to use it. Our application will allow store employees to keep track of how much of an item there is as well as give managers data about how much and how often items are sold so that they can be more prepared to order more of things before they run out. The app will also allow customers to see how much of an item is left in stock as well as telling them what aisle they can find the item in.

## Stakeholders and their Interests

### Software Developer and Maintainer
- Manageable (Easy to add and delete items)
- Low operating cost
- easy to deploy and change

### Store Owner(s)
- Cheap (low up front cost and upkeep cost)
- simple to set up
- immediate results
- high ROI
- doesn't negatively affect customer experience
- reduce operational costs and allows store to run more smoothly

### Customers
- Makes things more likely to be in stock when they need them
- Allows them to check availablity before going to the store

### Employees
- Accurate
- Easy to use
- Easy to understand and apply

## Personas

### Jay - Employee (Seth Bentley)

Jay is 30 years old and is the overnight stocker for a local store. Jay does not know much about computers or technology but is excited to learn how to use this new application to make his job easier. He currently uses a paper print out of the items to be stocked and where they need to be.

### Robert - Store Owner(Hayden Gagnon)

Robert is 54 years old and owns the local Target. He hopes to make his Target one of the top stores in the company with the most consistent selection available for customers. Robert is not very computer savvy but understands that the use of computer systems can help his store become more efficient and better for customers. He is willing to invest in systems for his business as long as those systems give benefits in return.

### Ben - Employee(Tomas Zamba)

Ben is 19 years old, he works full-time and in the evenings he attends his online classes. He is majoring in business administration, hoping to be a business owner one day. Ben has been well-shaped with computers since he was about seven years he has always been playing with electronic devices. He was also repairing and trying to download games, videos, and images from the internet. Ben is eager to understand the new application inside and out.

### Jaylin - Customer(Tomas Zamba)

Jaylin loves Target, her grandmother and grandfather always brought her to target after church sermons. They would walk into Target looking for exquisite clothes as well the perfumes. At the end of their trip, her grandfather always both her ice coffee from Starbucks. Furthermore, since Jaylin recently got a child, she only has time to walk in the aisle for a short time. She knows other stores have an application where she can see their inventory. However, she does not want to be disloyal to Target. Additionally, Jaylin is not tech-savvy, after all. She only used her mobile phone when calling or messaging her friends or family. However, she is willing to learn more about operating the mobile phone effectively when Target has an application where she can see the inventory.

## User Stories

### Jaylin- Customer(Tomas Zamba)

Jaylin is tremendously happy that Target has introduced its app. The day she heard the great news, she downloaded the app to test it out. She hopes the application displays the number of items left and on which aisle she can find it. This time she wanted to spend less time in the store. She hoped that the application would be up to date every few seconds and accurately display their inventory.

### Ben - Employee(Tomas Zamba)

Ben sees a lady( Jaylin) in discomfort, gazing at her phone and into the store. It seems like Jaylin is trying to find an item. Ben approaches Jaylin with a calm and welcoming voice. After exchanging a few words with Jaylin, Ben figured out it was Jaylin's first time utilizing the application. Ben takes out a tablet and opens the same application; however, Ben's application is more detailed than the customers. Ben shows the Lady how to operate the app. After typing in the item name, numerous similar items come up. After a minute of glazing through the items, the Lady clicks on the items she was looking for on Ben's tablet. After she clicked, the app displayed the item's quantity and the aisle where to find it. After Ben explained the whole process, he walked the Lady to the correct aisle, and Jaylin thanked Ben for his help as she walked toward the register.

### Ben - Employee(Hayden Gagnon)

While restocking shelves Ben notices that there are some items that he doesn't have enough of to fill the shelves. Ben checks the app to see if they have more in stock in the back or if he will have to notify his manager that they need to order more of these items. Ben quickly sees in the app that there is plenty of stock in the back and is able to go retrieve these items to finish stocking the shelves. 

### Jaylin - Customer(Hayden Gagnon)

Jaylin was really excited when she heard aout Target getting an app that tracked inventory so she could plan her trip to the store before she left her house. She would make her grocery list and before heading to target would check to make sure they have everything in stock so that she wouldn't have any surprises when she got there. Because of this she was able to notice that Target didn't have any chicken breasts available and was able to plan a meal that used a different meat than chicken before going to Target. Because of the app Jaylin had a much better shopping experience at Target than she would have if the app wasn't available.

### Robert - Owner(Seth Bentley)

Robert just recieved his first weekly report of sales from the application and notices that he sold many more of one brand of soda than another. He contacts his manager and informs them to start more prominently displaying this higher selling brand and to have a larger stock on hand. Robert is happy to find that this lead to higher profits from soda sales.

### Jay - Employee(Seth Bentley)

Jay started his shift by checking the application for which ailse needed the most inventory stocked. He was able to see all the items he needed from the back store room. Jay appriciates how fast and efficent the application has made his job. 
## Use Case Diagram

![Alt text](./DocImages/usecasediagram.png "Use Case Diagrams")

## Requirements

### Functional
1. Worker must be able to see how much of a given product is available by searching for name of product, or the item number.
2. Stocking clerk must be able to add to the available inventory when a delivery arrives.
3. Customer can see available items with price and ailse location.
4. Worker must be able to edit available stock after a manual inventory count.
5. Manager must have the ability to adjust the prices of products.
6. Manager can manually refresh the current inventory count of a single item or a group (outside of normal updates).
7. Owner and manager have access to report of number of items recieved and sold weekly.

### Non-Functional
1. Customer can access the inventory count, ailse, and price without signing in. (Manager, owner, and employees have access to different tiers of access)
2. All changes to inventory count, price, and location can be easily undone.
3. Reports can be generated in under 3 hours during overnight hours.

### Non-Requirements
1. No offline support is required.
