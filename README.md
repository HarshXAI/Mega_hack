# Mega_hack

E-commerce marketplace built at a hackathon: browse products, add to cart, buy now with Razorpay, and list items with image upload.

## Stack

- Frontend: React
- Backend: Express, MongoDB (Mongoose), Razorpay, Cloudinary, Multer

## API (Backend/app.js)

`POST /register-user`, `POST /login`, `GET /products`, `POST /upload-book`, `POST /cart/add`, `POST /cart/buy-now`, `POST /create-order`

## Run

```bash
cd Backend && npm install && npm start   # port 4002
cd frontend && npm install && npm start
```

You need your own MongoDB, Razorpay and Cloudinary credentials. Keep them in environment variables, never in the repo.
