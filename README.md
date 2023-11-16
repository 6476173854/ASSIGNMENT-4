<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
/* Default styles for all devices */
.gameslist {
  list-style: none; /* Remove bullet points */
}

.gameslist li {
  border-bottom: 1px solid #ccc; /* Add border-bottom to list items */
  padding: 10px; /* Add padding to list items */
}

.largekitten {
  display: block; /* Display the image with class .largekitten */
}

.smallkitten {
  display: none; /* Hide the image with class .smallkitten */
}

/* Mobile styles */
@media only screen and (max-width: 480px) {
  .largekitten {
    display: none; /* Hide the image with class .largekitten for mobile devices */
  }
}

/* Media query for screens with a width of 480 pixels and above */
@media only screen and (min-width: 480px) {
  .largekitten {
    display: none; /* Hide the image with class .largekitten */
  }

  .smallkitten {
    display: block; /* Display the image with class .smallkitten */
  }
}

/* Media query for screens with a width of 800 pixels and above */
@media only screen and (min-width: 800px) {
  .gameslist li {
    float: left; /* Float the list items of .gameslist to the left */
    border-bottom: none; /* Remove the border from the bottom */
    border-right: 1px solid #ccc; /* Add border to the right of each item */
  }
}

/* Media query for screens with a width between 900px and 1200px */
@media only screen and (min-width: 900px) and (max-width: 1200px) {
  h1 {
    font-size: 4rem; /* Set the font-size of h1 to 4rem */
  }
}

/* Media query for screens with a width of 1200 pixels and above */
@media only screen and (min-width: 1200px) {
  h1 {
    font-size: 6rem; /* Set the font-size of h1 to 6rem */
  }
}


</style>
  <title>Your Webpage Title</title>
</head>
<body>

  <div class="container">
    <img class="largekitten" src="largekitten.jpg" alt="Large Kitten Image">
    
    <ul class="gameslist">
      <li>ludo</li>
      <li>carrom</li>
      <li>basket</li>
    </ul>
    <h1>my name is ankush</h1>
  </div>

</body>
</html>
