# Test-repo

This is a repository to implement dependent dropdown menu.

## Installing required libraries

Use the below code snippet in your terminal to install all the required libraries
`pip install -r requirements.txt`

## Adding data to your tables in Postgres using SQL

use the following commands to populate the tables

```
INSERT INTO countries (id, name) VALUES (1, 'INDIA'), (2, 'UNITED STATES OF AMERICA');



INSERT INTO state (id, name, country_id) VALUES (1, 'MAHARASHTRA', 1), (2, 'KARNATAKA', 1), (3, 'GOA', 1), (4, 'KERALA', 1), (5, 'TAMIL NADU', 1), (6, 'ALABAMA', 2), (7, 'ALASKA', 2), (8, 'ARIZONA', 2), (9, 'CALIFORNIA', 2), (10, 'COLORADO', 2);

INSERT INTO city (id, name, stateid) VALUES (1, 'PUNE', 1), (2, 'NAGPUR', 1), (3, 'MUMBAI', 1);
INSERT INTO city (id, name, stateid) VALUES (4, 'BENGALURU', 2), (5, 'MYSORE', 2), (6, 'MANGALORE', 2);
INSERT INTO city (id, name, stateid) VALUES (7, 'PANAJI', 3), (8, 'PONDA', 3), (9, 'MARGAO', 3);
INSERT INTO city (id, name, stateid) VALUES (10, 'KOCHI', 4), (11, 'KOZHIKODE', 4), (12, 'THRISSUR', 4);
INSERT INTO city (id, name, stateid) VALUES (13, 'CHENNAI', 5), (14, 'VELLORE', 5), (15, 'MADURAI', 5);


INSERT INTO city (id, name, stateid) VALUES (16, 'BIRMINGHAM', 6), (17, 'HUNTSVILLE', 6), (18, 'MONTGOMERY', 6);
INSERT INTO city (id, name, stateid) VALUES (19, 'ANCHORAGE', 7), (20, 'JUNEAU', 7), (21, 'KETCHIKAN', 7);
INSERT INTO city (id, name, stateid) VALUES (22, 'PHEONIX', 8), (23, 'TUCSON', 8), (24, 'SCOTTSDALE', 8);
INSERT INTO city (id, name, stateid) VALUES (25, 'SAN FRANCISCO', 9), (26, 'LOS ANGELES', 9), (27, 'SAN DIEGO', 9);
INSERT INTO city (id, name, stateid) VALUES (28, 'DENVER', 10), (29, 'COLORADO SPRINGS', 10), (30, 'ASPEN', 10);

```
