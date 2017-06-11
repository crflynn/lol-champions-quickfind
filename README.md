# League of Legends Champion Quickfind Strings

The file ``champions.json`` contains the shortest strings necessary to
__uniquely__ identify each champion in League of Legends using the
client search field during champion select.

Knowing these strings can help you find your champions faster, so you are less
likely to accidentally dodge the queue when the timer is running low and you
can't find your champion by scrolling.

You can test all of these easily by logging into the client, clicking
_COLLECTION_ on the main menu bar at the top of the client, and clicking
_CHAMPIONS_ in the submenu bar beneath the _PLAY_ button. Enter any of the
champion-specific strings from ``champions.json`` and the champion search
results will give you _only_ that champion.

### Example:

Here is the entry for Blitzcrank in the json file:

    "blitzcrank": [
        "bi",
        "bk",
        "bt",
        "bz",
        "tz",
        "zk"
    ],

In the champion search bar typing ``bt`` or ``tz`` or any of the other strings
here will result in _only_ Blitzcrank appearing in the results.

As of writing this README, there are two champions who can be found using a
single character: Dr. Mundo (with ``.``) and Quinn (with ``q``).

Vi is the only champion who cannot be uniquely selected with a single string;
all of her string sequences are shared with Viktor, for example.
