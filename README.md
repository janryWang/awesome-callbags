# Callbag Libraries & Learning Material [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



## Table Contents

 - [Source factories](#source-factories)
 - [Sink factories](#sink-factories)
 - [Transformation operators](#transformation-operators)
 - [Filtering operators](#filtering-operators)
 - [Combination operators](#combination-operators)
 - [Utilities](#utilities)
 - [Misc](#misc)
 - [Redux middlewares](#redux-middlewares)


### Source factories

- [animation-frames](https://github.com/aaronshaf/callbag-animation-frames)
- [create](https://github.com/franciscotln/callbag-create)
- [gamepads](https://github.com/aaronshaf/callbag-gamepads)
- [keyboard](https://github.com/aaronshaf/callbag-keyboard)
- [interval](https://github.com/staltz/callbag-interval)
- [ms-elapsed](https://github.com/Andarist/callbag-ms-elapsed)
- [never](https://github.com/Andarist/callbag-never)
- [of](https://github.com/Andarist/callbag-of)
- [pausable-interval](https://github.com/staltz/callbag-pausable-interval)
- [timer](https://github.com/Andarist/callbag-timer)
- *Conversion from*:
  - [from](https://github.com/jadbox/callbag-from)
  - [from-obs](https://github.com/staltz/callbag-from-obs)
  - [from-iter](https://github.com/staltz/callbag-from-iter)
  - [from-event](https://github.com/staltz/callbag-from-event)
  - [from-delegated-event](https://github.com/krawaller/callbag-from-delegated-event)
  - [from-promise](https://github.com/staltz/callbag-from-promise)
  - [from-pull-stream](https://github.com/staltz/callbag-from-pull-stream)
  - [from-stream](https://github.com/jaw977/callbag-from-stream)

### Sink factories

- [for-each](https://github.com/staltz/callbag-for-each)
- [iterate](https://github.com/staltz/callbag-iterate)
- [observe](https://github.com/staltz/callbag-observe)
- [subscribe](https://github.com/zebulonj/callbag-subscribe)
- *Conversion to*:
  - [to-awaitable](https://github.com/staltz/callbag-to-awaitable)
  - [to-async-iterable](https://github.com/staltz/callbag-to-async-iterable)
  - [to-iterable](https://github.com/staltz/callbag-to-iterable)
  - [to-promise](https://github.com/Andarist/callbag-to-promise)
  - [to-pull-stream](https://github.com/staltz/callbag-to-pull-stream)
  - [to-rxjs](https://github.com/staltz/callbag-to-rxjs)

### Transformation operators

- [ap](https://github.com/shatteredaesthetic/callbag-ap)
- [delay](https://github.com/janryWang/callbag-delay)
- [exhaust-map](https://github.com/Andarist/callbag-exhaust-map)
- [flat-map](https://github.com/avinashcodes/callbag-flat-map)
- [flatten](https://github.com/staltz/callbag-flatten)
- [flatten-iter](https://github.com/aaronshaf/callbag-flatten-iter)
- [loop](https://github.com/Andarist/callbag-loop)
- [lossless-throttle](https://github.com/fasiha/callbag-lossless-throttle)
- [map](https://github.com/staltz/callbag-map)
- [map-delve](https://github.com/jaw977/callbag-map-delve)
- [map-to](https://github.com/krawaller/callbag-map-to)
- [map-when](https://github.com/franciscotln/callbag-map-when)
- [pairwise](https://github.com/Andarist/callbag-pairwise)
- [pluck](https://github.com/Andarist/callbag-pluck)
- [rescue](https://github.com/franciscotln/callbag-rescue)
- [scan](https://github.com/staltz/callbag-scan)
- [switch-map](https://github.com/avinashcodes/callbag-switch-map)
- [throttle](https://github.com/fasiha/callbag-throttle)
- [with-previous](https://github.com/krawaller/callbag-with-previous)

### Filtering operators

- [debounce](https://github.com/atomrc/callbag-debounce)
- [distinct-until-changed](https://github.com/Andarist/callbag-distinct-until-changed)
- [drop-after](https://github.com/Andarist/callbag-drop-after)
- [drop-repeats](https://github.com/franciscotln/callbag-drop-repeats)
- [drop-until](https://github.com/Andarist/callbag-drop-until)
- [filter](https://github.com/staltz/callbag-filter)
- [filter-promise](https://github.com/fasiha/callbag-filter-promise)
- [first](https://github.com/MartyJiang/callbag-first)
- [last](https://github.com/MartyJiang/callbag-last)
- [partition](https://github.com/Andarist/callbag-partition)
- [reject](https://github.com/franciscotln/callbag-reject)
- [skip](https://github.com/staltz/callbag-skip)
- [take](https://github.com/staltz/callbag-take)
- [take-until](https://github.com/franciscotln/callbag-take-until)
- [take-while](https://github.com/Andarist/callbag-take-while)

### Combination operators

- [buffer](https://github.com/Andarist/callbag-buffer)
- [buffer-time](https://github.com/Andarist/callbag-buffer-time)
- [cartesian-product](https://github.com/fasiha/callbag-cartesian-product)
- [combine](https://github.com/staltz/callbag-combine)
- [concat](https://github.com/staltz/callbag-concat)
- [concat-with](https://github.com/Andarist/callbag-concat-with)
- [default-if-empty](https://github.com/Andarist/callbag-default-if-empty)
- [merge](https://github.com/staltz/callbag-merge)
- [merge-with](https://github.com/krawaller/callbag-merge-with)
- [pull-when](https://github.com/Andarist/callbag-pull-when)
- [sample](https://github.com/staltz/callbag-sample)
- [sample-combine](https://github.com/krawaller/callbag-sample-combine)
- [sample-when](https://github.com/Andarist/callbag-sample-when)
- [start-with](https://github.com/krawaller/callbag-start-with)

### Multicasting

- [behavior-subject](https://github.com/zebulonj/callbag-behavior-subject)
- [remember](https://github.com/Andarist/callbag-remember)
- [share](https://github.com/staltz/callbag-share)
- [subject](https://github.com/staltz/callbag-subject)

### Utilities

- [latest](https://github.com/krawaller/callbag-latest)
- [mock](https://github.com/krawaller/callbag-mock)
- [pipe](https://github.com/staltz/callbag-pipe)
- [proxy](https://github.com/krawaller/callbag-proxy)
- [pump](https://github.com/zebulonj/callbag-pump)
- [tap](https://github.com/krawaller/callbag-tap)
- [tap-up](https://github.com/Andarist/callbag-tap-up)
- [worker](https://www.npmjs.com/package/callbag-worker)

### Misc

- [basics](https://github.com/staltz/callbag-basics)
- [pipe-me](https://github.com/sartaj/pipe-me)
- [pseudo-rxjs](https://github.com/staltz/callbag-pseudo-rxjs)
- [react-callbag-subject](https://github.com/aaronshaf/react-callbag-subject)

### Redux middlewares

- [redux-callbag](https://github.com/janryWang/redux-callbag)
