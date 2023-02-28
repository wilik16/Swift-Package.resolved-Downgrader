# Swift-Package.resolved-Downgrader
Downgrade Swift Project's Package.resolved Version 2 to Version 1.

# Why?
Xcode 13.2.1 only supports version 1 of `Package.resolved` file, so it won't compile a project that uses version 2 of this file. Some version of Xcode will automatically convert it to version 2 when it opens a project or add a new swift package (for example Xcode 13.4.1).

So, this script will help automatically downgrade the version unless you want to revert the file and add the additional package manually.

# Usage
Deploy to your hosting (or just open it locally in browser) or access https://wilik.id/swift/resolved-downgrader/

# Issues/Feedback or Contribution
I acknowledge that this script might not be perfect since there should be a lot of parameters with different values in `Package.resolved` version 2. So I am open with suggestions to improve this script, or you can directly open a Pull Request.