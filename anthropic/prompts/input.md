
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Golden Dragon Restaurant – Customer Reviews</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fdf6ec;
      color: #333;
      padding: 40px 20px;
    }

    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 2.4rem;
      color: #b5251e;
      letter-spacing: 1px;
    }

    header p {
      color: #888;
      font-size: 1rem;
      margin-top: 6px;
    }

    .reviews-container {
      max-width: 780px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 24px;
    }

    .review-card {
      background: #fff;
      border-radius: 12px;
      padding: 24px 28px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.08);
      border-left: 5px solid #b5251e;
    }

    .review-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 10px;
      flex-wrap: wrap;
      gap: 8px;
    }

    .reviewer-info {
      display: flex;
      flex-direction: column;
      gap: 3px;
    }

    .reviewer-name {
      font-weight: 700;
      font-size: 1.05rem;
      color: #b5251e;
    }

    .reviewer-city {
      font-size: 0.85rem;
      color: #888;
      display: flex;
      align-items: center;
      gap: 4px;
    }

    .review-date {
      font-size: 0.85rem;
      color: #aaa;
      white-space: nowrap;
    }

    .stars {
      font-size: 1.3rem;
      color: #f5a623;
      margin-bottom: 10px;
    }

    .stars .empty {
      color: #ddd;
    }

    .review-text {
      font-size: 0.97rem;
      line-height: 1.7;
      color: #555;
    }
  </style>
</head>
<body>

  <header>
    <h1>🐉 Golden Dragon Restaurant</h1>
    <p>Authentic Chinese Cuisine – Customer Reviews</p>
  </header>

  <div class="reviews-container">

    <!-- Review 1 -->
    <div class="review-card">
      <div class="review-header">
        <div class="reviewer-info">
          <span class="reviewer-name">FoodieFan_Sarah</span>
          <span class="reviewer-city">📍 San Francisco, CA</span>
        </div>
        <span class="review-date">February 18, 2026</span>
      </div>
      <div class="stars">
        <span>★★★★★</span>
      </div>
      <p class="review-text">
        Absolutely phenomenal experience from start to finish! The Peking duck was perfectly crispy, and the scallion pancakes were light and flavorful. Our server was attentive without being intrusive, and the ambiance felt warm and welcoming. I've been to many Chinese restaurants across the city, but Golden Dragon stands in a league of its own. We'll definitely be back for a family dinner soon!
      </p>
    </div>

    <!-- Review 2 -->
    <div class="review-card">
      <div class="review-header">
        <div class="reviewer-info">
          <span class="reviewer-name">DimSumDave</span>
          <span class="reviewer-city">📍 Los Angeles, CA</span>
        </div>
        <span class="review-date">January 30, 2026</span>
      </div>
      <div class="stars">
        <span>★★★★</span><span class="empty">★</span>
      </div>
      <p class="review-text">
        Great dim sum selection on the weekend brunch menu — the har gow and siu mai were fresh and well-seasoned. The only reason I'm not giving five stars is that the wait time was a bit long, even with a reservation. That said, the food more than made up for it. The XO sauce fried rice was a standout dish I'd order again in a heartbeat.
      </p>
    </div>

    <!-- Review 3 -->
    <div class="review-card">
      <div class="review-header">
        <div class="reviewer-info">
          <span class="reviewer-name">NoodleNomad</span>
          <span class="reviewer-city">📍 Seattle, WA</span>
        </div>
        <span class="review-date">January 12, 2026</span>
      </div>
      <div class="stars">
        <span>★★★</span><span class="empty">★★</span>
      </div>
      <p class="review-text">
        Decent food overall, but I felt the portions were a little small for the price. The mapo tofu had a nice kick to it and the wonton soup was comforting on a cold evening. However, the kung pao chicken was a bit too sweet for my taste — I prefer it spicier and more savory. The decor is lovely and the staff were friendly. Might give it another shot and try different dishes.
      </p>
    </div>

    <!-- Review 4 -->
    <div class="review-card">
      <div class="review-header">
        <div class="reviewer-info">
          <span class="reviewer-name">CityEats_Marcus</span>
          <span class="reviewer-city">📍 New York, NY</span>
        </div>
        <span class="review-date">December 28, 2025</span>
      </div>
      <div class="stars">
        <span>★★★★★</span>
      </div>
      <p class="review-text">
        We came here for a New Year's Eve dinner and it was an unforgettable experience. The whole steamed fish was beautifully presented and tasted incredibly fresh. The hot and sour soup was bold and perfectly balanced. The staff went out of their way to make our celebration special — they even brought out a complimentary dessert platter. Highly recommend for special occasions or just a great night out!
      </p>
    </div>

    <!-- Review 5 -->
    <div class="review-card">
      <div class="review-header">
        <div class="reviewer-info">
          <span class="reviewer-name">VeggieVibes_Priya</span>
          <span class="reviewer-city">📍 Austin, TX</span>
        </div>
        <span class="review-date">December 5, 2025</span>
      </div>
      <div class="stars">
        <span>★★★★</span><span class="empty">★</span>
      </div>
      <p class="review-text">
        As a vegetarian, I was pleasantly surprised by how many plant-based options were available. The Buddha's Delight was hearty and full of flavor, and the vegetable spring rolls were crispy without being greasy. I appreciated that the staff were knowledgeable about which dishes could be made without meat broth. The only minor issue was that the restaurant was quite noisy during peak hours, making conversation a little difficult. Overall, a solid choice for vegetarians!
      </p>
    </div>

  </div>

</body>
</html>

