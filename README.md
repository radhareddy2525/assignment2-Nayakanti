# assignment2-Nayakanti
# Radha Nayakanti
###### Melbourne Australia

 Melbourne is one of the best place for Nature lovers. Melbourne’s winding alleyways are **magical**; they’ll probably make you feel as though you’ve stepped into a real-life __Wonderland__. The city is well-known across Australia for its vibrant laneway culture, which is brimming with bustling shopping arcades, wandering musicians, live music, quiet street-side book cafes… and the occasional secret street party.

***
# Directions to My Favourite Place
1. Book a ride  from Mayville to Kansas City Airport.
2. Then book a best flight based on iternary from kanas to Melbourne as it takes long time to travel.
   1. Pack all the necessary items for Travelling.
   2. Make Sure to reach the Airport before three hours of departure time.
   3. Once reaching Melbourne Airport take a ride to Victoria.
   4. After Reaching Victoria take a motel to stay until your trip.
3. Finally Reached at your Favourite Place.
* Below are the foods that are bought to my favourite place
   * Meat
   * Alcohol
   * Playing Cards
   * Food
   * FireWood
   * DJ speakers



[Link to AboutMe file](https://github.com/S545020/assignment2-Nayakanti/blob/main/AboutMe.md)

---
# Table Creation using Markdown language
Below Table describles the food items that someone must try. The Table consists of name of food items and the place where these items will be avalible and then cost of the particular food item.
| Name of Food Item | Location | Cost of Item |
| --- | --- | ---: |
| Biryani| Hyderabad | $30 |
| Momos | Kolkata| $10 |
| Pani Puri | Maharashtra | $5 |
| Fish Fry | Kolkata | $25 |
---
# Block Quotes usage in Markdown language
> Life is from the inside out. When you shift on the inside life shifts on the outside. *Marcus Aurelius*

> The Happiness of your life depends on the quality of your thougths. *Seneca*
---
# Code Fencing usage in Markdown language
> The Fibonacci Sequence is the series of numbers(0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...). The next number is found by adding up the two numbers before it. For Example: the 2 is found by adding the two numbers before it (1+1), the 3 is found by adding the two numbers before it (1+2),the 5 is (2+3), and so on!

Link to Fibaonacci Source  <https://www.mathsisfun.com/numbers/fibonacci-sequence.html>
```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
} 
```
Link to the source code <https://cp-algorithms.com/algebra/fibonacci-numbers.html>