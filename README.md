# provider-3.1.0-1
A mixture between dependency injection (DI) and state management, built with widgets for widgets.  It purposefully uses widgets for DI/state management instead of dart-only classes like Stream. The reason is, widgets are very simple yet robust and scalable.  By using widgets for state management, provider can guarantee:  maintainability, through a forced uni-directional data-flow testability/composability, since it is always possible to mock/override a value robustness, as it is harder to forget to handle the update scenario of a model/widget

Use this package as a library

1. Depend on it

Add this to your package's pubspec.yaml file:


dependencies:
  provider: ^3.1.0+1

2. Install it

You can install packages from the command line:

with Flutter:


$ flutter pub get

Alternatively, your editor might support flutter pub get. Check the docs for your editor to learn more.

3. Import it

Now in your Dart code, you can use:


import 'package:provider/provider.dart';
  
