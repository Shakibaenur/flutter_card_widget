# Flutter Card Widget

The Card widget in the Flutter framework allows for creating surfaces with shadows and rounded corners, making it ideal for displaying content in articles, lists, and other UI sections. It offers various properties to customize the card's appearance to your liking.

## Specifying the Child Widget:
The Card widget can contain a child widget that represents the card's content. For example, to place text inside a card:

Example:

Card(
child: Text('This is a card'),
)

## Setting Color:
The color property changes the card's background color. This example shows a card with a blue background:

Example:

Card(
color: Colors.blue,
child: Text('Colored Card'),
)

## Increasing Elevation:
The elevation property adjusts the height of the card's shadow. Higher values create a more prominent shadow. For instance:

Example:

Card(
elevation: 8,
child: Text('Elevated Card'),
)



## Shape:
The shape property allows modification of the card's corners, such as making them rounded:

Example:

Card(
shape: RoundedRectangleBorder(
borderRadius: BorderRadius.circular(15.0),
),
child: Text('Rounded Corners Card'),
)

## Margin:
The margin property sets the card's margin:



Example:

Card(
margin: EdgeInsets.all(16.0),
child: Text('Margin Card'),
)

## Border on Foreground Control:
The borderOnForeground property controls if the card's border appears on the foreground:

Example:

Card(
borderOnForeground: false,
child: Text('Border Not on Foreground Card'),
)



## Clip Behavior:
The clipBehavior property defines how the content inside the card is clipped, with options such as Clip.none, Clip.hardEdge, and Clip.antiAlias:

Example:

Card(
clipBehavior: Clip.antiAlias,
child: Text('Anti-aliased Clip Card'),
)

## Semantic Container:
When set to true, the card is treated as a semantic container, otherwise, its children's semantics merge with the nearest enclosing semantic container:

Example:

Card(
semanticContainer: true,
child: Text('Semantic Container Card'),
)

## Shadow Color:
The shadowColor property sets the color of the card's shadow:

Example:

Card(
shadowColor: Colors.red,
child: Text('Shadow Color Card'),
)



## Border Radius:
The borderRadius property customizes the radius of the card's corners:

Example:

Card(
shape: RoundedRectangleBorder(
borderRadius: BorderRadius.circular(30.0),
),
child: Text('Custom Border Radius Card'),
)



## Properties of Card Widget:

borderOnForeground: This property takes in a boolean value as an object to decide whether to print a border or not.

child: This property takes in a widget as an object to show inside the Card widget.

clipBehavior: This property decides whether the content inside the Card will be clipped or not. It takes Clip enum as an object.

color: This property assigns background color to the card by taking in the Color class as the object.

elevation: This property takes in a double value as the object to decide the z-coordinate where the card should be placed.

margin: This property takes in EdgeInsetsGeometry as the object to add empty space around the Card.

semanticContainer: This property takes in a boolean as the object. This controls whether the Card widget with all its child widget will be seen as a single widget or not.

shadowColor: This property takes in Color class as the object to assign a color to the shadow, which appears beneath the card. By default, the color is set to black.

shape: This property takes ShapeBorder class as the object to decide the shape of the Card widget.



## Reference:

https://www.geeksforgeeks.org/flutter-card-widget

https://www.javatpoint.com/flutter-card


