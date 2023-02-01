# Srilakshmi Jonnala
# i'm studying my master's at Northwest Missouri State University in applied computer science program. i completed my under graduation at vignan's university in ECE .

![aboutme](/photo.jpeg)

---

# Trip

Here this table consists of countries that i visited , reason for the visit and number of days that i stayed there in those countries.


|  **Country**        | **Reason to visit**            |   **Number of Days**      |
|---------------------|--------------------------------|---------------------------|
| India               | visit places                   |   5                       |
| USA                 | for education                  |   6                       |
| UK                  | Visit places                   |   7                       |
| Egypt               | for education                  |   8                       |

---

# Phity Quotes

> I'm sick of following my dreams, man. I'm just going to ask where they're going and hook up with ’em later -_Mitch Hedberg_
>
> My mother always used to say: The older you get, the better you get, unless you’re a banana -_Rose_

---

# Code Fencing

> WordPress: How to retrieve custom field data from the page?

[Link](https://stackoverflow.com/questions/66293239/wordpress-how-to-retrieve-custom-field-data-from-the-page)

Word Press
```
<h3>All Post Meta</h3>

<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>
```

[Dump All Custom Fields](https://css-tricks.com/snippets/wordpress/dump-all-custom-fields)
