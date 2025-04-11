### Problem Statement: Find My Feast 🍽️ 

John is a passionate foodie who loves to explore new eateries around his city. However, every time he tries to find a restaurant serving his favourite food at a quality, he finds acceptable, he ends up spending hours browsing through endless online reviews and ratings. This often leaves him frustrated and struggling to make a choice. 

To solve John’s struggle, a **web application** named **“Find My Feast”** is envisioned. The application will help food lovers like John to discover local restaurants that serve their favourite dishes, meeting their desired level of quality and rating. 

### Objective: 
To build a web application allowing users to search for restaurants serving their preferred food choices, filtered by a threshold rating provided by the user.  

### Example: 
As a user, John wants to find a restaurant that serves his favourite food, such as *Pizza*, with a minimum rating of **4 stars** or above. He enters his **food choice** (*Pizza*) and the **desired rating** (*4+*) into the application.  

The application fetches the list of restaurants meeting his criteria, based on the schema data. Within seconds, John gets a curated list: 

- **Pizza Hut (Bengaluru)** serves *Pizza* with a rating of *4*. 
- **Dominos (Bengaluru)** serves *Pizza* with a rating of *5*. 

John can quickly make his choice based on this information and enjoy a delightful meal without any hassle. 

---

### JSON Sample:

```json
[
  {
    "Name": "McDonalds",
    "City": "Bengaluru",
    "Menu": ["Burger-4", "Fries-4"]
  },
  {
    "Name": "Burger King",
    "City": "Bengaluru",
    "Menu": ["Burger-4", "Shakes-3"]
  },
  {
    "Name": "Pizza Hut",
    "City": "Bengaluru",
    "Menu": ["Pizza-4", "Soft drink-4"]
  },
  {
    "Name": "Dominos",
    "City": "Bengaluru",
    "Menu": ["Pizza-5", "Bread stick-3"]
  },
  {
    "Name": "McDonalds",
    "City": "Delhi",
    "Menu": ["Burger-4", "Fries-4"]
  },
  {
    "Name": "Pizza Hut",
    "City": "Noida",
    "Menu": ["Pizza-2", "Soft drink-4"]
  }
]
