# ExamBuddy Ghana
Responsive WASSCE/BECE checker guidance and study practice website.

## Deploy on Render
- Runtime: Node
- Build command: npm install
- Start command: npm start
- Health check path: /health

## Checker catalogue API
Set DATAMART_API_KEY (and DATAMART_API_SECRET if required) in Render environment variables. Credentials remain server-side. The app calls DataMart's GET /api/checkers/products through /api/store/checkers/products.

## Payments
Purchases are intentionally disabled until a payment provider and a trusted server-verified payment webhook are configured. Never trust a browser-only payment success flag or commit supplier credentials to source control. This independent prototype is not affiliated with WAEC.