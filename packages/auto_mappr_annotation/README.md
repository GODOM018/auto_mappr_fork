<a href="https://github.com/netglade">  
  <img alt="netglade" height='120px' src="https://raw.githubusercontent.com/netglade/auto_mappr/main/packages/auto_mappr_annotation/doc/badge.png">  
</a>

Developed with 💚 by [netglade][netglade_link]

[![ci][ci_badge]][ci_badge_link]
[![auto_mappr_annotation][auto_mappr_annotation_pub_badge]][auto_mappr_annotation_pub_link]
[![license: MIT][license_badge]][license_badge_link]
[![style: netglade analysis][style_badge]][style_badge_link]
[![Discord][discord_badge]][discord_badge_link]

---

`@AutoMappr` annotation used for [AutoMappr][auto_mappr_pub_link] code generator.

```dart
import 'package:auto_mappr_annotation/auto_mappr_annotation.dart';

import 'main.auto_mappr.dart';

@AutoMappr([
  MapType<UserDto, User>(),
])
class Mappr extends $Mappr {}
```

[netglade_link]: https://netglade.com/en
[ci_badge]: https://github.com/netglade/auto_mappr/actions/workflows/ci.yaml/badge.svg
[ci_badge_link]: https://github.com/netglade/auto_mappr/actions
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_badge_link]: https://opensource.org/licenses/MIT
[style_badge]: https://img.shields.io/badge/style-netglade_analysis-26D07C.svg
[style_badge_link]: https://pub.dev/packages/netglade_analysis
[auto_mappr_pub_link]: https://pub.dartlang.org/packages/auto_mappr
[auto_mappr_annotation_pub_badge]: https://img.shields.io/pub/v/auto_mappr_annotation.svg
[auto_mappr_annotation_pub_link]: https://pub.dartlang.org/packages/auto_mappr_annotation
[discord_badge]: https://img.shields.io/discord/1091460081054400532.svg?logo=discord&color=blue
[discord_badge_link]: https://discord.gg/sJfBBuDZy4
