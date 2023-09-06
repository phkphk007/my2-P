# my2-P
# HEMANTH KUMAR P
###### Bali

Every Kind Of Natural Beauty. Beyond stunning beaches and magical temples, Bali has virtually every kind of natural beauty. **Glorious mountainous** areas with lush greenery, scenic lakes, gorgeous waterfalls, iconic rice fields, flower gardens, **gushing sacred rivers** and secret canyons all make up the island's landscape

***

[Link to my bio](MyStats.md)

***

## Sports And Games

This table has out door sports like football, cricket, tennis and badminton which are very competitive and some of the most watched sports around the world


| Sport | Reason to Play | Hours/Week |
| --- | --- | --- |
| Cricket | Can be played with small group of people | 6 |
| Foot Ball | Involves all players and very entertaining | 4 |
| Tennis | Improves balance and hand eye coordination | 4 |
| Badminton | Improves fitness | 5 |

***

## Sayings By Scientists

> “It is strange that only extraordinary man-made the discoveries twitch later appear so easy and simple.” – *George C. Lichtenberg*.

> “Art is the tree of life. Science is the tree of death.” – *William Blake*

> “Rockets are cool. There’s no getting around that.” – *Elon Musk*

***

## Namasthe India

> Add multiple categories to body class Wordpress

[link to wordpress code in stackoverflow](https://stackoverflow.com/questions/45972062)

```  

add_filter('body_class','add_category_to_single');
  function add_category_to_single($classes) {
    if (is_single() ) {
      global $post;
      foreach((get_the_category($post->ID)) as $category) {
        // add category slug to the $classes array
        $classes[] = $category->category_nicename;
      }
    }
    // return the $classes array
    return $classes;
  }

  ```
   
   [link to code snippet](https://css-tricks.com/snippets/wordpress/add-category-name-body_class/)
