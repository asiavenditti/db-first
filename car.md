# Car dealer db

## Table name: second_hand_cars

- id_car BIGINT PRIMARY KEY AUTO_INCREMENT INDEX
- brand | VARCHAR(30) NOT NULL
- model | VARCHAR(80) NOT NULL INDEX
- registration_year | YEAR NOT NULL INDEX
- mileage | INT NOT NULL INDEX
- price | INT NOT NULL 
- color | VARCHAR(15) NOT NULL
- transmission_type | VARCHAR(10) NOT NULL DEFAULT 'manuale'
- fuel_type VARCHAR(10) NOT NULL DEFAULT 'benzina'
- is_available | TINYINT NOT NULL
- euro_category | CHAR(6) NOT NULL
- power | VARCHAR(50) NOT NULL
- description | TEXT NULL
- origin_car | VARCHAR(30) NULL DEFAULT 'italia'
- owner_email | VARCHAR(100) NOT NULL
- owner_phone | VARCHAR(20) NOT NULL
- img_car | VARCHAR(255) NULL DEFAULT 'https://static.vecteezy.com/ti/vettori-gratis/p1/8618726-classica-macchina-rossa-in-stile-cartone-animato-gratuito-vettoriale.jpg'
