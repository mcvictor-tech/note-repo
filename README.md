# note-repo


le probleme êrsite mais j'ai reussi a capturer les logs : 


══╡ EXCEPTION CAUGHT BY RENDERING LIBRARY ╞═════════════════════════════════════════════════════════
js_primitives.dart:28 The following assertion was thrown during performLayout():
js_primitives.dart:28 BoxConstraints forces an infinite width.
js_primitives.dart:28 The offending constraints were:
js_primitives.dart:28   BoxConstraints(w=Infinity, 0.0<=h<=24.0)
js_primitives.dart:28 
js_primitives.dart:28 The relevant error-causing widget was:
js_primitives.dart:28   Container
js_primitives.dart:28   Container:file:///C:/Users/HP%20OMEN/Desktop/Codes/Important/Alpha/frontend/mobile/admin-dashboard/lib/screens/articles/components/article_filters.dart:205:26
js_primitives.dart:28 
js_primitives.dart:28 When the exception was thrown, this was the stack:
js_primitives.d


The following RenderObject was being processed when the exception was fired: RenderConstrainedBox#3cf9a relayoutBoundary=up7 NEEDS-LAYOUT NEEDS-PAINT NEEDS-COMPOSITING-BITS-UPDATE:
js_primitives.dart:28   creator: ConstrainedBox ← Container ← Align ← ConstrainedBox ← Semantics ← DropdownMenuItem<String>
js_primitives.dart:28     ← IgnorePointer ← _Visibility ← _VisibilityScope ← Visibility ← _RawIndexedStack ← IndexedStack ←
js_primitives.dart:28     ⋯
js_primitives.dart:28   parentData: offset=Offset(0.0, 0.0) (can use size)
js_primitives.dart:28   constraints: BoxConstraints(0.0<=w<=Infinity, 0.0<=h<=24.0)
js_primitives.dart:28   size: MISSING
js_primitives.dart:28   additionalConstraints: BoxConstraints(w=Infinity, 0.0<=h<=Infinity)
js_primitives.dart:28 This RenderObject had the following descendants (showing up to depth 5):
js_primitives.dart:28     child: RenderFlex#0ad23 NEEDS-LAYOUT NEEDS-PAINT NEEDS-COMPOSITING-BITS-UPDATE
js_primitives.dart:28       child 1: RenderSemanticsAnnotations#9f5d6 NEEDS-LAYOUT NEEDS-PAINT NEEDS-COMPOSITING-BITS-UPDATE
js_primitives.dart:28         child: RenderExcludeSemantics#e2382 NEEDS-LAYOUT NEEDS-PAINT NEEDS-COMPOSITING-BITS-UPDATE
js_primitives.dart:28           child: RenderConstrainedBox#bb063 NEEDS-LAYOUT NEEDS-PAINT NEEDS-COMPOSITING-BITS-UPDATE
js_primitives.dart:28             child: RenderPositionedBox#391f4 NEEDS-LAYOUT NEEDS-PAINT NEEDS-COMPOSITING-BITS-UPDATE
js_primitives.dart:28       child 2: RenderConstrainedBox#b2e66 NEEDS-LAYOUT NEEDS-PAINT
js_primitives.dart:28       child 3: RenderParagraph#e1820 NEEDS-LAYOUT NEEDS-PAINT
js_primitives.dart:28         text: TextSpan
js_primitives.dart:28 ════════════════════════════════════════════════════════════════════════════════════════════════════
44js_primitives.dart:28 Another exception was thrown: Assertion failed: file:///D:/Stephen/flutter/packages/flutter/lib/src/rendering/box.dart:2176:12
js_primitives.dart:28 Another exception was thrown: Cannot hit test a render box with no size.
js_primitives.dart:28 
=== GlobalKey Error Details ===
js_primitives.dart:28 Location: dart-sdk/lib/_internal/js_dev_runtime/private/ddc_runtime/errors.dart 288:3     throw_
packages/flutter/src/rendering/box.dart 2745:9                                  <fn>
packages/flutter/src/rendering/box.dart 2759:14                                 hitTest
packages/flutter/src/rendering/box.dart 3150:23                                 <fn>



ackages/flutter/src/rendering/binding.dart 642:34                              hitTestInView
packages/flutter/src/gestures/binding.dart 398:7                                [_handlePointerEventImmediately]
packages/flutter/src/gestures/binding.dart 390:5                                handlePointerEvent
packages/flutter/src/gestures/binding.dart 337:7                                [_flushPointerEventQueue]
packages/flutter/src/gestures/binding.dart 306:9                                [_handlePointerDataPacket]
lib/_engine/engine/platform_dispatcher.dart 1423:5                              invoke1
lib/_engine/engine/platform_dispatcher.dart 336:5                               invokeOnPointerDataPacket
lib/_engine/engine/pointer_binding.dart 405:30                                  [_sendToFramework]
lib/_engine/engine/pointer_binding.dart 225:7                                   onPointerData
lib/_engine/engine/pointer_binding.dart 1024:16                                 <fn>
lib/_engine/engine/pointer_binding.dart 948:7                                   <fn>
lib/_engine/engine/pointer_binding.dart 541:9                                   loggedHandler
dart-sdk/lib/_internal/js_dev_runtime/patch/js_allow_interop_patch.dart 212:27  _callDartFunctionFast1

js_primitives.dart:28 Context: while handling a pointer data packet
js_primitives.dart:28 Library: gestures library
js_primitives.dart:28 ===========================

js_primitives.dart:28 Another exception was thrown: Cannot hit test a render box with no size.
js_primitives.dart:28 
=== GlobalKey Error Details ===
js_primitives.dart:28 Location: dart-sdk/lib/_internal/js_dev_runtime/private/ddc_runtime/errors.dart 288:3     throw_
packages/flutter/src/rendering/box.dart 2745:9                                  <fn>
packages/flutter/src/rendering/box.dart 2759:14                                 hitTest
packages/flutter/src/rendering/box.dart 3150:23                                 <fn>
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/rendering/box.dart 3145:32                                 defaultHitTestChildren
packages/flutter/src/rendering/custom_layout.dart 419:12                        hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
