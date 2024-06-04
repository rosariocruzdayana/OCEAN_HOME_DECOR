# OCEAN_HOME_DECOR

CREATE TABLE ocean_home_decor (id INTEGER PRIMARY KEY, decor TEXT, quantity INTEGER, price INTEGER, discount INTEGER);

INSERT INTO ocean_home_decor VALUES (1, "lamps" 20, 40, 15);
INSERT INTO ocean_home_decor VALUES (2, "tables" 8, 80, 20);
INSERT INTO ocean_home_decor VALUES (3, "chandeliers" 5, 100, 15);
INSERT INTO ocean_home_decor VALUES (4, "silverware" 30, 25, 10);
INSERT INTO ocean_home_decor VALUES (5, "pillows" 40, 15, 20);
INSERT INTO ocean_home_decor VALUES (6, "blankets, 60, 25, 20);
INSERT INTO ocean_home_decor VALUES (7, "picture_frames" 35, 45, 15);
INSERT INTO ocean_home_decor VALUES (8, "wall_art" 25, 40, 20);
INSERT INTO ocean_home_decor VALUES (9, "carpets" 50, 120, 30);
INSERT INTO ocean_home_decor VALUES (10, "couches" 5, 300, 10);
INSERT INTO ocean_home_decor VALUES (11, "chairs" 18, 45, 25);
INSERT INTO ocean_home_decor VALUES (12, "candles" 60, 42, 50);
INSERT INTO ocean_home_decor VALUES (13, "ornaments" 200, 10, 40); 
INSERT INTO ocean_home_decor VALUES (14, "coasters" 150, 12, 15);
INSERT INTO ocean_home_decor VALUES (15, "plates" 120, 32, 75);

SELECT * FROM ocean_home_decor WHERE > 40 ORDER BY price; 

/* What is the average discount at ocean_home_decor? */
SELECT AVG(discount) FROM ocean_home_decor;

/* What is the highest discounted price at ocean_home_decor? */
SELECT MAX(discount) as most_discounted_decor FROM ocean_home_decor;


