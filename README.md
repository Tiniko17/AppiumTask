# AppiumTask

Appium task contains the logic for automating Reddit app on Android.

Assumption: Reddit account exsists

Steps:
1. Open Reddit app on an unlocked android emulator
2. Click "Search"
3. Type "banking"
4. Click "results for "banking...""
5. Click "Sort"
6. Click "Hot"
7. Scroll until we have 20 posts stored
8. Pick the post with the most upvotes and print its username, how long ago it was posted and number of comments.

*The code does not contain the logic for the case when 2 posts have the same highest number of upvotes as it was not asked in the task. In real-life testing,
I would cover that gap too.
