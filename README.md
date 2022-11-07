# burmese-language-bug
A basic flutter app highlighting a bug in the ios build not supporting the burmese language for localizable strings, specifically for an app name.

Here is a public repo I made reproducing the issue on the basic flutter app. The languages the app name is supposed to localize to is English (base), Spanish, Burmese, and Burmese with “Myanmar (Burma)” region. To reproduce the issue, run the app and then change the ios system language in Settings->General->Language & Region with the desired language at the top. It will work for English and Spanish but not for either of the Burmese options.
