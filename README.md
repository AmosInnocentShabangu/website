
# Online Product Ordering Website

## Description
A multi-page website that allows customers to browse products and place orders using a product code system.

The website contains 27 pages where users can:
- Browse available items
- View product details with unique product codes
- Click an "Order Now" button
- Submit the product code and contact details in the comment section
- The website automatically sends order details to the admin via email

## Features
- Multi-page product catalog (27 pages)
- Unique product codes for each item
- "Order Now" functionality
- Comment-based order submission
- Email notification for new orders
- Mobile-friendly design

## Technologies Used
- HTML
- CSS
- JavaScript
- Xneelo
- formspree

## How Ordering Works
1. Customer browses products
2. Customer selects an item and clicks **Order Now**
3. Customer is redirected to the comment section
4. Customer enters:
   - Product code
   - Contact details
5. Order details are sent directly to admin email


### Script for index.html
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/jpg" href="images/am icon.jpg">
    <title>AM Online store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="search-box">
        <input type="text" id="searchInput" placeholder="Search products..." onkeyup="searchProduct()">
        <span class="search-icon">🔍</span>
    </div>

    <div class="header-icons">
        <div class="icon">👤</div>
        <button class="icon" onclick="scrollToComment()">
    🛒
</button>
    </div>
    
        <h1>AM Online Store</h1>
    </header>

    <nav>
    <div class="navbar">
        <ul>
            <li><a href="index.html">Home</a> </li>
            <div class="Women">
            <li ><a href="Hwomen.html">Women</a>
                <div class="Women">
                    <a href="Women.html">clothes</a>
                    <a href="Shoes.html">Shoes</a>
                    <a href="Hair.html">Hair</a>
                    <a href="Bags.html">Bags</a>
                   
                </div>
            </div>

            <div class="Men">
            <li><a href="Hmen.html">Men</a> 
                <div class="Men">
                    <a href="clothes.html">clothes</a>
                    <a href="T-Shirts.html">T-Shirts</a>
                </div>
            </div>

            <div class="Kids">
            <li><a href="kids.html">Kids</a>
                <div class="Kids">
                    <a href="Kclothes.html">clothes</a>
                    <a href="Kshoes.html">Shoes</a>
                    <a href="Toys.html">Toys</a>
                </div>
            </div>

            <div class="School">
            <li><a href="School.html">School</a>
                <div class="School">

                </div>
            </div>
            <div class="House">
            <li><a href="house.html">House</a>
                <div class="House">
                    <a href="linens.html">linens</a>

                </div>
            </div>


            <li><a href="jewellery.html">Jewellery</a>


            <li><a href="loundry.html">Loundry</a></li>



            <li><a href="Other.html">Other</a></li>
        </ul>
    </div>
    </nav>
    <main>
        <div class="promo-banner">
  <h2>Scroll down for new special deals</h2>
  <p>Find special deals from just R29.99, look good always</p>
