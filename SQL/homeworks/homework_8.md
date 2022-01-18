```SQL
1. CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```

```SQL
-- example 50 rows for employee table from mockaroo.com
INSERT INTO employee (id, first_name, email, birthday) VALUES (1, 'Benoite', 'bbiddlecombe0@desdev.cn', '9/22/1997');
INSERT INTO employee (id, first_name, email, birthday) VALUES (2, 'Kaylyn', 'kblondin1@cnn.com', '5/4/1978');
INSERT INTO employee (id, first_name, email, birthday) VALUES (3, 'Urbanus', 'ubangham2@yahoo.co.jp', '5/9/1952');
INSERT INTO employee (id, first_name, email, birthday) VALUES (4, 'Cos', 'cprall3@list-manage.com', '1/20/1950');
INSERT INTO employee (id, first_name, email, birthday) VALUES (5, 'Selby', 'sclaypoole4@webs.com', '6/2/1966');
INSERT INTO employee (id, first_name, email, birthday) VALUES (6, 'Tierney', 'tquinell5@economist.com', '11/24/1989');
INSERT INTO employee (id, first_name, email, birthday) VALUES (7, 'Brandyn', 'bjoll6@theglobeandmail.com', '12/22/1963');
INSERT INTO employee (id, first_name, email, birthday) VALUES (8, 'Millard', 'mbrewin7@1688.com', '12/15/1991');
INSERT INTO employee (id, first_name, email, birthday) VALUES (9, 'Kaile', 'ksondon8@accuweather.com', '1/24/1982');
INSERT INTO employee (id, first_name, email, birthday) VALUES (10, 'Kristina', 'kgimblett9@omniture.com', '12/19/1969');
INSERT INTO employee (id, first_name, email, birthday) VALUES (11, 'Eldredge', 'escartha@jalbum.net', '12/20/1968');
INSERT INTO employee (id, first_name, email, birthday) VALUES (12, 'Gustaf', 'gfendb@scientificamerican.com', '5/6/1966');
INSERT INTO employee (id, first_name, email, birthday) VALUES (13, 'Ingmar', 'imostync@tiny.cc', '9/1/1947');
INSERT INTO employee (id, first_name, email, birthday) VALUES (14, 'Ambrose', 'aconellyd@hc360.com', '10/31/1986');
INSERT INTO employee (id, first_name, email, birthday) VALUES (15, 'Christiano', 'cmagoge@prnewswire.com', '12/9/1951');
INSERT INTO employee (id, first_name, email, birthday) VALUES (16, 'Ardine', 'asifflettf@msu.edu', '3/21/1952');
INSERT INTO employee (id, first_name, email, birthday) VALUES (17, 'Angele', 'aspooleg@house.gov', '10/3/1948');
INSERT INTO employee (id, first_name, email, birthday) VALUES (18, 'Agace', 'ablythh@google.es', '4/15/1993');
INSERT INTO employee (id, first_name, email, birthday) VALUES (19, 'Taddeusz', 'tharryi@livejournal.com', '7/19/1978');
INSERT INTO employee (id, first_name, email, birthday) VALUES (20, 'Mable', 'mennalsj@constantcontact.com', '5/30/1972');
INSERT INTO employee (id, first_name, email, birthday) VALUES (21, 'Giffy', 'ghewertsonk@icq.com', '1/8/1965');
INSERT INTO employee (id, first_name, email, birthday) VALUES (22, 'Zelda', 'zahlinl@phoca.cz', '7/29/1948');
INSERT INTO employee (id, first_name, email, birthday) VALUES (23, 'Corrinne', 'cdockertym@wix.com', '6/2/1994');
INSERT INTO employee (id, first_name, email, birthday) VALUES (24, 'Gisela', 'gairdrien@cornell.edu', '9/22/1982');
INSERT INTO employee (id, first_name, email, birthday) VALUES (25, 'Gwenette', 'gbaisso@biglobe.ne.jp', '3/22/1964');
INSERT INTO employee (id, first_name, email, birthday) VALUES (26, 'Alejandrina', 'aswendellp@china.com.cn', '10/24/1991');
INSERT INTO employee (id, first_name, email, birthday) VALUES (27, 'Sullivan', 'sfearensideq@arizona.edu', '4/1/1993');
INSERT INTO employee (id, first_name, email, birthday) VALUES (28, 'Marcelle', 'mwysonr@census.gov', '6/15/1970');
INSERT INTO employee (id, first_name, email, birthday) VALUES (29, 'Dottie', 'djanuss@artisteer.com', '1/31/1945');
INSERT INTO employee (id, first_name, email, birthday) VALUES (30, 'Gayelord', 'gspadellit@baidu.com', '4/12/1986');
INSERT INTO employee (id, first_name, email, birthday) VALUES (31, 'Chick', 'cbreadu@is.gd', '6/18/1995');
INSERT INTO employee (id, first_name, email, birthday) VALUES (32, 'Ruthie', 'rsilvermannv@nbcnews.com', '1/22/1994');
INSERT INTO employee (id, first_name, email, birthday) VALUES (33, 'Vanessa', 'vpulteneyew@elegantthemes.com', '10/21/1962');
INSERT INTO employee (id, first_name, email, birthday) VALUES (34, 'Rheta', 'rlexax@opensource.org', '2/17/1979');
INSERT INTO employee (id, first_name, email, birthday) VALUES (35, 'Erhart', 'esenchenkoy@admin.ch', '3/24/1974');
INSERT INTO employee (id, first_name, email, birthday) VALUES (36, 'Walton', 'wkuhlmeyz@time.com', '4/5/1967');
INSERT INTO employee (id, first_name, email, birthday) VALUES (37, 'Read', 'rtrain10@techcrunch.com', '3/10/1983');
INSERT INTO employee (id, first_name, email, birthday) VALUES (38, 'Tonnie', 'tbatchellor11@tiny.cc', '12/11/1952');
INSERT INTO employee (id, first_name, email, birthday) VALUES (39, 'Marsiella', 'mghelardi12@hud.gov', '8/10/1940');
INSERT INTO employee (id, first_name, email, birthday) VALUES (40, 'Kira', 'kluciani13@so-net.ne.jp', '1/3/1975');
INSERT INTO employee (id, first_name, email, birthday) VALUES (41, 'Catlaina', 'crummin14@comcast.net', '4/21/1976');
INSERT INTO employee (id, first_name, email, birthday) VALUES (42, 'Jabez', 'jkermitt15@hp.com', '9/7/1994');
INSERT INTO employee (id, first_name, email, birthday) VALUES (43, 'Ulick', 'ushea16@dell.com', '10/29/1997');
INSERT INTO employee (id, first_name, email, birthday) VALUES (44, 'Deirdre', 'dblancowe17@guardian.co.uk', '5/27/1994');
INSERT INTO employee (id, first_name, email, birthday) VALUES (45, 'Dag', 'dgomersal18@acquirethisfirst_name.com', '9/12/1968');
INSERT INTO employee (id, first_name, email, birthday) VALUES (46, 'Pansy', 'pgaishson19@indiatimes.com', '11/28/1981');
INSERT INTO employee (id, first_name, email, birthday) VALUES (47, 'Merci', 'mtrail1a@example.com', '7/7/1998');
INSERT INTO employee (id, first_name, email, birthday) VALUES (48, 'Jorgan', 'joilier1b@loc.gov', '6/8/1972');
INSERT INTO employee (id, first_name, email, birthday) VALUES (49, 'Ricardo', 'rrunciman1c@infoseek.co.jp', '6/10/1959');
INSERT INTO employee (id, first_name, email, birthday) VALUES (50, 'Sib', 'sboocock1d@ted.com', '2/7/1965');
```

```SQL
3.
    1. UPDATE employee
    SET email = 'test@test.com'
    WHERE id = 5

    2. UPDATE employee
    SET birthday = '1999-11-11'
    WHERE id = 8

    3. UPDATE employee
    SET first_name = 'Roberto'
    WHERE id = 2

    4. UPDATE employee
    SET email = 'interesting@int.com'
    WHERE id = 19

    5. UPDATE employee
    SET first_name = 'Arin'
    WHERE id = 25
```

```SQL
4.
    1. DELETE FROM employee
    WHERE first_name = 'Arin'

    2. DELETE FROM employee
    WHERE id = 2

    3. DELETE FROM employee
    WHERE email = 'test@test.com'

    4. DELETE FROM employee
    WHERE birthday = '1999-11-11'

    5. DELETE FROM employee
    WHERE first_name = 'Roberto'
```
