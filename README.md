# ScrollViews-Demo

There is 3 types of Scrollable Views

- UIScrollView
- UICollectionView
- UITableView

Each has Pros and Cons

## UIScrollView

- It is needed first to pin the scroll view to the parent VC with its 4 edges
- And second to pin whatever's inside the scroll view to scroll view itself, below it is the stack view

![UIScrollView](https://github.com/mesutgdk/ScrollViews-Demo/assets/112901255/0293d089-da10-468e-8111-80cd236206b7)



## UICollectionView

![UICollectionView](https://github.com/mesutgdk/ScrollViews-Demo/assets/112901255/b8a282d0-12f1-467a-b9d0-777ec5b92b7b)

## UITableView

![UITableView](https://github.com/mesutgdk/ScrollViews-Demo/assets/112901255/ae6c6834-a88f-499c-b50a-784d75e21553)


## Pros & Cons

### UIScrollView (Common)

🥙 Pros

- Make anything scrollable
- Minimalist
- Full Control
- Good for long pages

🧘🏿 Cons

- Cant easly reload
- No built affordances (i.e. pull to refresh)
- Auto Layout more complex

### UICollectionView (Rare)

🍇 Pros

- Customizable layouts
- Multi-column scrollable
- Can dynamically change layout
- Good for photos in a grid

🤾🏻 Cons

- More complex
- Often overkill

### UITableView (All The Time!)

🍔 Pros

- Highly preformant (reuseIdentifiers)
- Many affordances built in (headers, footers, sections)
- Perfect for single column lists

🏋🏼 Cons

- Hard to do complex non-single column layouts




