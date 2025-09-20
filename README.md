# note-repo


le probleme etrangement persiste toujours j'arrive tout pas a comprend comme si cela est un autre probleme la voila le resultat en logs : 



Context: while handling a pointer data packet
js_primitives.dart:28 Library: gestures library
js_primitives.dart:28 ===========================

js_primitives.dart:28 Another exception was thrown: Cannot hit test a render box that has never been laid out.
js_primitives.dart:28 
=== GlobalKey Error Details ===
js_primitives.dart:28 Location: dart-sdk/lib/_internal/js_dev_runtime/private/ddc_runtime/errors.dart 288:3     throw_
packages/flutter/src/rendering/box.dart 2729:11                                 <fn>
packages/flutter/src/rendering/box.dart 2759:14                                 hitTest
packages/flutter/src/rendering/box.dart 3150:23                                 <fn>
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/rendering/box.dart 3145:32                                 defaultHitTestChildren
packages/flutter/src/rendering/custom_layout.dart 419:12                        hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 2024:18                           hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 2024:18                           hitTest
packages/flutter/src/rendering/box.dart 3150:23                                 <fn>
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/rendering/box.dart 3145:32                                 defaultHitTestChildren
packages/flutter/src/rendering/flex.dart 1160:12                                hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/shifted_box.dart 95:23                           <fn>
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/rendering/shifted_box.dart 90:20                           hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/box.dart 3150:23                                 <fn>
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/rendering/box.dart 3145:32                                 defaultHitTestChildren
packages/flutter/src/rendering/custom_layout.dart 419:12                        hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 2024:18                           hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 3593:31                           hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/proxy_box.dart 2942:22                           <fn>
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/rendering/proxy_box.dart 2936:18                           hitTestChildren
packages/flutter/src/rendering/proxy_box.dart 2922:12                           hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 3728:31                           hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/widgets/overlay.dart 1033:80                               childHitTest
packages/flutter/src/rendering/box.dart 816:31                                  addWithPaintOffset
packages/flutter/src/widgets/overlay.dart 1034:21                               hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 3851:17                           hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/proxy_box.dart 185:63                            hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/widgets/tap_region.dart 222:72                             hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/proxy_box.dart 130:19                            hitTestChildren
packages/flutter/src/rendering/box.dart 2762:11                                 hitTest
packages/flutter/src/rendering/view.dart 302:12                                 hitTest
packages/flutter/src/rendering/binding.dart 642:34                              hitTestInView
packages/flutter/src/gestures/binding.dart 398:7                                [_handlePointerEventImmediately]
packages/flutter/src/gestures/binding.dart 390:5                                handlePointerEvent
packages/flutter/src/gestures/binding.dart 337:7                                [_flushPointerEventQueue]
packages/flutter/src/gestures/binding.dart 306:9                                [_handlePointerDataPacket]
lib/_engine/engine/platform_dispatcher.dart 1423:5                              invoke1
lib/_engine/engine/platform_dispatcher.dart 336:5                               invokeOnPointerDataPacket
lib/_engine/engine/pointer_binding.dart 405:30                                  [_sendToFramework]
lib/_engine/engine/pointer_binding.dart 225:7                                   onPointerData
lib/_engine/engine/pointer_binding.dart 1034:18                                 <fn>
lib/_engine/engine/pointer_binding.dart 948:7                                   <fn>
lib/_engine/engine/pointer_binding.dart 541:9                                   loggedHandler
dart-sdk/lib/_internal/js_dev_runtime/patch/js_allow_interop_patch.dart 212:27  _callDartFunctionFast1

js_primitives.dart:28 Context: while handling a pointer data packet
js_primitives.dart:28 Library: gestures library
js_primitives.dart:28 
