for backend api data

http://localhost:8080

/user/signup    -POST 
/user/login    -POST


/product/mens    -GET
/product/womens    -GET

/product/mens/shoes    -GET
/product/mens/gift    -GET
/product/mens/clotes    -GET

/product/womens/shoes    -GET
/product/womens/gift    -GET
/product/womens/clotes    -GET

/product/:productId {pass productId from params}


/wishlist/get      -GET {pass token from the Headres}
/wishlist/add      -POST {pass toke from the Headers } {pass productId from payload}
/wishlist/delete/:wishlistId      -DELETE  {pass token from the Headres} {pass wishlistId from the params}



/cart/get      -GET {pass token from the Headres}
/cart/add      -POST  {pass toke from the Headers } {pass productId from payload}
/cart/delete/:cardId      -DELETE  {pass token from the Headres} {pass cartId from the params}