</div>
    <div id="product-list">
        <div class="gallery">
        <a href="wc1.jpeg">
                <img src="women/wc1.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Dress</h3>
                <p id="code">Code=wc1</p>
                <p>ORDER NOW</p>
                <p>R 259,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="women/wc22.jpeg">
                <img src="women/wc22.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>jumpsuit</h3>
                <p id="code">Code=wc22</p>
                <p>ORDER NOW</p>
                <p>R R249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/wc23.jpeg">
                <img src="women/wc23.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>jumpsuit</h3>
                <p id="code">Code=wc23</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/wc24.jpeg">
                <img src="women/wc24.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>jumpsuit</h3>
                <p id="code">Code=wc24</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/wc25.jpeg">
                <img src="women/wc25.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Tight</h3>
                <p id="code">Code=wc25</p>
                <p>ORDER NOW</p>
                <p>R 119,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/wc26.jpeg">
                <img src="women/wc26.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Tight</h3>
                <p id="code">Code=wc26</p>
                <p>ORDER NOW</p>
                <p>R 119,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/wc27.jpeg">
                <img src="women/wc27.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>jumpsuit</h3>
                <p id="code">Code=wc27</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/ws1.jpeg">
                <img src="women/ws1.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=ws1</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="women/ws2.jpeg">
                <img src="women/ws2.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=ws2</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="women/ws17.jpeg">
                <img src="women/ws17.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>shoes</h3>
                <p id="code">Code=ws17</p>
                <p>ORDER NOW</p>
                <p>R 119,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="women/ws6.jpeg">
                <img src="women/ws6.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=ws6</p>
                <p>ORDER NOW</p>
                <p>R 279,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
               <div class="gallery">
            <a href="men/mc1.jpeg">
                <img src="men/mc1.jpeg" alt="T-Shirt"></a>
            <div class="description"> <h3>T-Shirt</h3>
                <p id="code">Code=mc1 </p>
                <p>ORDER NOW</p>
                <p>R 279,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="men/mc2.jpeg">
                <img src="men/mc2.jpeg" alt="T-Shirt"></a>
            <div class="description"> <h3>T-Shirt</h3>
                <p id="code">Code=mc2 </p>
                <p>ORDER NOW</p>
                <p>R 279,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="men/mc3.jpeg">
                <img src="men/mc3.jpeg" alt="T-Shirt"></a>
            <div class="description"> <h3>T-Shirt</h3>
                <p id="code">Code=mc3 </p>
                <p>ORDER NOW</p>
                <p>R 279,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="men/mc4.jpeg">
                <img src="men/mc4.jpeg" alt="T-Shirt"></a>
            <div class="description"> <h3>T-Shirt</h3>
                <p id="code">Code=mc4</p>
                <p>ORDER NOW</p>
                <p>R 279,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="men/mc5.jpeg">
                <img src="men/mc5.jpeg" alt="T-Shirt"></a>
            <div class="description"> <h3>T-Shirt</h3>
                <p id="code">Code=mc5</p>
                <p>ORDER NOW</p>
                <p>R 279,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="men/mc6.jpeg">
                <img src="men/mc6.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc6</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="men/mc6.jpeg">
                <img src="men/mc6.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc6</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="men/mc7.jpeg">
                <img src="men/mc7.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc7</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="men/mc8.jpeg">
                <img src="men/mc8.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc8</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc9.jpeg">
                <img src="men/mc9.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc9</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc10.jpeg">
                <img src="men/mc10.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc10</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
               <div class="gallery">
            <a href="Jewellary/jr18.jpeg">
                <img src="Jewellary/jr18.jpeg" alt="Jewellary">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr18</p>
                <p>ORDER NOW</p>
                <p>R 799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="Jewellary/jr19.jpeg">
                <img src="Jewellary/jr19.jpeg" alt="Jewellary">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr19</p>
                <p>ORDER NOW</p>
                <p>R R799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="Jewellary/jr15.jpeg">
                <img src="Jewellary/jr15.jpeg" alt="Jewellary">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr15</p>
                <p>ORDER NOW</p>
                <p>R 799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="Jewellary/jr1.jpeg">
                <img src="Jewellary/jr1.jpeg" alt="red dress">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr1</p>
                <p>ORDER NOW</p>
                <p>R 799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="Jewellary/jr2.jpeg">
                <img src="Jewellary/jr2.jpeg" alt="red dress">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr2</p>
                <p>ORDER NOW</p>
                <p>R 799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="Jewellary/jr3.jpeg">
                <img src="Jewellary/jr3.jpeg" alt="red dress">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr3</p>
                <p>ORDER NOW</p>
                <p>R 799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="Jewellary/jr4.jpeg">
                <img src="Jewellary/jr4.jpeg" alt="red dress">
            </a>
            <div class="description"> <h3>Bracelet</h3>
                <p id="code">Code=jr4</p>
                <p>ORDER NOW</p>
                <p>R 799,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="Jewellary/jr5.jpeg">
                <img src="Jewellary/jr5.jpeg" alt="red dress">
            </a>
            <div class="description"> <h3>Watch</h3>
                <p id="code">Code=jr5</p>
                <p>ORDER NOW</p>
                <p>R 149,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
               <div class="gallery">
                 <a href="other/or28.jpeg">
                <img src="other/or28.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or28</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or26.jpeg">
                <img src="other/or26.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or26</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                 <a href="other/or27.jpeg">
                <img src="other/or27.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or27</p>
                <p>ORDER NOW</p>
                <p>R 299,99/p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or29.jpeg">
                <img src="other/or29.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or29
                </p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or30.jpeg">
                <img src="other/or30.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or30</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or31.jpeg">
                <img src="other/or31.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or31</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or32.jpeg">
                <img src="other/or32.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or32</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or33.jpeg">
                <img src="other/or33.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or33</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or34.jpeg">
                <img src="other/or34.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or34</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or35.jpeg">
                <img src="other/or35.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or35</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                 <a href="other/or37.jpeg">
                <img src="other/or37.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or37</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or38.jpeg">
                <img src="other/or38.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or38</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
                 <a href="other/or39.jpeg">
                <img src="other/or39.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or39</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
               <div class="gallery">
            <a href="kids/kd1.jpeg">
                <img src="kids/kd1.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd1</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="kids/kd2.jpeg">
                <img src="kids/kd2.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd2
                </p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="kids/kd3.jpeg">
                <img src="kids/kd3.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd3
                </p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="kids/kd4.jpeg">
                <img src="kids/kd4.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd4</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="kids/kd5.jpeg">
                <img src="kids/kd5.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd5</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
        
            </div>
        
        </div>
         <div class="gallery">
            <a href="kids/kd6.jpeg">
                <img src="kids/kd6.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd6</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="kids/kd7.jpeg">
                <img src="kids/kd7.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd7</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="kids/kd8.jpeg">
                <img src="kids/kd8.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd8</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="kids/kd9.jpeg">
                <img src="kids/kd9.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd9</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="kids/kd10.jpeg">
                <img src="kids/kd10.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd10</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="kids/kd11.jpeg">
                <img src="kids/kd11.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd11</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="kids/kd12.jpeg">
                <img src="kids/kd12.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd12</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="kids/kd13.jpeg">
                <img src="kids/kd13.jpeg" alt="Shirt"></a>
            <div class="description"> <h3>Shirt</h3>
                <p id="code">Code=kd13</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
               <div class="gallery">
            <a href="bags/bg1.jpeg">
            <img src="bags/bg1.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg1</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg3.jpeg">
            <img src="bags/bg3.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg3</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg4.jpeg">
            <img src="bags/bg4.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg4</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="bags/bg5.jpeg">
            <img src="bags/bg5.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg5</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="bags/bg5.jpeg">
            <img src="bags/bg5.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg5
                </p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg6.jpeg">
            <img src="bags/bg6.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg6</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg7.jpeg">
            <img src="bags/bg7.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg7</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="bags/bg7.jpeg">
            <img src="bags/bg7.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg7</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="bags/bg7.jpeg">
            <img src="bags/bg7.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg7</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg8.jpeg">
            <img src="bags/bg8.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg8</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg9.jpeg">
            <img src="bags/bg9.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg9</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg10.jpeg">
            <img src="bags/bg10.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg10</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg11.jpeg">
            <img src="bags/bg11.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg11</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg12.jpeg">
            <img src="bags/bg12.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg12</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg13.jpeg">
            <img src="bags/bg13.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg13</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg14.jpeg">
            <img src="bags/bg14.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg14</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg15.jpeg">
            <img src="bags/bg15.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg15</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg16.jpeg">
            <img src="bags/bg16.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg16</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg17.jpeg">
            <img src="bags/bg17.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg17</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg18.jpeg">
            <img src="bags/bg18.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg18</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg19.jpeg">
            <img src="bags/bg19.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg19
                </p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg20.jpeg">
            <img src="bags/bg20.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg20</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg21.jpeg">
            <img src="bags/bg21.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg21</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg22.jpeg">
            <img src="bags/bg22.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg15</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg23.jpeg">
            <img src="bags/bg23.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg23</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg24.jpeg">
            <img src="bags/bg24.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg24</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg25.jpeg">
            <img src="bags/bg25.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg25</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg26.jpeg">
            <img src="bags/bg26.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg26</p>
                <p>ORDER NOW</p>
                <p>R499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="bags/bg27.jpeg">
            <img src="bags/bg27.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg27</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
                <a href="other/or1.jpeg">
                <img src="other/or1.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or1 </p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
                <a href="other/or2.jpeg">
                <img src="other/or2.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or2</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
                <a href="other/or3.jpeg">
                <img src="other/or3.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or3 </p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
                <a href="other/or4.jpeg">
                <img src="other/or4.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or4</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
                <a href="other/or5.jpeg">
                <img src="other/or5.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or5 </p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
                <a href="other/or6.jpeg">
                <img src="other/or6.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or6</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
                <a href="other/or7.jpeg">
                <img src="other/or7.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or7
                </p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
                <a href="other/or8.jpeg">
                <img src="other/or8.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or8</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
                <a href="other/or9.jpeg">
                <img src="other/or9.jpeg" alt=""></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or1 </p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                <a href="other/or10.jpeg">
                <img src="other/or10.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or10</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                <a href="other/or11.jpeg">
                <img src="other/or11.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or11</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                <a href="other/or14.jpeg">
                <img src="other/or14.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Tissue Oil</h3>
                <p id="code">Code=or14</p>
                <p>ORDER NOW</p>
                <p>R 89,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                 <a href="other/or15.jpeg">
                <img src="other/or15.jpeg" alt=""></a>
               <div class="description"> <h3>Combo</h3>
                <p id="code">Code=or15</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>

                
            </div>
        
        </div>
                <div class="gallery">
                <a href="other/or18.jpeg">
                <img src="other/or18.jpeg" alt=""></a>
               <div class="description"> <h3>Tissue Oil</h3>
                <p id="code">Code=or18</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                <a href="other/or21.jpeg">
                <img src="other/or21.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Tissue Oil</h3>
                <p id="code">Code=or21</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                <a href="other/or24.jpeg">
                <img src="other/or24.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or24</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
                 <a href="other/or25.jpeg">
                <img src="other/or25.jpeg" alt="Perfume"></a>
               <div class="description"> <h3>Perfume</h3>
                <p id="code">Code=or25</p>
                <p>ORDER NOW</p>
                <p>R 129,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="women/ws7.jpeg">
                <img src="women/ws7.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>shoes</h3>
                <p id="code">Code=ws7</p>
                <p>ORDER NOW</p>
                <p>R 299,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="women/ws8.jpeg">
                <img src="women/ws8.jpeg" alt="Shoes">
            </a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=ws8</p>
                <p>ORDER NOW</p>
                <p>R 449,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="women/ws9.jpeg">
                <img src="women/ws9.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=ws9</p>
                <p>ORDER NOW</p>
                <p>R 449,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="women/ws10.jpeg">
                <img src="women/ws10.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=ws10</p>
                <p>ORDER NOW</p>
                <p>R 449,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        
                <div class="gallery">
            <a href="bags/bg1.jpeg">
            <img src="bags/bg1.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg1</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg3.jpeg">
            <img src="bags/bg3.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg3</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg4.jpeg">
            <img src="bags/bg4.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg4</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="bags/bg5.jpeg">
            <img src="bags/bg5.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg5</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="bags/bg5.jpeg">
            <img src="bags/bg5.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg5
                </p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg6.jpeg">
            <img src="bags/bg6.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg6</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="bags/bg7.jpeg">
            <img src="bags/bg7.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg7</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="bags/bg7.jpeg">
            <img src="bags/bg7.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg7</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="bags/bg7.jpeg">
            <img src="bags/bg7.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg7</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg8.jpeg">
            <img src="bags/bg8.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg8</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg9.jpeg">
            <img src="bags/bg9.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg9</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="bags/bg10.jpeg">
            <img src="bags/bg10.jpeg" alt="Bag">
            </a>
            <div class="description"> <h3>Bag</h3>
                <p id="code">Code=bg10</p>
                <p>ORDER NOW</p>
                <p>R 419,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="women/wc2.jpeg">
                <img src="women/wc2.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Dress</h3>
                <p id="code">Code=wc2</p>
                <p>ORDER NOW</p>
                <p>R 259,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="women/wc3.jpeg">
                <img src="women/wc3.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Dress</h3>
                <p id="code">Code=wc3</p>
                <p>ORDER NOW</p>
                <p>R 259,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="women/wc4.jpeg">
                <img src="women/wc4.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Dress</h3>
                <p id="code">Code=wc4</p>
                <p>ORDER NOW</p>
                <p>R 259,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="women/wc5.jpeg">
                <img src="women/wc5.jpeg" alt="Dress">
            </a>
            <div class="description"> <h3>Dress</h3>
                <p id="code">Code=wc5</p>
                <p>ORDER NOW</p>
                <p>R 259,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="lenins/ln1.jpeg">
                <img src="lenins/ln1.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs1</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="lenins/ln2.jpeg">
                <img src="lenins/ln2.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs2</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="lenins/ln3.jpeg">
                <img src="lenins/ln3.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs3</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
 
         <div class="gallery">
            <a href="lenins/ln4.jpeg">
                <img src="lenins/ln4.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs4</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="lenins/ln5.jpeg">
                <img src="lenins/ln5.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs5</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="lenins/ln6.jpeg">
                <img src="lenins/ln6.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs6</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="lenins/ln7.jpeg">
                <img src="lenins/ln7.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs7</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="lenins/ln8.jpeg">
                <img src="lenins/ln8.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs8</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="lenins/ln9.jpeg">
                <img src="lenins/ln9.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs9</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln10.jpeg">
                <img src="lenins/ln10.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs10</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln11.jpeg">
                <img src="lenins/ln11.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs11</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln12.jpeg">
                <img src="lenins/ln12.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs12</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln13.jpeg">
                <img src="lenins/ln13.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs13</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln14.jpeg">
                <img src="lenins/ln14.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs14</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln15.jpeg">
                <img src="lenins/ln15.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs15</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln16.jpeg">
                <img src="lenins/ln16.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs16</p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="lenins/ln17.jpeg">
                <img src="lenins/ln17.jpeg" alt="bed set">
            </a>
            <div class="description"> <h3>bed set</h3>
                <p id="code">Code=bs17
                </p>
                <p>AVAILABLE NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="kids/kd14.jpeg">
                <img src="kids/kd14.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd14</p>
                <p>ORDER NOW</p>
                <p>R 199,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="kids/kd15.jpeg">
                <img src="kids/kd15.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd15</p>
                <p>ORDER NOW</p>
                <p>R 199,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        <div class="gallery">
            <a href="kids/kd16.jpeg">
                <img src="kids/kd16.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd16</p>
                <p>ORDER NOW</p>
                <p>R 199,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
            <div class="gallery">
            <a href="kids/kd17.jpeg">
                <img src="kids/kd17.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd17</p>
                <p>ORDER NOW</p>
                <p>R 399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
             <div class="gallery">
            <a href="kids/kd45.jpeg">
                <img src="kids/kd45.jpeg" alt="jumpsuit"></a>
            <div class="description"> <h3>jumpsuit</h3>
                <p id="code">Code=kd18</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kids/kd47.jpeg">
                <img src="kids/kd47.jpeg" alt="Both"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=kd47</p>
                <p>ORDER NOW</p>
                <p>R 229,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Buy Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kids/kd49.jpeg">
                <img src="kids/kd49.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd49</p>
                <p>ORDER NOW</p>
                <p>R 399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kids/kd18.jpeg">
                <img src="kids/kd18.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd18</p>
                <p>ORDER NOW</p>
                <p>R 399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kd19.jpeg">
                <img src="kids/kd19.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd19</p>
                <p>ORDER NOW</p>
                <p>R399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kids/kd20.jpeg">
                <img src="kids/kd20.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd20</p>
                <p>ORDER NOW</p>
                <p>R 399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kids/kd21.jpeg">
                <img src="kids/kd21.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd21</p>
                <p>ORDER NOW</p>
                <p>R 399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                    <div class="gallery">
            <a href="kids/kd22.jpeg">
                <img src="kids/kd22.jpeg" alt="Shoes"></a>
            <div class="description"> <h3>Shoes</h3>
                <p id="code">Code=kd22</p>
                <p>ORDER NOW</p>
                <p>R 399,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
         <div class="gallery">
            <a href="men/mc11.jpeg">
                <img src="men/mc11.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc6</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc12.jpeg">
                <img src="men/mc12.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc12</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc13.jpeg">
                <img src="men/mc13.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc13</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc14.jpeg">
                <img src="men/mc14.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc14</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc15.jpeg">
                <img src="men/mc15.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Sports</h3>
                <p id="code">Code=mc15</p>
                <p>ORDER NOW</p>
                <p>R 499,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                <div class="gallery">
            <a href="men/mc16.jpeg">
                <img src="men/mc16.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc16</p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
             <div class="gallery">
            <a href="men/mc17.jpeg">
                <img src="men/mc17.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc17
                </p>
                <p>ORDER NOW</p>
                <p>R 249,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                        <div class="gallery">
            <a href="men/mc18.jpeg">
                <img src="men/mc18.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc18
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
                                <div class="gallery">
            <a href="men/mc19.jpeg">
                <img src="men/mc19.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc19
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
          <div class="gallery">
            <a href="men/mc20.jpeg">
                <img src="men/mc20.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc20 </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
            <div class="gallery">
            <a href="men/mc21.jpeg">
                <img src="men/mc21.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc21</p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
            </div>
        </div>
         <div class="gallery">
            <a href="men/mc22.jpeg">
                <img src="men/mc22.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc22
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        </div>
        <div class="gallery">
            <a href="men/mc23.jpeg">
                <img src="men/mc23.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc23
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
            </div>
        </div>
            <div class="gallery">
            <a href="men/mc24.jpeg">
                <img src="men/mc24.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc24
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
            </div>
        </div>
            <div class="gallery">
            <a href="men/mc25.jpeg">
                <img src="men/mc25.jpeg" alt="Sports"></a>
            <div class="description"> <h3>T-Shirt</h3>
                <p id="code">Code=mc25
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
            </div>
        </div>
          <div class="gallery">
            <a href="men/mc26.jpeg">
                <img src="men/mc26.jpeg" alt="Sports"></a>
            <div class="description"> <h3>Both</h3>
                <p id="code">Code=mc26
                </p>
                <p>ORDER NOW</p>
                <p>R 349,99</p>
                <button class="buy-btn" onclick="scrollToComment()">Order Now</button>
                
            </div>
        
        </div>
        </div>
