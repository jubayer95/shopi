### Env Variables

##Add your config variables values in the config.env file in backend/config folder.

PORT=4000
DB_URI="mongodb://localhost:27017/E"

FRONTEND_URL="http://localhost:3000"

STRIPE_API_KEY=pk_test_51LVQqcSBZ40cP6Go1rUgo9CXHgSUCeZ5SypbISKWC0e4jFcB81qUgsjcWIqIBQVIarja5LMnGQ4XlzYT8qUNzFDE00ZWOabClf
STRIPE_SECRET_KEY=sk_test_51LVQqcSBZ40cP6Go96OouNV2TzuMI1ModrIB5u3bp8hSvqKjpuYFynNPcLDfYHmjYLxr8OwbW5bFsfPB7R5StxJ0004rkTzYK4

JWT_SECRET=HAIJSJDISAJMDJAODOAJDAJSDM

JWT_EXPIRE= 5d

COOKIE_EXPIRES_TIME = 5d


SMTP_PORT = 465
SMTP_HOST = gmail

SMPT_EMAIL=tanjilbhuyan@gmail.com

SMPT_PASSWORD=hmywbilnkpcvaqjc

CLOUDINARY_CLOUD_NAME= dl3229msu
CLOUDINARY_API_KEY= 969764887452726
CLOUDINARY_API_SECRET= JhNTcdPuNr6_nYZ3xVYEQ8WnKoM

### Install Dependencies (Frontend)

```
cd frontend
npm i
```

### Install Dependencies (Backend)

```
npm i
```

### Seed Database

Use the following commeand to put some dummy products in that database.
Run it in the root folder.

```
npm run seeder
```
