How many albums does the artist Led Zeppelin
have? 

SELECT Name, COUNT(Title)
FROM artists INNER JOIN albums
ON artists.ArtistId = albums.ArtistId
WHERE Name = 'Led Zeppelin'
