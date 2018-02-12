# Learning RxJava 2 for Android by example
### Using RxJava 2.0 Library in your application
Add this in your build.gradle
```groovy
compile 'io.reactivex.rxjava2:rxjava:2.1.1'
```
If you are using RxAndroid also, then add the following
```groovy
compile 'io.reactivex.rxjava2:rxandroid:2.0.1'
```

# RxJava 2 Examples present in this sample project

* RxJava 2.0 Example using `CompositeDisposable` as `CompositeSubscription` and `Subscription` have
been removed.

* RxJava 2 Example using `Flowable`.

* RxJava 2 Example using `SingleObserver`, `CompletableObserver`.

* RxJava 2 Example using RxJava2 operators such as `map, zip, take, reduce, flatMap, filter, buffer, skip, merge, concat, replay`, and much more:

* RxJava 2 Android Samples using `Function` as `Func1` has been removed.

* RxJava 2 Android Samples  using `BiFunction` as `Func2` has been removed.

* And many others android examples

# Quick Look on few changes done in RxJava2 over RxJava1

RxJava1 -> RxJava2

* `onCompleted` -> `onComplete` - without the trailing d
* `Func1` -> `Function`
* `Func2` -> `BiFunction`
* `CompositeSubscription` -> `CompositeDisposable`
* `limit` operator has been removed - Use `take` in RxJava2
* and much more.

# Operators :
* `Map` -> transform the items emitted by an Observable by applying a function to each item
* `Zip` -> combine the emissions of multiple Observables together via a specified function and emit single items for each combination based on the results of this function
* `Filter` -> emit only those items from an Observable that pass a predicate test
* `FlatMap` -> transform the items emitted by an Observable into Observables, then flatten the emissions from those into a single Observable
* `Take` -> emit only the first n items emitted by an Observable
* `Reduce` -> apply a function to each item emitted by an Observable, sequentially, and emit the final value
* `Skip` -> suppress the first n items emitted by an Observable
* `Buffer` -> periodically gather items emitted by an Observable into bundles and emit these bundles rather than emitting the items one at a time
* `Concat` -> emit the emissions from two or more Observables without interleaving them
* `Replay` -> ensure that all observers see the same sequence of emitted items, even if they subscribe after the Observable has begun emitting items
* `Merge` -> combine multiple Observables into one by merging their emissions

### License
```
   Copyright (C) 2011 Android Open Source Project

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

 
