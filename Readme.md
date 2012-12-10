Pinboard Recipe
===============

![Pinboard Recipe Screenshot](https://github.com/anoved/Pinboard-Recipe/raw/master/PinboardRecipe.png)

[Pinboard](http://pinboard.in/) is a fast, no-nonsense bookmarking site. You can tag pages to [read later](https://pinboard.in/tour/#later) with a [browser bookmarklet](https://pinboard.in/howto/#saving). A one-time signup fee applies.

[Calibre](http://www.calibre-ebook.com/) is a free and open source ebook library management application. It is extensible with Python scripts called [recipes](http://manual.calibre-ebook.com/news.html) which can be used to compile ebooks from arbitrary webpages.

Use this `Pinboard.recipe` to create ebooks of your unread bookmarks.

Setup
-----

- In Calibre, select _Add a custom news source_ from the _Fetch news_ toolbar button or menu. Click _Load recipe from file_ and select the [`Pinboard.recipe`](https://raw.github.com/anoved/Pinboard-Recipe/master/Pinboard.recipe) file downloaded from this repository.
- Locate your [Pinboard API Token](https://pinboard.in/settings/password) and paste it into the _Pinboard Bookmarks_ source code as the `apitoken` value (indicated near the top of the script).
- By default, your unread bookmarks are marked as read once retrieved. If you would prefer to delete them instead, set the `delete_bookmarks` variable to `True`.
- Click _Add/Update recipe_ and click _Yes_ to confirm that you want to update ("replace") the recipe.

Now when you click _Fetch News_ you can choose _Pinboard Bookmarks_ from the _Custom_ section of the recipe list.

For more information about installing and modifying recipes, [see this post on the Calibre forums](http://www.mobileread.com/forums/showthread.php?t=121439).

License
-------

Pinboard Recipe is freely distributed under the open source [GNU General Public License v3](http://opensource.org/licenses/GPL-3.0). See the `LICENSE` file for details.
