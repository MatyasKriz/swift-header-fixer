# SwiftHead
Has this ever happened to you?
```
//
// OldFileName.swift
// IrrelevantTarget
//
// Created by Great Programmer on 12/12/2012.
// Copyright © 2018 Spark Inc. All rights reserved.
//
```

Or were you too lazy to look for the unicode copyright symbol in order to add the somehow missing copyright line?

```
//
// YourFile.swift
// ThisCouldBeUs
//
// Created by Awesome Programmer on 11/11/2012.
//
```

Perhaps you don't believe in headers and your boss is pressuring you into adding headers into files where there isn't even a single comment line, let alone 7 in a row.

### SwiftHead to the rescue!

Simply clone this repo, `cd` into the directory and run this simple command:
```
cp ./swifthead.rb /usr/local/bin && mv /usr/local/bin/swifthead.rb /usr/local/bin/swifthead && chmod +x /usr/local/bin/swifthead
```

#### All Done.

You may need to reload your shell. After that you can fix all your Swift file headers at once!

By utilizing this latest technology ruby script `swifthead` which is now in your `$PATH`. It fixes all `.swift` files in the directory you call it from. Alternatively, you can pass a path as an argument to the script.

Don't be shy, go on. Try it on that cute production code of yours.

<br><br><br>
<sub><sub>The ruby script is provided as is without any warranties. Demolishing your code base by finding a bug in it makes only one person responsible – you! Treat your code like your firstborn baby and version it properly.</sub></sub>
