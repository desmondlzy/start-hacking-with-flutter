# Start Hacking with Flutter
My notes on how to get started on flutter

## Before Write Any Codes...

- Make sure you have your [dev toolchain](https://flutter.dev/docs/get-started/install) ready.
- Flutter uses Dart, so take a quick [tour](https://dart.dev/guides/language/language-tour) of it right now (I would call Dart a smarter and cleaner version of Java, so it's fairly easy to learn)

## Golden Rule

GOOGLE IS OUR BEST FRIEND

### It means that...
Whenever you feel unsure how to implement layouts/features, or the signature of a class you plan to use, just google it out. Usually google is simply the most efficient way of getting problems solved. Based on my not-so-long learning and coding experience, Google with proper keywords gives a good solution in the top 3 results 95% of the time.

## Read List

In general, the [official website](https://flutter.dev/) gives a lot of useful information, tips, and best practices. The official website should be always be of top priority (and Google usually direct you there).

Finishing these items, you will be able to write any UI by yourself (theoretically).

- [Write your first app](https://flutter.dev/docs/get-started/codelab)
- In flutter, almost everything is a widget, so be sure to [understand the use of widgets](https://flutter.dev/docs/development/ui/widgets-intro)
- Then we can put the widgets together into the UI we want with [layouts](https://flutter.dev/docs/development/ui/layout) (This can take 70% of your time building any UI)
- We need to navigate in our app from page to page with [routing mechanics](https://flutter.dev/docs/cookbook/navigation/named-routes), sometimes with [arguments](https://flutter.dev/docs/cookbook/navigation/navigate-with-arguments) passing around.

After you read through the above, I think it's a good time to start writing some real code. Just remember the Golden Rule and try to make use of what you learned and build your app.

But Flutter really have a large number of widgets coming with the SDK that help you do a lot of things. So you may want to get familiar with (some of) them if you don't want to reinvent the wheel.

- [Widget of the week](https://www.youtube.com/watch?v=b_sQ9bMltGU&list=PLjxrf2q8roU23XGwz3Km7sQZFTdB996iG), my fav!.
- Read the rest part of the [cookbook](https://flutter.dev/docs/cookbook) as per your need.
- [Sliver](https://flutter.dev/docs/development/ui/advanced/slivers) is a very important concept and it is almost inevitable you will use it, but it can be also a bit hard to understand.

Then you may want to know how [Flutter manages state](https://flutter.dev/docs/development/data-and-backend/state-mgmt/options). This is a concept you don't need to know right away at this stage. But as the app scales up, lack of state management planning will eventually leads to spaghetti codebase, and a disaster of maintainance. This part is also why modern declarative UI frameworks are favored over those traditional frameworks. 
