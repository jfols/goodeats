# goodeats

A curated list of places to eat in the Central Ohio area.

## Adding Information

Places are added in the `_data/places.yml` data file. Each region (Westerville, Columbus, etc) are an element in the main list with each `location` representing individual location information.

```yml
- name: Make Believe World
  locations:
    - name: The Watering Hole
      emoji: 🍵
      address: 1234 Main Road, Make Believe World, OH 12345
      website: http://example.com/
      recommendations:
        - Don't eat the burritos.
        - The hamburger is the best.
    - name: Local Food Truck
      emoji: ☕️🍸🥃🍺
      address: 3rd and 5th, Make Believe World, OH 98765
      website: http://example.net
      recommendations:
```