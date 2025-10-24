
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Kafe R&A - Rasa & Aroma</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    
    <style>
        /* Variabel Warna untuk konsistensi */
        :root {
            --color-primary: #3d3d3d; /* Hitam/Cokelat Gelap untuk teks utama */
            --color-secondary: #a0522d; /* Sienna/Cokelat Tanah untuk aksen */
            --color-background: #fcf6e9; /* Krem Sangat Muda */
            --color-paper: #ffffff; /* Putih Bersih untuk kotak menu */
        }

        /* Gaya Dasar */
        body {
            font-family: 'Poppins', sans-serif; /* Font modern sans-serif */
            margin: 0;
            padding: 0;
            background-color: var(--color-background); /* Background Krem */
            color: var(--color-primary);
            line-height: 1.6;
        }
        .container {
            width: 90%;
            max-width: 700px;
            margin: 40px auto;
            padding: 30px;
            background-color: var(--color-paper);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08); /* Bayangan lembut */
            border-radius: 12px;
            border: 1px solid #eee;
        }

        /* Gaya Header (Logo) */
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        .logo-placeholder {
            /* Placeholder meniru gaya logo R&A DRINK */
            font-family: 'Playfair Display', serif; /* Font Serif untuk kesan elegan pada logo */
            font-size: 60px;
            font-weight: 700;
            color: #000;
            line-height: 0.8;
            position: relative;
            display: inline-block;
            margin-bottom: 10px;
        }
        .logo-text {
             display: block;
        }
        .drink-text {
            font-family: 'Poppins', sans-serif;
            font-size: 14px;
            font-weight: 600;
            color: var(--color-secondary);
            position: absolute;
            top: 25px; 
            right: -60px; 
            transform: rotate(15deg);
        }
        .caption {
            font-size: 14px;
            color: var(--color-secondary);
            margin-top: 10px;
            font-style: italic;
        }
        h1 {
            font-family: 'Playfair Display', serif;
            color: var(--color-primary);
            font-size: 32px;
            letter-spacing: 2px;
            border-bottom: 2px solid var(--color-secondary);
            padding-bottom: 8px;
            margin: 20px 0;
            text-align: center;
        }
        h2 {
            font-family: 'Playfair Display', serif;
            color: var(--color-secondary);
            font-size: 24px;
            margin-top: 40px;
            margin-bottom: 15px;
            padding-left: 10px;
            border-left: 4px solid var(--color-secondary); /* Aksen garis */
        }

        /* Gaya Item Menu */
        .menu-item {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            padding: 12px 0;
            border-bottom: 1px dashed #e0e0e0;
        }
        .item-info {
            flex-grow: 1;
            padding-right: 15px;
        }
        .menu-item-name {
            font-weight: 600;
            font-size: 17px;
            color: var(--color-primary);
        }
        .menu-item-description {
            font-size: 13px;
            color: #888;
            margin-top: 2px;
        }
        .menu-item-price {
            font-weight: 700;
            font-size: 17px;
            color: var(--color-secondary);
            white-space: nowrap; /* Mencegah harga pindah baris */
        }
        .menu-section:last-child .menu-item:last-child {
            border-bottom: none;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <div class="logo-placeholder">
                <span class="logo-text">R&A</span>
                <span class="drink-text">DRINK</span>
            </div>
            <p class="caption">Kafe R&A - Tempatnya Rasa dan Aroma Terbaik</p>
            <h1>DAFTAR MENU</h1>
        </div>

        <div class="menu-section">
            <h2>☕ Kopi Klasik (Espresso Based)</h2>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Americano</div>
                    <div class="menu-item-description">Shot espresso dengan air panas. (Ice / Hot)</div>
                </div>
                <div class="menu-item-price">Rp 25.000</div>
            </div>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Caramel Macchiato</div>
                    <div class="menu-item-description">Susu, espresso, sirup vanilla, diakhiri saus karamel.</div>
                </div>
                <div class="menu-item-price">Rp 40.000</div>
            </div>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Hazelnut Latte</div>
                    <div class="menu-item-description">Kopi susu dengan rasa kacang hazelnut yang kaya.</div>
                </div>
                <div class="menu-item-price">Rp 38.000</div>
            </div>

            <h2>🍹 Minuman Segar (Non-Kopi)</h2>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Pure Matcha Latte</div>
                    <div class="menu-item-description">Matcha premium grade A dengan susu segar tanpa pemanis buatan.</div>
                </div>
                <div class="menu-item-price">Rp 42.000</div>
            </div>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Iced Lychee Tea</div>
                    <div class="menu-item-description">Teh hitam dingin dengan ekstrak leci dan buah utuh.</div>
                </div>
                <div class="menu-item-price">Rp 30.000</div>
            </div>
        </div>

        <div class="menu-section">
            <h2>🍽️ Makanan Berat & Sandwich</h2>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Chicken Carbonara Pasta</div>
                    <div class="menu-item-description">Spaghetti creamy dengan potongan ayam dan keju parmesan.</div>
                </div>
                <div class="menu-item-price">Rp 55.000</div>
            </div>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Club Sandwich R&A</div>
                    <div class="menu-item-description">Roti panggang tumpuk, daging, telur, keju, dan sayuran segar.</div>
                </div>
                <div class="menu-item-price">Rp 48.000</div>
            </div>

            <h2>🍰 Dessert & Pastry</h2>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Molten Lava Cake</div>
                    <div class="menu-item-description">Kue cokelat hangat dengan isian lelehan cokelat di dalamnya.</div>
                </div>
                <div class="menu-item-price">Rp 45.000</div>
            </div>
            <div class="menu-item">
                <div class="item-info">
                    <div class="menu-item-name">Butter Croissant</div>
                    <div class="menu-item-description">Croissant murni mentega (butter) berkualitas tinggi.</div>
                </div>
                <div class="menu-item-price">Rp 28.000</div>
            </div>
        </div>

    </div>

</body>
</html>
