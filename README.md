# assignment2-Vemula
# Mounitha Vemula
### Indian Cricket

My favorite sport is cricket.Itgives me refreshment when i was not feeling good.**Cricket is simple but it is very complicated**.It gives the chance to each and every player in the team.It is very good exercise to our body and it is very thrilling game.**It is full of emotion**.


Indian Cricket Team
--------
1. Mahendra Singh Dhoni
2. Ravindra Jadeja
3. Ashwin 


-------
* Australia Cricket Team
* Bangladesh Cricket Team
* Newzland Cricket Team 

> Link to AboutMe.md [About Me](https://github.com/VEMULA-MOUNITHA/assignment2-Vemula/blob/main/AboutMe.md)

------
### Countries
------
Below table describes about the countries which I wish to vist and I would like to recommend to visit and the reasons for visiting these countries.

-----------------
| Name of the Country | Reason | Number Of Days|
| ----------| ------| ------|
| Europe | Visiting New Architecture,Catching the Northern Lights | 19 |
| United States | Wildlife Viewing,National Parks,Disney Parks | 21 |
| Australia | Weather,Perfect Roadtrip Destination,Beaches | 15 |
| France | World famous cuisine,Mountains and jagged coastlines | 11 |

-------
### Pithy Quotes

> “Nothing sucks more than that moment during an argument when you realize you’re wrong.” *George Carlin*


> “only Married People Can Understand How You Can Be Miserable And Happy At The Same Time." *Chris Rock*

-------
### Code Fencing
-------
> Wordpress config misbehaving in opposite ways using two configs (https://stackoverflow.com/questions/75289444/wordpress-config-misbehaving-in-opposite-ways-using-two-configs)


```
function exclude_post_categories($excl='', $spacer=' ') {
  $categories = get_the_category(get_the_ID());
  if (!empty($categories)) {
    $exclude = $excl;
    $exclude = explode(",", $exclude);
    $thecount = count(get_the_category()) - count($exclude);
    foreach ($categories as $cat) {
      $html = '';
      if (!in_array($cat->cat_ID, $exclude)) {
        $html .= '<a href="' . get_category_link($cat->cat_ID) . '" ';
        $html .= 'title="' . $cat->cat_name . '">' . $cat->cat_name . '</a>';
        if ($thecount > 0) {
          $html .= $spacer;
        }
        $thecount--;
        echo $html;
      }
    }
    }
  }

```
> code snippets of above code (https://css-tricks.com/snippets/wordpress/the_category-excludes/)