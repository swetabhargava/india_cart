
## Features
- **App**
  - User Authentication using  (BCrypt gem)
  - ADMIN and User roles 
  - Products icons saved on Google Cloud or Amazon Cloud
  - Email Account Activation
  - Users can follow other users
  - Twitter like feed mechenism for followers
  - Beautiful Search Bars
  - Beautiful Paginations
  - Users can post articles
  - Proceed products to cart
  - Make Orders
  - Edit , destroy orders (Admin)
- _**Working on it**_
  - - Implement State Machine
  - - Use more Ajax requests
  - - Implementing tickets
  - - Implementing shipping

Images from version V1.0


| Home  | Users
|:-:|:-:|
| ![First](https://github.com/swetabhargava/india_cart/blob/master/app/assets/images/home.png?raw=true) | ![Sec](https://github.com/swetabhargava/india_cart/blob/master/app/assets/images/users.png?raw=true) |

| Orders  | Articles
|:-:|:-:|
| ![First](https://github.com/swetabhargava/india_cart/blob/master/app/assets/images/order.png?raw=true) | ![Sec](https://github.com/swetabhargava/india_cart/blob/master/app/assets/images/article.png?raw=true) |

Cart
![cart](https://github.com/swetabhargava/india_cart/blob/master/app/assets/images/cart.png?raw=true)


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly: THE TESTS FAIL (Because i didn't corrected them all loool! )

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