<script>
function searchProduct() {
    let input = document.getElementById('searchInput').value.toLowerCase();
    let products = document.getElementsByClassName('gallery');

    for (let i = 0; i < products.length; i++) {
        let name = products[i].getElementsByTagName('h3')[0].innerText.toLowerCase();
        if (name.includes(input)) {
            products[i].style.display = "block";
        } else {
            products[i].style.display = "none";
        }
    }
}
</script>

<section id="comment-section">
    <h2>To buy or order leave a comment with the product <mark style="color: red;">code</mark> and your contact details don't forget to click on the send comment, we will contact you within 30 minutes. </h2>
    <form action="https://formspree.io/f/mblbrodo" method="POST" class="comment-form">
        <textarea id="comment-box" name="comment" placeholder="Write your comment...
code=RD1
0791234567
am@gmail.com" required></textarea>
        <button type="submit">Send Comment</button>
    </form>
</section>

<h1 id="bd"> </h1>
<script>
function scrollToComment() {
    document.getElementById('comment-section').scrollIntoView({ behavior: 'smooth' });
    const commentBox = document.getElementById('comment-box');
    commentBox.style.borderColor = 'red';
    setTimeout(() => {
        commentBox.style.borderColor = '#ccc';
    }, 3000);
}
</script>


    </main>
    <footer>
        <aside id="popi">
            <p>please note that the contact information provided will be used solely for business 
                purpose and will not be shared or used for any other reasons without prior consent
            </p>
        </aside>

        <section id="social">
            <h4>Social media accounts</h4>
            <p1>whatsapp</p1>
            <p>instagram</p>
            <p>youtube</p>
            <p>tick tok</p>
        </section>

        <article id="about">
            <h4>about us</h4>
            <p>A.M online store is a online shop the physical location is in nelpruit, providing service across South Africa </p>
        </article>
        
    </footer>
