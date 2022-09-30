#  Hide bottom navigation bar on scroll down and vice versa
https://stackoverflow.com/questions/54414268/hide-bottom-navigation-bar-on-scroll-down-and-vice-versa

# flutter
Documents FLutter
- Loading

https://loading.io/
- Get keyboard height in Flutter

https://stackoverflow.com/questions/49269319/get-keyboard-height-in-flutter/64473806#64473806

- Valide sv deeplink 

ios: https://search.developer.apple.com/appsearch-validation-tool

- Tip guid useful:
https://github.com/erluxman/awesomefluttertips

- Example state notifier:
https://github.com/dangngocduc/provider_sample

- Page search Lib + UI ( Flutter Gems )
https://fluttergems.dev/

- Lib UI table the same excel
https://pub.dev/packages/lazy_data_table ( đã làm ở app ChintaiDx)

- Tải các Version Xcode
https://stackoverflow.com/questions/10335747/how-to-download-xcode-dmg-or-xip-file

- Hide Appbar on Scroll Flutter?
https://stackoverflow.com/questions/51948252/hide-appbar-on-scroll-flutter

- Emoiji
https://www.webfx.com/tools/emoji-cheat-sheet/

- Vòng đời flutter
https://viblo.asia/p/flutter-doi-dieu-can-ghi-nho-RQqKLN6zl7z

- About Flutter Location
https://github.com/Lyokone/flutterlocation?fbclid=IwAR1TL-4-1ovvbr-vt1qoXLJgy6AmplCObfH1yotTYpBpON7qQA8iG1p5UU4

- open source Example UI: 
https://github.com/nisrulz/flutter-examples

# ListView
- Load more
https://www.kindacode.com/article/flutter-listview-pagination-load-more/

- Listview filter search in Flutter
https://stackoverflow.com/a/50569613

- Add header
https://stackoverflow.com/a/49992238

//
ListView.builder(
    itemCount: data == null ? 1 : data.length + 1,
    itemBuilder: (BuildContext context, int index) {
        if (index == 0) {
            // return the header
            return new Column(...);
        }
        index -= 1;

        // return row
        var row = data[index];
        return new InkWell(... with row ...);
    },
);
//
# Tablayout
- Flutter Switching to Tab Reloads Widgets and runs FutureBuilder: with AutomaticKeepAliveClientMixin
https://stackoverflow.com/a/51225879/10819917

# Action sheet (IOS)
https://flatteredwithflutter.com/actionsheet-in-flutter/
code: https://github.com/AseemWangoo/flutter_programs/blob/master/CupertinoActionSheet.dart

# Bottom sheet (Android)
https://flutterdoc.com/bottom-sheets-in-flutter-ec05c90453e7

# Popup Menu Button
https://flutterrdart.com/flutter-popup-menu-button-example/

# Image & Icon
https://docs.flutter.dev/development/ui/widgets/assets

# Flutter calling child class function from parent class
https://stackoverflow.com/a/53706941

# Chat demo
https://github.com/duytq94/flutter-chat-demo

# extend class
https://code-maven.com/slides/dart-programming/extending-class

# Build Flutter
for that you need to run flutter build ios --release before you archive the app.
This is a known issue.
