# HideKeyboard
Category for hiding keyboard while clicking anywhere on the screen

**How to use it?**

- Download the category file(s) 
- Insert it into your source code
- Call the category

**Example**

Inside a UIViewController, call your cateogry like this:

**Objective-C**

```
#import "UIViewController+KeyboardFeature.h"
...
- (void)viewDidLoad {
    [super viewDidLoad];
    [self hideKeyboardWhenTappedAround];
}
...
```

**Swift**

```
...
override func viewDidLoad() {
    super.viewDidLoad()
    self.hideKeyboardWhenTappedAround() 
}
...
```

Hope that will be helpful! 👍
