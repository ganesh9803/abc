I.Create the Database and Table:

1. -- Create a new SQLite database and table for products
sqlite3 products.db

-- Inside the SQLite prompt, create the table
CREATE TABLE products (
    id INTEGER PRIMARY KEY,
    title TEXT NOT NULL,
    brand TEXT NOT NULL,
    price INTEGER NOT NULL,
    image_url TEXT NOT NULL,
    rating TEXT NOT NULL
);

2. Insert Data into the Table:

INSERT INTO products (id, title, brand, price, image_url, rating) VALUES
(1, 'Wide Bowknot Hat', 'MAJIK', 288, 'https://assets.ccbp.in/frontend/react-js/ecommerce/clothes-cap.png', '3.6'),
(2, 'Plain Round Neck T-shirt', 'Huetrap', 395, 'https://assets.ccbp.in/frontend/react-js/ecommerce/clothes-fit-t-shirt.png', '4.1'),
(3, 'Cotton Hoodie', 'Scott International', 498, 'https://assets.ccbp.in/frontend/react-js/ecommerce/clothes-hoodie.png', '3.8'),
(4, 'Men\'s Waistcoat', 'LEVIS', 2500, 'https://assets.ccbp.in/frontend/react-js/ecommerce/clothes-jacket.png', '4.3');

II.prime_deals Data:
1. Create the prime_deals Table:

CREATE TABLE prime_deals (
    id INTEGER PRIMARY KEY,
    image_url TEXT NOT NULL,
    title TEXT NOT NULL,
    price INTEGER NOT NULL,
    brand TEXT NOT NULL,
    rating REAL NOT NULL
);

2. Insert Data into the prime_deals Table:

INSERT INTO prime_deals (id, image_url, title, price, brand, rating) VALUES
(1001, 'https://assets.ccbp.in/frontend/react-js/ecommerce/appliances-silver-hair-dryer.png', 'Hair Dryer', 760, 'Phillips', 3.9),
(1002, 'https://assets.ccbp.in/frontend/react-js/ecommerce/toys-people-toys.png', 'Minifigures', 760, 'LEGO', 3.9),
(1003, 'https://assets.ccbp.in/frontend/react-js/ecommerce/electronics-short-tri-pod.png', 'Lightweight Tripod', 760, 'LEGO', 3.9);



