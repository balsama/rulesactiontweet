Rules Tweet Action
==================

Originally, the goal of this module was to emulate the features already provided by services like [Twitter Feed](http://twitterfeed.com/). I still think that goal is justifiable and worthy. It occured to me, however, that it would be infinitely more powerful and scalable if we could implement a tweet function as an action in the Rules module.

So that's where we are now. It's doubtful that you'll see any meaningful code here soon, but that's the goal.

`EVENT: foo; CONDITION: bar=bar; ACTION: tweet!`

Of course, a requirement to this module is that the site registers their Drupal install as an App with twitter for oAuth.

More to come.
