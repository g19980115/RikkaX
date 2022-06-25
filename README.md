# RikkaX 

[![](https://jitpack.io/v/g19980115/RikkaX.svg)](https://jitpack.io/#g19980115/RikkaX)

Libraries used in Rikka apps.

Because these libraries were for internal use, some of them may not be suitable as public libraries.

The libraries suitable as public libraries are as follows.

-------------------

## [AppCompat](./appcompat)

Modified version of AndroidX AppCompat.

## [Compatibility](./compatibility)

Helper class that helps you to check device information. For example, if the device runs MIUI.

## Html

### [Html](./html/html)

Copy of `android.text.Html` class.

### [Html-ktx](./html/html-ktx)

A ktx library to simplify `Html.fromHtml`.

## [Insets](./insets)

Handle window insets without writing `OnApplyWindowInsetsListener` everywhere.

## [LittleEndianDataStream](./io/little-endian-data-stream)

Similar to DataStreams classes, but in little-endian.

## [LayoutInflater](./layoutinflater)

Implementation of `android.view.LayoutInflater.Factory2` which makes custom attributes for all views possible.

## [Lazy](./lazy)

Lazy initialization helper classes, similar to Kotlin, but for Java-only projects.

## Lifecycle

### [ResourceLiveData](./lifecycle/lifecycle-resource-livedata)

MutableLiveData class with status.

### [SharedViewModel](./lifecycle/lifecycle-shared-viewmodel)

ViewModel that shares across activities.

### [ViewModelLazy](./lifecycle/lifecycle-viewmodel-lazy)

An easier-to-use version of ViewModelLazy than Androidx.

## Material

### [MaterialPreference](./material/material-preference)

Android 12 Settings app-styled preference.

## [ParcelableList](./parcelablelist)

Helper class to transfer a large list of Parcelable objects through Binder.

## [MultiProcessPreference](./preference/multiprocess)

ContentProvider-based SharedPreference with multi-process support.

## [SimpleMenuPreference](./preference/simplemenu-preference)

A version of `ListPreference` that use Simple Menus from Material Design 1.

## RecyclerView
### [RecyclerViewKtx](./recyclerview/recyclerview-ktx)

RecyclerView helper.

## Widget

### [BorderView](./widget/borderview)

BorderRecyclerView BorderNestedScrollView that shows border when content scrolls.

### [MainSwitchBar](./widget/mainswitchbar)

MainSwitchBar & MainSwitchPreference ported from AOSP [SettingLib/MainSwitchPreference](https://cs.android.com/android/platform/superproject/+/master:frameworks/base/packages/SettingsLib/MainSwitchPreference/).

### [SwitchBar](./widget/switchbar)

SwitchBar in system settings.

```gradle
def rikkax_version="1.0.5.8"
implementation "com.github.g19980115.RikkaX:mainswitchbar:$rikkax_version"
implementation "com.github.g19980115.RikkaX:borderview:$rikkax_version"
implementation "com.github.g19980115.RikkaX:lifecycle-shared-viewmodel:$rikkax_version"
implementation "com.github.g19980115.RikkaX:core-ktx:$rikkax_version"
implementation "com.github.g19980115.RikkaX:layoutinflater:$rikkax_version"
implementation "com.github.g19980115.RikkaX:lazy:$rikkax_version"
implementation "com.github.g19980115.RikkaX:annotation:$rikkax_version"
implementation "com.github.g19980115.RikkaX:little-endian-data-stream:$rikkax_version"
implementation "com.github.g19980115.RikkaX:stub:$rikkax_version"
implementation "com.github.g19980115.RikkaX:core:$rikkax_version"
implementation "com.github.g19980115.RikkaX:multiprocess:$rikkax_version"
implementation "com.github.g19980115.RikkaX:appcompat:$rikkax_version"
implementation "com.github.g19980115.RikkaX:insets:$rikkax_version"
implementation "com.github.g19980115.RikkaX:material-help:$rikkax_version"
implementation "com.github.g19980115.RikkaX:compatibility:$rikkax_version"
implementation "com.github.g19980115.RikkaX:material-preference:$rikkax_version"
implementation "com.github.g19980115.RikkaX:recyclerview-adapter:$rikkax_version"
implementation "com.github.g19980115.RikkaX:switchbar:$rikkax_version"
implementation "com.github.g19980115.RikkaX:lifecycle-resource-livedata:$rikkax_version"
implementation "com.github.g19980115.RikkaX:material:$rikkax_version"
implementation "com.github.g19980115.RikkaX:html-ktx:$rikkax_version"
implementation "com.github.g19980115.RikkaX:html:$rikkax_version"
implementation "com.github.g19980115.RikkaX:recyclerview-ktx:$rikkax_version"
implementation "com.github.g19980115.RikkaX:parcelablelist:$rikkax_version"
implementation "com.github.g19980115.RikkaX:material-chooser:$rikkax_version"
implementation "com.github.g19980115.RikkaX:simplemenu-preference:$rikkax_version"
implementation "com.github.g19980115.RikkaX:lifecycle-viewmodel-lazy:$rikkax_version"
```
