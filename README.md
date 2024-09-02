# CraftyCommerce

CraftyCommerce is an e-commerce platform aimed at providing seamless shopping experiences for artisans and small businesses. This project is a collaborative effort by a fictional development team to explore modern web development practices.

## Development Team
- **Alice Smith** - Frontend Developer
- **Bob Johnson** - Backend Developer
- **Charlie Davis** - UI/UX Designer

# CraftyCommerce

## Project Overview
CraftyCommerce is a fictional e-commerce platform developed to practice and demonstrate Git workflows in a team environment.

## Branches Overview
### Branch: feature-user-authentication
- **Purpose:** Implemented user authentication using OAuth.
- **Features:** Login, registration, and password reset functionality.

### Branch: feature-payment-gateway
- **Purpose:** Integrated payment gateway for processing transactions.
- **Features:** Supported payment methods include credit/debit cards and PayPal.

## Challenges Faced
- Resolving merge conflicts between feature-user-authentication and feature-payment-gateway.
- Managing dependencies across different branches.

## Lessons Learned
Working on this project highlighted the importance of clear communication and frequent commits. We learned the value of feature branches in isolating work and how to effectively manage merge conflicts.

## Final Repository Submission
The final version of the project is available at the following URL: [CraftyCommerce Repository](https://github.com/Praveen-kush/CraftyCommerce)



Dell@DESKTOP-JC58O94 MINGW64 ~ (main)
$ git clone https://github.com/Praveen-kush/CraftyCommerce.git
Cloning into 'CraftyCommerce'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

Dell@DESKTOP-JC58O94 MINGW64 ~ (main)
$ cd CraftyCommerce

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (main)
$ touch .gitignore

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (main)
$ git add .gitignore

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (main)
$ git commit -m "Add .gitignore to exclude unnecessary files"
[main 68ff6b3] Add .gitignore to exclude unnecessary files
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (main)
$ git checkout -b feature-product-listing
Switched to a new branch 'feature-product-listing'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ git checkout -b feature-shopping-cart
Switched to a new branch 'feature-shopping-cart'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git checkout -b feature-customer-reviews
Switched to a new branch 'feature-customer-reviews'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git checkout feature-product-listing
Switched to branch 'feature-product-listing'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ echo "console.log('Product Listing Feature');" > product-listing.js

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ git add product-listing.js
warning: in the working copy of 'product-listing.js', LF will be replaced by CRLF the next time Git touches it

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ git commit -m "Add product listing functionality"
[feature-product-listing 27ce7d9] Add product listing functionality
 1 file changed, 1 insertion(+)
 create mode 100644 product-listing.js

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ git checkout feature-shopping-cart
Switched to branch 'feature-shopping-cart'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ echo "console.log('Shopping Cart Feature');" > shopping-cart.js

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git add shopping-cart.js
warning: in the working copy of 'shopping-cart.js', LF will be replaced by CRLF the next time Git touches it

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git commit -m "Add shopping cart functionality"
[feature-shopping-cart 9c57c41] Add shopping cart functionality
 1 file changed, 1 insertion(+)
 create mode 100644 shopping-cart.js

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git checkout feature-customer-reviews
Switched to branch 'feature-customer-reviews'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ echo "console.log('Customer Reviews Feature');" > customer-reviews.js

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git add customer-reviews.js
warning: in the working copy of 'customer-reviews.js', LF will be replaced by CRLF the next time Git touches it

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git commit -m "Add customer reviews functionality"
[feature-customer-reviews e2c584c] Add customer reviews functionality
 1 file changed, 1 insertion(+)
 create mode 100644 customer-reviews.js

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git checkout feature-product-listing
Switched to branch 'feature-product-listing'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ git pull origin master
fatal: couldn't find remote ref master

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-product-listing)
$ git checkout feature-shopping-cart
Switched to branch 'feature-shopping-cart'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git pull origin master
fatal: couldn't find remote ref master

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git checkout feature-customer-reviews
Switched to branch 'feature-customer-reviews'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git pull origin master
fatal: couldn't find remote ref master

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git push origin feature-product-listing
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/CraftyCommerce.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git push origin feature-shopping-cart
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/CraftyCommerce.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git push origin feature-customer-reviews
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Praveen-kush/CraftyCommerce.git/'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git checkout master
error: pathspec 'master' did not match any file(s) known to git

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git pull origin master
fatal: couldn't find remote ref master

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git branch --list
* feature-customer-reviews
  feature-product-listing
  feature-shopping-cart
  main

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git checkout branch-name
error: pathspec 'branch-name' did not match any file(s) known to git

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-customer-reviews)
$ git checkout feature-shopping-cart
Switched to branch 'feature-shopping-cart'

Dell@DESKTOP-JC58O94 MINGW64 ~/CraftyCommerce (feature-shopping-cart)
$ git log
commit 9c57c41a655c1be9b46e27afacc841ab702892e7 (HEAD -> feature-shopping-cart)
Author: Praveen-kush <praveenkushwaha0468@gmail.com>
Date:   Mon Sep 2 22:35:44 2024 +0530

    Add shopping cart functionality

commit 68ff6b35ec0e2f0e000d8b651b58f51d36ec74df (main)
Author: Praveen-kush <praveenkushwaha0468@gmail.com>
Date:   Mon Sep 2 22:12:45 2024 +0530

    Add .gitignore to exclude unnecessary files

commit b04225fdcbbdcb84f9e580a2e0ad186e29071449 (origin/main, origin/HEAD)
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 22:08:56 2024 +0530

    Update README.md

commit 372e09d19c3a0a41c19b8f6833a37a921bfb92e5
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 22:06:26 2024 +0530

    Update README.md

commit ddf94b2c69782bf80371a2133ffac0ba3dc638ed
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 22:04:31 2024 +0530

    Initial commit
...skipping...
commit 9c57c41a655c1be9b46e27afacc841ab702892e7 (HEAD -> feature-shopping-cart)
Author: Praveen-kush <praveenkushwaha0468@gmail.com>
Date:   Mon Sep 2 22:35:44 2024 +0530

    Add shopping cart functionality

commit 68ff6b35ec0e2f0e000d8b651b58f51d36ec74df (main)
Author: Praveen-kush <praveenkushwaha0468@gmail.com>
Date:   Mon Sep 2 22:12:45 2024 +0530

    Add .gitignore to exclude unnecessary files

commit b04225fdcbbdcb84f9e580a2e0ad186e29071449 (origin/main, origin/HEAD)
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 22:08:56 2024 +0530

    Update README.md

commit 372e09d19c3a0a41c19b8f6833a37a921bfb92e5
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 22:06:26 2024 +0530

    Update README.md

commit ddf94b2c69782bf80371a2133ffac0ba3dc638ed
Author: Praveen Maurya <99396223+Praveen-kush@users.noreply.github.com>
Date:   Mon Sep 2 22:04:31 2024 +0530

    Initial commit
(END)

