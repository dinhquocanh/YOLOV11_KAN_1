# grocery > 2024-03-18 12:31am
https://universe.roboflow.com/lamar-university-venef/grocery-rfn8l

Provided by a Roboflow user
License: CC BY 4.0

# Grocery Product Dataset Analysis

## Dataset Overview
- Total Classes: 62
- Total Images: 63,476
- Average Images per Class: 1,024

## Product Categories

### Beverages (28 Classes)
#### Coca-Cola Products
- Regular Variants: 20oz (2,963), 16oz (1,508), 350ml (55)
- Flavored Variants:
  * Cherry (915)
  * Cherry Vanilla (916)
  * Vanilla (2,265)
  * Spiced (1,271)
- Diet/Zero Variants:
  * Diet 20oz (2,705)
  * Diet Can 16oz (858)
  * Zero 16oz (194)

#### Other Sodas
- Sprite Family:
  * Regular: 20oz (2,619), 40oz (1,608), Can 16oz (808)
  * Flavored: Cherry (1,005), Tropical Mix (1,164)
  * Zero: 20oz (1,266)
- Fanta Products:
  * Regular: 20oz (1,587), Can 16oz (2,101)
  * Grape: 20oz (934)
  * Zero: 20oz (1,529)
- Dr Pepper:
  * 20oz (1,081), 1L (154), Can 16oz (828)
- Mountain Dew: 16oz (1,314 + 202)
- Barqs Black: 20oz (1,218)
- Crush: 16oz (207)

#### Minute Maid
- Blue Raspberry (1,639)
- Fruit Punch (1,200)
- Lemonade (1,378)
- Pink Lemonade (1,185)

### Snacks (34 Classes)

#### Chips
- Doritos:
  * Nacho Cheese (625)
  * Cool Ranch (617)
  * Spicy Nacho (633)
- Lays:
  * Classic (393)
  * Barbecue (635)
  * Limon (645)
- Cheetos:
  * Crunchy Regular (594)
  * Crunchy Flamin Hot (388)
  * Crunchy Flamin Hot Limon (641)
  * Crunchy XXTRA Flamin Hot (594)
  * Puffs (635)
- Funyuns Flamin Hot (594)

#### Cookies & Candies
- Oreo:
  * Regular (1,149)
  * King Size (1,141)
  * Double Stuf King Size (1,141)
- Chips Ahoy:
  * Regular (1,095)
  * King Size (1,141)
- Lenny & Larry's:
  * Birthday Cake (1,687)
  * Chocolate Chips (1,650)
  * Double Chocolate Chips (1,491)
  * Peanut Butter (1,599)
  * Peanut Butter Chocolate Chips (1,656)
  * Snickerdoodle (1,687)
- Other Candies:
  * Bueno Share Size (984)
  * Crunch (1,203)
  * Nerds Share Size (984)
  * Payday Share Size (824)
  * Skittles Share Size (2,133)
  * Sour Punch Share Size (984)
  * Whatchamacallit King Size (984)

## Distribution Analysis

### Image Count Distribution
- Highest Count: CocaCola20Oz (2,963)
- Lowest Count: CocaCola350Ml (55)
- Median Count: ~1,141

### Size Variants
- Standard Bottles: 16oz, 20oz, 40oz, 1L, 350ml
- Share Size / King Size variants for most candy products
- Regular and larger sizes for cookie products

### Image Capture Specifications
- The dataset will consist of 60+ products, each captured from a 360-degree perspective.
- Each product is  photographed at intervals of 15 degrees, resulting in a series of images covering the entire circumference of the product.