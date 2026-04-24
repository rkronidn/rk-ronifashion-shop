<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RK Roni Fashion Shop</title>
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Hind Siliguri', sans-serif; }
        body { background-color: #f4f6f9; color: #333; text-align: center; }
        header { background: #ff4757; color: white; padding: 30px 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .container { max-width: 1100px; margin: 30px auto; padding: 0 15px; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .product-card { background: white; border-radius: 15px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.1); padding-bottom: 20px; border: 1px solid #eee; }
        .product-img { width: 100%; height: 350px; object-fit: cover; background: #ddd; }
        .info { padding: 15px; }
        .price { color: #ff4757; font-size: 22px; font-weight: bold; margin-bottom: 15px; }
        .whatsapp-btn { background: #25D366; color: white; text-decoration: none; padding: 12px 20px; border-radius: 50px; font-weight: bold; display: inline-block; }
        footer { margin-top: 50px; padding: 20px; background: #2f3542; color: white; }
    </style>
</head>
<body>

<header>
    <h1>RK Roni Fashion Shop</h1>
    <p>সেরা মানের প্রিমিয়াম পাঞ্জাবি ও পোশাকের সংগ্রহ</p>
</header>

<div class="container">
    <div class="product-grid">
        
        <div class="product-card">
            <img src="IMG_20260424_104334.jpg" class="product-img" alt="শার্ট 1">
            <div class="info">
                <h3>প্রিমিয়াম ব্ল্যাক পাঞ্জাবি</h3>
                <p class="price">৳ ১,৫৫০</p>
                <a href="https://wa.me/8801625686012?text=আমি এই পাঞ্জাবিটি অর্ডার করতে চাই" class="whatsapp-btn">WhatsApp-এ অর্ডার দিন</a>
            </div>
        </div>

        <div class="product-card">
            <img src="860f93f8cb9bcd15186ed7a18642a8a1c97a5a8e.jpg" class="product-img" alt="শার্ট 2">
            <div class="info">
                <h3>এক্সক্লুসিভ হোয়াইট পাঞ্জাবি</h3>
                <p class="price">৳ ১,৬০০</p>
                <a href="https://wa.me/8801700000000?text=আমি এই সাদা পাঞ্জাবিটি অর্ডার করতে চাই" class="whatsapp-btn">WhatsApp-এ অর্ডার দিন</a>
            </div>
        </div>

    </div>
</div>

<footer>
    <p>&copy; ২০২৬ | RK Roni Fashion Shop | দোহর, নবাবগঞ্জ</p>
</footer>

</body>
</html>
