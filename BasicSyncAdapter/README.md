BasicSyncAdapter
================

This sample demonstrates how to implement a sync adapter to fetch background data for an app that doesn't require a user-visible account type or two-way synchronization.

The sample periodically downloads the feed from the [Android Developers Blog][1] and caches the data in a content provider. At runtime, the cached feed data is displayed inside a [ListView][2].

To learn more about creating and using sync adapters, see [Transferring Data Using Sync Adapters][3].

---

* [Source][4]

[1]: http://android-developers.blogspot.com/
[2]: https://developer.android.com/reference/android/widget/ListView.html
[3]: https://developer.android.com/training/sync-adapters/index.html
[4]: https://developer.android.com/samples/BasicSyncAdapter/index.html
