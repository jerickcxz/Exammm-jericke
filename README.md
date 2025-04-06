
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopee</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        
        /* Header Styles */
        .header {
            background-color: #f36f21;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        
        /* Navigation Styles */
        .navigation {
            background-color: #f0f0f0;
            padding: 10px;
        }
        .navigation ul {
            list-style: none;
            margin: 0;
            padding: 0;
        }
        .navigation li {
            display: inline-block;
            margin-right: 20px;
        }
        .navigation a {
            color: #333;
            text-decoration: none;
        }
        
        /* Main Content Styles */
        .main-content {
            width: 70%;
            float: left;
            padding: 20px;
        }
        
        /* Side Content Styles */
        .side-content {
            width: 100%;
            float: right;
            padding: 20px;
            background-color: #f0f0f0;
        }
        
        /* Footer Styles */
        .footer {
            background-color: #f36f21;
            color: #fff;
            padding: 20px;
            text-align: center;
            clear: both;
        }
        
        /* Product Styles */
        .product {
            padding: 20px;
            border: 1px solid #ddd;
            margin-bottom: 20px;
        }
        .product-image {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }
        .product-name {
            font-weight: bold;
            margin-bottom: 10px;
        }
        .product-price {
            font-size: 18px;
            color: #f36f21;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="header">
        <h1>JERICK RIVERA EXAM</h1>
    </div>
    
    <!-- Navigation Section -->
    <div class="navigation">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Categories</a></li>
            <li><a href="#">Deals</a></li>
            <li><a href="#">Cart</a></li>
        </ul>
    </div>
    
    <!-- Main Content Section -->
    <div class="container">
        <div class="main-content">
            <h2>Products</h2>
            <div class="product">
                <img src="1.jpeg" alt="Product 1" class="product-image">
                <div class="product-name">NBA BASKETBALL SHOES</div>
                <div class="product-price">₱359</div>
                <button>Add to Cart</button>
            </div>
            
            <div class="product">
                <img src="2.jpeg" alt="Product 2" class="product-image">
                <div class="product-name">ORIGINAL MOLTEN</div>
                <div class="product-price">₱599</div>
                <button>Add to Cart</button>
            </div>
                        <div class="product">
                <img src="3.jpeg" alt="Product 2" class="product-image">
                <div class="product-name">NIKE SOCKS</div>
                <div class="product-price">₱369</div>
                <button>Add to Cart</button>
            </div>
        </div>
        
        <!-- Side Content Section -->
        <div class="side-content">
            <h2>Categories</h2>
            <ul>
                <li>Electronics</li>
                <li>Fashion</li>
                <li>Home & Garden</li>
            </ul>
        </div>
    </div>
    
    <!-- Footer Section -->
    <div class="footer">
        <p>&copy; JERICK RIVERA</p>
    </div>
</body>
</html>
