<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>TrendAffi — Quick Deals</title>
  <meta name="description" content="TrendAffi — quick minimal product list. Click Buy to open affiliate link." />
  <style>
    :root{
      --green:#2E6B36;
      --white:#ffffff;
      --muted:#6b6b6b;
      --card-radius:12px;
      --max-width:1100px;
      --gap:14px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, Arial;
      background:#ffffff;
      color:#111;
      -webkit-font-smoothing:antialiased;
    }
    .wrap{max-width:var(--max-width);margin:0 auto;padding:18px}
    header{display:flex;align-items:center;gap:12px;padding:10px 0;border-bottom:1px solid #eee}
    .logo img{width:64px;height:64px;object-fit:contain;border-radius:10px}
    .brand{font-weight:800;color:var(--green);font-size:18px}
    .hero{padding:18px 0}
    h1{margin:0;font-size:20px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:14px}

    /* grid - minimal cards */
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:var(--gap);margin-top:18px}
    .card{
      border-radius:var(--card-radius);
      overflow:hidden;
      background:#fff;
      border:1px solid #f0f0f0;
      display:flex;
      flex-direction:column;
      align-items:stretch;
      justify-content:flex-start;
      min-height:260px;
      box-shadow:0 6px 18px rgba(15,18,15,0.04);
    }
    .card .imgwrap{height:180px;background:#fafafa;display:flex;align-items:center;justify-content:center}
    .card .imgwrap img{max-width:100%;max-height:100%;object-fit:contain}
    .card .meta{padding:12px;display:flex;flex-direction:column;gap:8px;flex:1}
    .card .title{font-weight:700;color:#0d1f14;font-size:14px;min-height:40px;line-height:1.2}
    .card .btns{display:flex;gap:8px;margin-top:auto}
    .buy{
      flex:1;
      background:var(--green);
      color:var(--white);
      text-decoration:none;
      padding:10px;
      border-radius:8px;
      text-align:center;
      font-weight:700;
      font-size:14px;
    }
    .share{
      background:transparent;
      color:var(--green);
      border:1px solid rgba(46,107,54,0.12);
      padding:10px;
      border-radius:8px;
      text-align:center;
      text-decoration:none;
      font-weight:700;
    }
    footer{margin:30px 0 60px;color:var(--muted);font-size:13px;text-align:center}

    @media (max-width:640px){
      .logo img{width:56px;height:56px}
      .card .imgwrap{height:160px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">
        <!-- local file path you uploaded; keep this path as-is when pasting -->
        <img src="/mnt/data/98b08d93-ac44-4a6e-8335-0f45c2f6dd17.png" alt="TrendAffi Logo">
      </div>
      <div>
        <div class="brand">TrendAffi</div>
        <div style="font-size:13px;color:#666">Daily Deals • Smart Savings</div>
      </div>
    </header>

    <div class="hero">
      <h1>Quick Shop — Minimal View</h1>
      <p class="lead">Tap product image → press Buy. All buttons open Amazon affiliate links.</p>
    </div>

    <section class="grid">

      <!-- Card 1 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+1" alt="Product 1"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 1</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/48iJcO5" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/48iJcO5" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 2 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+2" alt="Product 2"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 2</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4owmYhj" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4owmYhj" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 3 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+3" alt="Product 3"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 3</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4qUZUdN" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4qUZUdN" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 4 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+4" alt="Product 4"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 4</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4r1Ngd6" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4r1Ngd6" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 5 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+5" alt="Product 5"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 5</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3Ju6ebq" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3Ju6ebq" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 6 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+6" alt="Product 6"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 6</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3WVRvce" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3WVRvce" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 7 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+7" alt="Product 7"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 7</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4p5coxz" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4p5coxz" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 8 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+8" alt="Product 8"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 8</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4oyASzn" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4oyASzn" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 9 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+9" alt="Product 9"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 9</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3LA8lLk" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3LA8lLk" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 10 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+10" alt="Product 10"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 10</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/43WYCoC" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/43WYCoC" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 11 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+11" alt="Product 11"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 11</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4ovmU1g" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4ovmU1g" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 12 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+12" alt="Product 12"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 12</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3JYMcWw" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3JYMcWw" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 13 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+13" alt="Product 13"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 13</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/47V96Gm" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/47V96Gm" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 14 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+14" alt="Product 14"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 14</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3Ju6C9S" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3Ju6C9S" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 15 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+15" alt="Product 15"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 15</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4nNxdfX" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4nNxdfX" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 16 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+16" alt="Product 16"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 16</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4oB5K2a" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4oB5K2a" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 17 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+17" alt="Product 17"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 17</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4qRm5Br" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4qRm5Br" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 18 (duplicate link kept) -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+18" alt="Product 18"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 18</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4qRm5Br" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4qRm5Br" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 19 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+19" alt="Product 19"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 19</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/49bOyvw" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/49bOyvw" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 20 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+20" alt="Product 20"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 20</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3WTZUNs" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3WTZUNs" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 21 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+21" alt="Product 21"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 21</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/3JIKBUP" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/3JIKBUP" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 22 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+22" alt="Product 22"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 22</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4i14DGL" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4i14DGL" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 23 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+23" alt="Product 23"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 23</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/47TXbZs" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/47TXbZs" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

      <!-- Card 24 -->
      <article class="card">
        <div class="imgwrap"><img src="https://via.placeholder.com/600x400?text=Product+24" alt="Product 24"></div>
        <div class="meta">
          <div class="title">Top Deal — Product 24</div>
          <div style="display:flex;gap:8px" class="btns">
            <a class="buy" href="https://amzn.to/4nWVjoP" target="_blank" rel="noopener">Buy Now</a>
            <a class="share" href="https://amzn.to/4nWVjoP" target="_blank" rel="noopener">Share</a>
          </div>
        </div>
      </article>

    </section>

    <footer>
      <p>Affiliate disclosure: TrendAffi may earn a commission if you buy through links on this page.</p>
      <p class="small">Tip: Replace placeholder images with actual Amazon product images (right-click → Copy image address) for better conversions.</p>
    </footer>
  </div>
</body>
</html>
