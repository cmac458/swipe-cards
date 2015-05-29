Swipe Cards Tri-Directional
===================

Swipeable card based layout for Ionic and Angular. 

Note: There is also a similar ion library here: https://github.com/driftyco/ionic-ion-swipe-cards where you swipe the cards down instead of left or right. Which this is based on. 

<!-- [Demo](http://codepen.io/ionic/pen/nxEdH) -->

<!-- ## Install

    `bower install ionic-contrib-tinder-cards` -->

    ## Usage

    Include `swipecards.js`, `collide.js` and `swipecards.css` after the rest of your Ionic and Angular includes. Add `ionic.contrib.ui.tinderCards` as a module dependency of your app. Then use the following AngularJS directives:

    ```html
    <td-cards>
    <td-card ng-repeat="card in cards" on-destroy="cardDestroyed($index)" on-swipe="cardSwiped($index)">
    Card content here
</td-card>
</td-cards>
```

To add new cards dynamically, just add them to the cards array:

```javascript
$scope.cards = [
{ // card 1 },
{ // card 2 }
];

$scope.cardDestroyed = function(index) {
  $scope.cards.splice(index, 1);
};

$scope.cardSwiped = function(index) {
  var newCard = // new card data
  $scope.cards.push(newCard);
};
```



