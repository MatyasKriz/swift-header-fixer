# SwiftHead
Has this ever happened to you?
```c
//
// OldFileName.swift
// IrrelevantTarget
//
// Created by Great Programmer on 12/12/2012.
// Copyright © 2018 Spark Inc. All rights reserved.
//
```

Or were you too lazy to look for the unicode copyright symbol in order to add the somehow missing copyright line?

```c
//
// YourFile.swift
// ThisCouldBeUs
//
// Created by Awesome Programmer on 11/11/2012.
//
```

Perhaps you don't believe in headers and your boss is pressuring you into adding them into files with barely a single comment line, let alone 7 in a row.

### SwiftHead to the rescue!
By utilizing this latest technology ruby script `swifthead` which is indispensable in your `$PATH`, you can fix all your `.swift` files in the directory you call it from. Complete usage with parameters is described below.

### Showcase
Using our new `swifthead` utility, you can turn this:
```c
//
// OldFileName.swift
// IrrelevantTarget
//
// Created by Great Programmer on 12/12/2012.
// Copyright © 2018 Spark Inc. All rights reserved.
//
```
into relevant this:
```c
//
//  ActualFileName.swift
//  CurrentTarget
//
//  Created by Great Programmer on 12/12/2012.
//  Copyright © 2018 Spark Inc. All rights reserved.
//
```

**OR**

This:
```c
//
// YourFile.swift
// ThisCouldBeUs
//
// Created by Awesome Programmer on 11/11/2012.
//
```
into beautiful this:
```c
//
//  YourFile.swift
//  ThisCouldBeUs
//
//  Created by Awesome Programmer on 11/11/2012.
//  Copyright © 2018 Spark Inc. All rights reserved.
//
```
using `swifthead`.

The actual code in your files stays safe and untouched! Only the headers are modified.

### Installation
If you clone within the next 20 minutes, you'll get the latest installation command for **FREE**.

**Clone RIGHT NOW**, `cd` into the directory and run this installation command:
```
cp ./swifthead.rb /usr/local/bin && mv /usr/local/bin/swifthead.rb /usr/local/bin/swifthead && chmod +x /usr/local/bin/swifthead
```

### Usage
```
swifthead [-p|--path PATH_TO_DIRECTORY] [-c|--company COMPANY_NAME]
```

As of now, the script itself doesn't support `-h` or `--help` parameters, therefore you can either remember the usage or write a PR.

#### All Done.

You may need to reload your shell. After that you can fix all your Swift file headers at once!

Don't be shy, go on. Try it on that cute production code of yours. I double dare you.

<br><br>
<sub><sub>The ruby script is provided as is without any warranties. Demolishing your code base by finding a bug in it makes only one person responsible – you! Treat your code like your firstborn baby and version it properly.</sub></sub>
