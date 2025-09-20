# note-repo


le ^robleme de bottom overflowed persiste : 

[PaginationControls] currentPage: 1, totalPages: 4, itemsPerPage: 50, itemCount: 50, totalItems: 160, start: 1, end: 50
js_primitives.dart:28 Another exception was thrown: RenderFlex children have non-zero flex but incoming height constraints are unbounded.
js_primitives.dart:28 Another exception was thrown: Assertion failed: 


pourquoi cela persiste : 
de plus il ya aussi cette erreure que je voit 

en console quand je lance mon app 

══╡ EXCEPTION CAUGHT BY WIDGETS LIBRARY ╞═══════════════════════════════════════════════════════════
js_primitives.dart:28 The following assertion was thrown while applying parent data.:
js_primitives.dart:28 Incorrect use of ParentDataWidget.
js_primitives.dart:28 The ParentDataWidget Positioned(right: 16.0, bottom: 16.0) wants to apply ParentData of type
js_primitives.dart:28 StackParentData to a RenderObject, which has been set up to accept ParentData of incompatible type
js_primitives.dart:28 ParentData.
js_primitives.dart:28 Usually, this means that the Positioned widget has the wrong ancestor RenderObjectWidget. Typically,
js_primitives.dart:28 Positioned widgets are placed directly inside Stack widgets.
js_primitives.dart:28 The offending Positioned is currently placed inside a Opacity widget.
js_primitives.dart:28 The ownership chain for the RenderObject that received the incompatible parent data was:
js_primitives.dart:28   MouseRegion ← _FloatingRefreshButton ← Positioned ← Opacity ← Transform ← AnimatedBuilder ← Stack
js_primitives.dart:28 ← Obx ← NotificationListener<OverscrollIndicatorNotification> ←
js_primitives.dart:28 NotificationListener<ScrollNotification> ← ⋯
js_primitives.dart:28 
js_primitives.dart:28 When the exception was thrown, this was the stack:
js_primitives.dart:28 dart-sdk/lib/_internal/js_dev_runtime/private/ddc_runtime/errors.dart 288:3     throw_
js_primitives.dart:28 packages/flutter/src/widgets/framework.dart 6689:11                             <fn>
js_primitives.dart:28 packages/flutter/src/widgets/framework.dart 6705:14                             [_updateParentData]
js_primitives.dart:28 packages/flutter/src/widgets/framework.dart 6749:7                              attachRenderObject
