# ASSIGNMENT2-ANCHURI

# Anchuri Sindhuja
### Museum of London

Step inside the museum of London for an unforgettable journey through the capital's turbulent past. Discover **prehistoric London**, see how the city changed under **Romans and Saxons**,<br> wonder at ___medieval London and examine the tumultuous years when London was ravaged by civil wars.__

### Airport Routemap
The airport that is closest to the museum is London Heathrow (LHR)

1.Heathrow Airport (LHR)
2.Head northwest on Hatton Cross Roundabout
3.Exit the roundabout onto Faggs Rd
4.Turn left onto Great South-West Rd/A30
5.Turn left onto The Pkwy/A312
6.A40 turns slightly left and becomes King Edward St
7.Continue onto Montague St
8.At Rotunda, take the 2nd exit onto London Wall/A1211
8.Turn left
9.Museum of London, 150 London Wall, London EC2Y 5HN, United Kingdom

### Places around musuem
* Stonehenge
* Windsor Castle 
* Bath from London 
* Stonehenge
* Windsor Castle 

[AboutMe.md]                                                     (C:\Users\S550588\Desktop\ASSIGNMENT2-ANCHURI\AboutMe.md)

---------------------------------------------------------------------------------------------------------
### Tables

I would recommend to visit New York, Boston, Texas, New Jersey cities in USA. The first coloum in the table includes Name of the city, second coloum includes important location to visit and the third coloum indicates the  amount of time to spend visiting the important location.

| Name of the city | Location to visit     | Time spent in the location  |
|------------------|-----------------------|-----------------------------|  
| New York         | Statue of Liberty     |  2 hours                    |
| Boston           | New England Aquarium  |  2 hours                    |
| Texas            | San Antonio River Walk|  1 hour                     |
| New Jersey       | Ocean City            |  30 mins                    |
 
 --------------------------------------------------------------------------------------------------------

### Pithy Quotes

> When you're building a character, or at least when I'm building a character, you start saying, 'How am I going to make people like him?' - *John sandford*

> "Be not afraid of greatness. Some are born great, some achieve greatness, and others have greatness thrust upon them.” - *William Shakespeare*

---------------------------------------------------------------------------------------------------------

###  Code Fencing

>[article](https://css-tricks.com/php-templating-in-just-php/)

$ <?php

function getTwitterStatus($userid){
$url = "https://api.twitter.com/1/statuses/user_timeline/$userid.xml?count=1&include_rts=1callback=?";

$xml = simplexml_load_file($url) or die("could not connect");

       foreach($xml->status as $status){
       $text = $status->text;
       }
       echo $text;
 }

// USAGE
getTwitterStatus("chriscoyier");

?>

> [PHP Snippet source](https://css-tricks.com/snippets/php/get-latest-twitter-status/)