</body>
</html>

```
[index.html](https://github.com/user-attachments/files/24736838/index.html)

### Script for styke.css

```
header{
    text-align: center;
    padding: 15px 30px;
    justify-content: space-between;
    align-items: center;
}
.search-box {
    display: flex;
    align-items: center;
    background: white;
    padding: 8px 15px;
    border-radius: 10px;
    border: 1px solid #ccc;
    width: 260px;
    position: relative;
    margin-left: auto;
}

.search-box input {
    border: none;
    outline: none;
    width: 100%;
    font-size: 16px;
}
#hair{
    align-items: center;
    text-align: center;
    float: left;
}

.search-icon {
    font-size: 18px;
    margin-left: 8px;
    color: #555;
}

/* HEADER ICONS */
.header-icons {
    display: flex;
    align-items: center;
    gap: 25px;
}

.header-icons .icon {
    margin-top: -50px;
    font-size: 22px;
    cursor: pointer;
    transition: 0.3s;
}

.header-icons .icon:hover {
    transform: scale(1.1);
}

#button{
    padding: 10px;
    margin-left: 85%;
}
h1{
    margin-top: 5px;
    font-size: 55px;
    font-family: Georgia, 'Times New Roman', Times, serif;
    color:rgb(51, 4, 92);
    text-shadow: 3px 3px 5px hsl(0, 100%, 61%), -3px -3px 5px hsl(175, 100%, 61%) ;
}
.navbar ul{
    list-style-type: none;
    background-color: hsl(0, 7%, 45%);
    margin: 0px;
    padding: 0px;
    text-align: center;
    display: flex;
    border-radius: 8px;
    gap: 20px;
    overflow: hidden;
    flex-wrap: wrap;

}
.navbar a{
    color: white;
    text-decoration: none;
    padding: 10px;
    display: block;
    text-align: center;

}
.navbar a:hover{
    background-color: hsl(0, 3%, 6%);
}
.navbar li{
    align-items: center

}

