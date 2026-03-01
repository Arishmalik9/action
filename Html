<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Local Shop – Fresh Finds, Best Prices</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --cream: #fdf6ee;
    --dark: #1a1208;
    --gold: #c89b3c;
    --gold-light: #e8c46a;
    --rust: #b8441b;
    --warm-gray: #6b5d4f;
    --card-bg: #fff9f2;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--cream);
    color: var(--dark);
    overflow-x: hidden;
  }

  /* ── NAV ── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    padding: 1.1rem 2rem;
    display: flex; align-items: center; justify-content: space-between;
    background: rgba(253,246,238,0.85);
    backdrop-filter: blur(14px);
    border-bottom: 1px solid rgba(200,155,60,0.2);
  }
  .nav-logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem; font-weight: 900;
    color: var(--dark); letter-spacing: -0.02em;
  }
  .nav-logo span { color: var(--gold); }
  .nav-links a {
    margin-left: 1.8rem;
    text-decoration: none; color: var(--warm-gray);
    font-size: 0.9rem; font-weight: 500;
    transition: color .2s;
  }
  .nav-links a:hover { color: var(--gold); }

  /* ── HERO ── */
  #hero {
    position: relative; height: 100vh; min-height: 560px;
    display: flex; align-items: center; justify-content: center;
    overflow: hidden;
  }
  .hero-img {
    position: absolute; inset: 0;
    background: url('https://i.ibb.co/bR8R0BvV/IMG-0895.jpg') center/cover no-repeat;
  }
  .hero-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(160deg, rgba(26,18,8,0.65) 0%, rgba(184,68,27,0.25) 100%);
  }
  .hero-content {
    position: relative; text-align: center; color: #fff;
    padding: 0 1.5rem;
    animation: fadeUp .9s ease both;
  }
  .hero-badge {
    display: inline-block; background: var(--gold);
    color: var(--dark); font-size: 0.72rem; font-weight: 700;
    letter-spacing: .14em; text-transform: uppercase;
    padding: .35rem .9rem; border-radius: 999px; margin-bottom: 1.2rem;
  }
  .hero-content h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.8rem, 8vw, 6rem);
    font-weight: 900; line-height: 1.05; letter-spacing: -0.02em;
    text-shadow: 0 4px 30px rgba(0,0,0,0.4);
    margin-bottom: .6rem;
  }
  .hero-content p {
    font-size: clamp(1rem, 2.5vw, 1.3rem);
    font-weight: 300; opacity: .88; margin-bottom: 2.2rem;
    letter-spacing: .04em;
  }
  .btn-hero {
    display: inline-block; background: var(--gold);
    color: var(--dark); font-weight: 700; font-size: 1rem;
    padding: .95rem 2.6rem; border-radius: 999px;
    text-decoration: none; letter-spacing: .04em;
    box-shadow: 0 8px 30px rgba(200,155,60,0.45);
    transition: transform .2s, box-shadow .2s;
  }
  .btn-hero:hover { transform: translateY(-3px); box-shadow: 0 14px 40px rgba(200,155,60,0.55); }

  /* ── SECTION HEADINGS ── */
  .section-label {
    text-align: center; margin-bottom: 3.5rem;
  }
  .section-label small {
    display: block; font-size: 0.72rem; font-weight: 700;
    letter-spacing: .18em; text-transform: uppercase;
    color: var(--gold); margin-bottom: .5rem;
  }
  .section-label h2 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(1.9rem, 4vw, 3rem);
    font-weight: 900; letter-spacing: -0.02em;
  }

  /* ── PRODUCTS ── */
  #products { padding: 6rem 1.5rem; }

  .carousel-wrap { position: relative; }
  .carousel {
    display: flex; gap: 1.5rem;
    overflow-x: auto; scroll-snap-type: x mandatory;
    padding-bottom: 1rem;
    scrollbar-width: none;
  }
  .carousel::-webkit-scrollbar { display: none; }

  .product-card {
    flex: 0 0 min(78vw, 300px);
    scroll-snap-align: start;
    background: var(--card-bg);
    border-radius: 20px;
    overflow: hidden;
    border: 1px solid rgba(200,155,60,0.15);
    box-shadow: 0 4px 24px rgba(26,18,8,0.07);
    transition: transform .25s, box-shadow .25s;
    cursor: pointer;
  }
  .product-card:hover { transform: translateY(-6px); box-shadow: 0 14px 40px rgba(26,18,8,0.13); }

  .product-img {
    width: 100%; aspect-ratio: 1/1;
    object-fit: cover; display: block;
  }
  .product-info {
    padding: 1.2rem 1.2rem 1.4rem;
  }
  .product-name {
    font-family: 'Playfair Display', serif;
    font-size: 1.15rem; font-weight: 700; margin-bottom: .35rem;
  }
  .product-price {
    color: var(--rust); font-weight: 700; font-size: 1rem;
    margin-bottom: 1rem;
  }
  .btn-add {
    width: 100%; padding: .7rem;
    background: var(--dark); color: #fff;
    border: none; border-radius: 10px;
    font-family: 'DM Sans', sans-serif;
    font-size: .9rem; font-weight: 600;
    cursor: pointer; transition: background .2s;
  }
  .btn-add:hover { background: var(--rust); }
  .btn-add.added { background: var(--gold); color: var(--dark); }

  /* Carousel nav arrows */
  .carousel-nav {
    display: flex; justify-content: center; gap: 1rem; margin-top: 1.5rem;
  }
  .carr-btn {
    background: var(--dark); color: #fff;
    border: none; border-radius: 50%; width: 42px; height: 42px;
    font-size: 1.1rem; cursor: pointer; transition: background .2s;
  }
  .carr-btn:hover { background: var(--gold); color: var(--dark); }

  /* ── CART BADGE ── */
  .cart-fab {
    position: fixed; bottom: 6rem; right: 1.5rem; z-index: 90;
    background: var(--dark); color: #fff;
    border: none; border-radius: 999px;
    padding: .75rem 1.3rem; font-family: 'DM Sans', sans-serif;
    font-size: .9rem; font-weight: 700;
    cursor: pointer; box-shadow: 0 6px 24px rgba(26,18,8,0.3);
    display: flex; align-items: center; gap: .5rem;
    transition: transform .2s, background .2s;
  }
  .cart-fab:hover { background: var(--rust); transform: scale(1.04); }
  .cart-count {
    background: var(--gold); color: var(--dark);
    border-radius: 50%; width: 22px; height: 22px;
    display: flex; align-items: center; justify-content: center;
    font-size: .75rem;
  }

  /* ── ORDER MODAL ── */
  .modal-backdrop {
    display: none; position: fixed; inset: 0; z-index: 200;
    background: rgba(26,18,8,0.6); backdrop-filter: blur(6px);
    align-items: center; justify-content: center; padding: 1rem;
  }
  .modal-backdrop.open { display: flex; }
  .modal {
    background: var(--cream); border-radius: 24px;
    padding: 2rem; width: 100%; max-width: 480px;
    max-height: 90vh; overflow-y: auto;
    box-shadow: 0 24px 80px rgba(26,18,8,0.3);
    animation: fadeUp .3s ease both;
  }
  .modal h3 {
    font-family: 'Playfair Display', serif;
    font-size: 1.6rem; font-weight: 900; margin-bottom: 1.4rem;
  }
  .modal label {
    display: block; font-size: .82rem; font-weight: 600;
    color: var(--warm-gray); margin-bottom: .3rem; letter-spacing: .04em;
  }
  .modal input {
    width: 100%; padding: .75rem 1rem;
    border: 1.5px solid rgba(200,155,60,0.3);
    border-radius: 10px; font-family: 'DM Sans', sans-serif;
    font-size: .95rem; background: #fff;
    margin-bottom: 1.1rem; outline: none;
    transition: border-color .2s;
  }
  .modal input:focus { border-color: var(--gold); }

  .cart-items-list { margin-bottom: 1.2rem; }
  .cart-item-row {
    display: flex; justify-content: space-between; align-items: center;
    padding: .55rem 0; border-bottom: 1px solid rgba(200,155,60,0.15);
    font-size: .9rem;
  }
  .cart-item-row:last-child { border-bottom: none; }
  .remove-item { background: none; border: none; color: var(--rust); cursor: pointer; font-size: 1rem; }

  .empty-cart { text-align: center; color: var(--warm-gray); padding: 1.5rem 0; font-size: .9rem; }

  .btn-order {
    width: 100%; padding: .95rem;
    background: var(--rust); color: #fff;
    border: none; border-radius: 12px;
    font-family: 'DM Sans', sans-serif; font-size: 1rem; font-weight: 700;
    cursor: pointer; transition: background .2s, transform .15s;
    margin-top: .5rem;
  }
  .btn-order:hover:not(:disabled) { background: #9a3615; transform: translateY(-2px); }
  .btn-order:disabled { opacity: .6; cursor: not-allowed; }

  .modal-close {
    float: right; background: none; border: none;
    font-size: 1.4rem; cursor: pointer; color: var(--warm-gray);
    line-height: 1;
  }

  .msg { font-size: .85rem; margin-top: .8rem; text-align: center; font-weight: 500; }
  .msg.success { color: #2d7a4f; }
  .msg.error { color: var(--rust); }

  /* ── WHATSAPP ── */
  .wa-btn {
    position: fixed; bottom: 1.5rem; right: 1.5rem; z-index: 90;
    width: 56px; height: 56px; border-radius: 50%;
    background: #25d366;
    display: flex; align-items: center; justify-content: center;
    box-shadow: 0 6px 24px rgba(37,211,102,0.4);
    transition: transform .2s;
  }
  .wa-btn:hover { transform: scale(1.1); }
  .wa-btn svg { width: 28px; height: 28px; fill: #fff; }

  /* ── FOOTER ── */
  footer {
    text-align: center; padding: 2.5rem 1.5rem;
    background: var(--dark); color: rgba(255,255,255,0.45);
    font-size: .82rem;
  }
  footer strong { color: var(--gold); }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(28px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  @media(max-width:600px) {
    .nav-links { display: none; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">The <span>Local</span> Shop</div>
  <div class="nav-links">
    <a href="#hero">Home</a>
    <a href="#products">Products</a>
    <a href="#order">Order</a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-img"></div>
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <div class="hero-badge">✦ Neighbourhood Favourite ✦</div>
    <h1>The Local<br>Shop</h1>
    <p>Fresh Finds, Best Prices</p>
    <a href="#products" class="btn-hero">Shop Now ↓</a>
  </div>
</section>

<!-- PRODUCTS -->
<section id="products">
  <div class="section-label">
    <small>✦ Our Selection ✦</small>
    <h2>Fresh Picks Today</h2>
  </div>

  <div class="carousel-wrap">
    <div class="carousel" id="carousel">

      <div class="product-card">
        <img class="product-img" src="https://i.ibb.co/yFr0P33p/image.jpg" alt="Product 1" loading="lazy">
        <div class="product-info">
          <div class="product-name">Fresh Essentials Pack</div>
          <div class="product-price">Best Price</div>
          <button class="btn-add" onclick="addToCart(this, 'Fresh Essentials Pack')">Add to Cart</button>
        </div>
      </div>

      <div class="product-card">
        <img class="product-img" src="https://i.ibb.co/chKzpf73/image.jpg" alt="Product 2" loading="lazy">
        <div class="product-info">
          <div class="product-name">Daily Grocery Bundle</div>
          <div class="product-price">Best Price</div>
          <button class="btn-add" onclick="addToCart(this, 'Daily Grocery Bundle')">Add to Cart</button>
        </div>
      </div>

      <div class="product-card">
        <img class="product-img" src="https://i.ibb.co/PG9tSjFw/image.jpg" alt="Product 3" loading="lazy">
        <div class="product-info">
          <div class="product-name">Local Specials Box</div>
          <div class="product-price">Best Price</div>
          <button class="btn-add" onclick="addToCart(this, 'Local Specials Box')">Add to Cart</button>
        </div>
      </div>

      <!-- Duplicate cards for fuller carousel look -->
      <div class="product-card">
        <img class="product-img" src="https://i.ibb.co/yFr0P33p/image.jpg" alt="Product 4" loading="lazy">
        <div class="product-info">
          <div class="product-name">Seasonal Favourites</div>
          <div class="product-price">Best Price</div>
          <button class="btn-add" onclick="addToCart(this, 'Seasonal Favourites')">Add to Cart</button>
        </div>
      </div>

    </div>

    <div class="carousel-nav">
      <button class="carr-btn" onclick="scrollCarousel(-1)">←</button>
      <button class="carr-btn" onclick="scrollCarousel(1)">→</button>
    </div>
  </div>
</section>

<!-- CART FAB -->
<button class="cart-fab" onclick="openModal()" id="cartFab">
  🛒 View Cart
  <span class="cart-count" id="cartCount">0</span>
</button>

<!-- ORDER MODAL -->
<div class="modal-backdrop" id="modalBackdrop" onclick="handleBackdropClick(event)">
  <div class="modal" id="orderModal">
    <button class="modal-close" onclick="closeModal()">✕</button>
    <h3 id="order">Place Your Order</h3>

    <div class="cart-items-list" id="cartItemsList">
      <div class="empty-cart" id="emptyMsg">Your cart is empty. Add some products first!</div>
    </div>

    <div id="formSection">
      <label>Your Name *</label>
      <input type="text" id="custName" placeholder="e.g. Ahmed Khan">

      <label>Phone Number *</label>
      <input type="tel" id="custPhone" placeholder="e.g. 03001234567">

      <label>Delivery Address</label>
      <input type="text" id="custAddress" placeholder="Optional – your address">

      <button class="btn-order" id="sendBtn" onclick="sendOrder()">Send Order via Email</button>
      <div class="msg" id="statusMsg"></div>
    </div>
  </div>
</div>

<!-- WHATSAPP -->
<a class="wa-btn" href="https://wa.me/9999999999" target="_blank" rel="noopener" title="Chat on WhatsApp">
  <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
  </svg>
</a>

<!-- FOOTER -->
<footer>
  <p>&copy; 2024 <strong>The Local Shop</strong> · Fresh Finds, Best Prices · All Rights Reserved</p>
</footer>

<script>
  // ── EmailJS Init ──
  // IMPORTANT: Replace 'YOUR_PUBLIC_KEY' with your EmailJS public key
  // and configure a template at https://emailjs.com
  emailjs.init('YOUR_PUBLIC_KEY');

  // ── Cart State ──
  let cart = [];

  function addToCart(btn, name) {
    const existing = cart.find(i => i.name === name);
    if (existing) {
      existing.qty++;
    } else {
      cart.push({ name, qty: 1 });
    }
    updateCartCount();
    btn.textContent = '✓ Added';
    btn.classList.add('added');
    setTimeout(() => {
      btn.textContent = 'Add to Cart';
      btn.classList.remove('added');
    }, 1600);
  }

  function updateCartCount() {
    const total = cart.reduce((s, i) => s + i.qty, 0);
    document.getElementById('cartCount').textContent = total;
  }

  function renderCartItems() {
    const list = document.getElementById('cartItemsList');
    const emptyMsg = document.getElementById('emptyMsg');
    list.innerHTML = '';
    if (cart.length === 0) {
      list.innerHTML = '<div class="empty-cart">Your cart is empty. Add some products first!</div>';
      return;
    }
    cart.forEach((item, idx) => {
      const row = document.createElement('div');
      row.className = 'cart-item-row';
      row.innerHTML = `
        <span>${item.name}</span>
        <span style="display:flex;align-items:center;gap:.7rem">
          <span style="font-weight:600">x${item.qty}</span>
          <button class="remove-item" onclick="removeItem(${idx})">✕</button>
        </span>`;
      list.appendChild(row);
    });
  }

  function removeItem(idx) {
    cart.splice(idx, 1);
    updateCartCount();
    renderCartItems();
  }

  function openModal() {
    renderCartItems();
    document.getElementById('modalBackdrop').classList.add('open');
    document.getElementById('statusMsg').textContent = '';
  }

  function closeModal() {
    document.getElementById('modalBackdrop').classList.remove('open');
  }

  function handleBackdropClick(e) {
    if (e.target === document.getElementById('modalBackdrop')) closeModal();
  }

  async function sendOrder() {
    const name = document.getElementById('custName').value.trim();
    const phone = document.getElementById('custPhone').value.trim();
    const address = document.getElementById('custAddress').value.trim();
    const statusMsg = document.getElementById('statusMsg');
    const sendBtn = document.getElementById('sendBtn');

    if (!name || !phone) {
      statusMsg.className = 'msg error';
      statusMsg.textContent = '⚠ Please fill in your name and phone number.';
      return;
    }
    if (cart.length === 0) {
      statusMsg.className = 'msg error';
      statusMsg.textContent = '⚠ Your cart is empty!';
      return;
    }

    const itemList = cart.map(i => `• ${i.name} (x${i.qty})`).join('\n');
    sendBtn.disabled = true;
    sendBtn.textContent = 'Sending…';

    try {
      // Replace 'YOUR_SERVICE_ID' and 'YOUR_TEMPLATE_ID' with your EmailJS values
      await emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', {
        to_email: 's.m.arshmalik952888@gmail.com',
        customer_name: name,
        customer_phone: phone,
        customer_address: address || 'Not provided',
        order_items: itemList,
        order_date: new Date().toLocaleString(),
      });
      statusMsg.className = 'msg success';
      statusMsg.textContent = '✓ Order sent successfully! We\'ll contact you soon.';
      cart = [];
      updateCartCount();
      renderCartItems();
      document.getElementById('custName').value = '';
      document.getElementById('custPhone').value = '';
      document.getElementById('custAddress').value = '';
    } catch (err) {
      statusMsg.className = 'msg error';
      statusMsg.textContent = '✕ Failed to send. Please try WhatsApp or call us directly.';
      console.error(err);
    }
    sendBtn.disabled = false;
    sendBtn.textContent = 'Send Order via Email';
  }

  // ── Carousel ──
  function scrollCarousel(dir) {
    const c = document.getElementById('carousel');
    c.scrollBy({ left: dir * 320, behavior: 'smooth' });
  }

  // Auto-slide
  setInterval(() => scrollCarousel(1), 4000);
</script>
</body>
</html>
