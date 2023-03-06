You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed next to such an item.

Implement the method which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:

`[]`                                - output:  `"no one likes this"`  
`["Peter"]`                         - output:  `"Peter likes this"`  
`["Jacob", "Alex"]`                 - output:  `"Jacob and Alex like this"`  
`["Max", "John", "Mark"]`           - output:  `"Max, John and Mark like this"`  
`["Alex", "Jacob", "Mark", "Max"]`  - output:  `"Alex, Jacob and 2 others like this"`  

Note: for 4 or more names, the number in *"and 2 others"* simply increases.
