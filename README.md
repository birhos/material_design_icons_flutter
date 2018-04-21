# material_design_icons_flutter

The [Material Design Icons](https://materialdesignicons.com/) Icon pack available as set of Flutter Icons.

Based on Material Design Icons 2.3.50. Includes 2350 icons.

This package will respect Material Design Icons' version since it might introduce breaking changes between **minor** versions.

## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
  material_design_icons_flutter: 2.3.50
```

## Usage

```dart
import 'package:material_design_icons_flutter/material_design_icons_flutter.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      // Use the MdiIcons class for the IconData
      icon: new Icon(MdiIcons.sword), 
      onPressed: () { print("Using the sword"); }
     );
  }
}
```

## Name Conversion

Some icons' name is reversed keyword in Dart (and most other languages), so the names have been changed.

- `null` -> `nullIcon`
- `switch` -> `switchIcon`
- `sync` -> `syncIcon`