.navbar{
    width: fit-content;
    display: flex;
    justify-content: center;   
    margin: 0 auto;           /
}
@media (max-width: 768px) {
    .navbar a {
        font-size: 14px; /* Slightly smaller */
        padding: 6px 10px;
    }
}
.Women .Women{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.Women :hover .Women{
    display: block;

}
.Men .Men{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.Men :hover .Men{
    display: block;

}
.Kids .Kids{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.Kids :hover .Kids{
    display: block;
}
.School .School{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.School :hover .School{
    display: block;
}
.Jewellery .Jewellery{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.Jewellery :hover .Jewellery{
    display: block;

}
.House .House{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.House :hover .House{
    display: block;

}
.Loundry .Loundry{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.Loundry :hover .Loundry{
    display: block;

}
.Other .Other{
    display: none;
    position: absolute;
    background-color: rgb(180, 117, 243);
}
.Other :hover .Other{
    display: block;

}
h2{
    color: rgb(89, 59, 116);
}
.promo-banner {
  background-color: #d69ae5; 
  padding: 30px 20px;
  text-align: center;
  border-radius: 15px;
  margin: 20px auto;
  width: 90%; /* Adjusts size, can change */
  max-width: 1200px; /* Prevents it from being too wide */
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.promo-banner h2 {
  font-size: 32px;
  font-weight: bold;
  margin-bottom: 10px;
  color: #222;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
}

.promo-banner p {
  font-size: 16px;
  color: #333;
  font-weight: 400;
}

.gallery{
    display: inline-block;
    border: 1px solid rgb(48, 45, 42);
    margin: 5px;
    width: 200px;
}
.gallery .description{
    padding: 5px;
    text-align: center;
}
.gallery:hover{
    border: 1px solid rgb(231, 221, 210);
}
.gallery img{
    width: 100%;
    height: 250px;
}
.ld:hover{
    border: 1px solid rgb(231, 221, 210);
}
.ld img{
    width: 480px;
    height: 480px;
}
.ld{
    display: inline-block;
    border: 1px solid rgb(48, 45, 42);
    margin: 5px;
    width: auto;
}
.ld .description{
    padding: 5px;
    text-align: center;
    float: right;
}
#code{
    color: red;
}
footer{

}
#popi{
    width: 20%;
    float: left;
    padding: 10px;
}
#social{
    width: 40%;
    float: left;
    padding: 10px;
}
#about{
    width: 30%;
    float: left;
    padding: 10px;
}
#wc{
    color: black;
    border-bottom: 3px solid black;
}
#bd{
    color: black;
    border-bottom: 3px solid black;
}
aside{
    width: auto;
    float: left;
    margin: 0px;
}
.navbarw ul{
    list-style-type: none;
    background-color: hsl(0, 7%, 45%);
    padding: center;
    margin: 0px;
    overflow: hidden;
    text-align: left;
}
.navbarw a{
    color: white;
    text-decoration: none;
    padding: 15px;
    display: block;
    text-align: left;

}
.navbarw a:hover{
    background-color: hsl(0, 3%, 6%);
}

.navbarw{
    display:;
}
.comment-form {
    width: 100%;
    max-width: 400px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.comment-form textarea {
    resize: auto;
    height: 50px;
    padding: 10px;
    border-radius: 5px;
    border: 2px solid #ccc;
    transition: border 0.9s ease;
}

.comment-form button {
    background: #6a1b9a;
    color: white;
    border: none;
    padding: 8px;
    border-radius: 5px;
    cursor: pointer;
}
.buy-btn {
    background-color: #6a1b9a;
    color: white;
    padding: 8px 15px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
}
```
[style.css](https://github.com/user-attachments/files/24736927/style.css)

### Other Scripts
- [kids.html](https://github.com/user-attachments/files/24737038/kids.html)
- [Kclothes.html](https://github.com/user-attachments/files/24737037/Kclothes.html)
- [Kclothes.html](https://github.com/user-attachments/files/24737031/Kclothes.html)
- [jewellery.html](https://github.com/user-attachments/files/24737029/jewellery.html)
- [jeans.html](https://github.com/user-attachments/files/24737024/jeans.html)
- [Hwomen.html](https://github.com/user-attachments/files/24737018/Hwomen.html)
- [house.html](https://github.com/user-attachments/files/24737015/house.html)
- [Home.html](https://github.com/user-attachments/files/24737011/Home.html)
- [Hmen.html](https://github.com/user-attachments/files/24737009/Hmen.html)
- [Hair.html](https://github.com/user-attachments/files/24737007/Hair.html)
- [furniture.html](https://github.com/user-attachments/files/24737004/furniture.html)
- [clothes.html](https://github.com/user-attachments/files/24737000/clothes.html)
- [books.html](https://github.com/user-attachments/files/24736996/books.html)
- [Bags.html](https://github.com/user-attachments/files/24736993/Bags.html)

## Screenshots

<img width="1366" height="616" alt="Screenshot 2026-01-20 at 14-50-08 AM Online store" src="https://github.com/user-attachments/assets/7738a686-9e83-40a3-9296-c63564bc7141" />
<img width="1366" height="616" alt="Screenshot 2026-01-20 at 14-49-24 AM Online store" src="https://github.com/user-attachments/assets/d11c0cb3-24dd-4359-9fe4-8666b8f5d90d" />
<img width="1366" height="616" alt="Screenshot 2026-01-20 at 14-50-30 AM Online store" src="https://github.com/user-attachments/assets/d0ef9b67-2ab8-4f48-9890-caccc1e4bf19" />

<img width="1366" height="768" alt="vsc2" src="https://github.com/user-attachments/assets/d6bb036c-4e37-43f8-ae58-a26690da4805" />
<img width="1366" height="768" alt="vsc" src="https://github.com/user-attachments/assets/8c6e73e2-170f-4108-9cee-6334779fd209" />


