# Problem 3 Failures
- List any other students you worked with:
- Generative AI transcript URL (if any):
- About how long did you work on this problem? 

For each section below, describe exactly which constraint is violated and how it is being violated. If any of these query run successfully, you need to go back and tweak your table settings, as you have not correctly established all the constraints. There are a lot of these, but each really should not take you that long. **Beware that some queries might have multiple constraints being violated, so make sure you identify everything that is wrong.**


## A)
```sql
INSERT INTO hw5.ratings (reviewer_id, movie_id, stars, rating_date) 
VALUES
  (1, 2, 0, '2012-02-18');
```
Description:



## B)
```sql
INSERT INTO hw5.ratings (reviewer_id, movie_id, stars, rating_date) 
VALUES
  (4, 3, 4.3, '1999-12-31');
```
Description:



## C)
```sql
INSERT INTO hw5.reviewers (id) 
VALUES
  (20);
```
Description:



## D)
```sql
INSERT INTO hw5.ratings (reviewer_id, movie_id, stars) 
VALUES
  (1, 3, 3);
```
Description:



## E)
```sql
INSERT INTO hw5.movies (id, title, year, director) 
VALUES
  (51, 'The Graduate', 1867, 'Mike Nichols'),
  (52, 'The Graduate', 1867, 'Krzysztof Kieslowski');
```
Description:



