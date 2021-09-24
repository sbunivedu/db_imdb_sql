## IMDb Database

Consider the schema of the IMDb (The Internet Movie Database). Write queries to answer the following questions. 
```
actors(id, first_name, last_name, gender, film_count)
directors(id, first_name, last_name)
movies(id, name, year, rank)
directors_genres(director_id, genre, prob)
movies_directors(director_id, movie_id)
movies_genres(movie_id, genre)
```

1. Find the actors who have "mick" in their first names.
1. Find the number of genres each movie is in.
1. What are the names of all movies released in 1995?
1. How many people played a part in the movie "Lost in Translation"?
1. What are the names of all the people who played a part in the movie "Lost in Translation"?
1. Who directed the movie "Fight Club"?
1. How many movies has Clint Eastwood directed?
1. What are the names of all directors who have
  directed at least one horror movie?
1. What are the names of every actor who has appeared
  in a movie directed by Christopher Nolan?
1. Consider all actors that had five or more roles in a movie in 2010. List each such actor's name, the movie name, and the roles he/she played. Your answer should have one tuple for each combination of (actor, movie, role) - so if an actor has 10 roles in a given movie, there should be 10 tuples for that actor and movie.
1. For each year, count the number of movies in that year that had only female actors. A movie without any actors is also a movie with only female actors (since there are no male actors in such a movie!).
1. For each year, report the percentage of movies with only female actors made that year, and also the total number of movies made that year.
1. Find the movie(s) with the largest cast. Return the movie title and the size of the cast. By "cast size" we mean the number of distinct actors that played in that movie: if an actor played multiple roles, or if the actor is simply listed more than once, we still count her/him only once. You may not assume that only one film has the largest cast.
1. A decade is a sequence of 10 consecutive years. For example 1965, 1966, ..., 1974 is a decade, and so is 1967, 1968, ..., 1976. Find the decade with the largest number of movies.
1. (optional) The Bacon number of an actor is the length of the shortest path between the actor and Kevin Bacon in the "co-acting" graph. That is, Kevin Bacon has Bacon number 0; all actors who acted in the same film as KB have Bacon number 1; all actors who acted in the same film as some actor with Bacon number 1 (but not with Bacon himself) have Bacon number 2, etc. Count how many actors have Bacon number is 2.
* https://oracleofbacon.org
* https://oracleofbacon.org/onecenter.php?who=Kevin+Bacon
