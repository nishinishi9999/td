# td

Simple cygwin tool for feature and bug tracking.

![screenshot](https://user-images.githubusercontent.com/14959143/31885444-d2757d08-b7f0-11e7-943a-90db3380c56d.png)


# Usage



    init
        Initialize td project.

    close
        Close td project.

    add
        Add an entry to todo.txt.

        Example: td add abcd | td add abcd -t TEST | td add abcd -to efgh

    rm
        Remove entry from todo.txt

        Example: td rm 10

    done
        Either show all entries marked as down or set an entry done
        (being a special case of td set <n> s done)

        Example: td done | td done 10

    set
        Set an entry attribute (if an entry n is provided) or a global variable.

        Example: td set -version 0.1.1 | td set -n 10 -t TEST

    filter
        Filter results by entry with one arguments or by attribute with two.

        Example: td filter -e test | td filter -v 0.1.0

    list
        List all or some opened td projects

        Example: td list -all | td list -name abcd

    help
        Show this help

    version
        Show current version

# Author
Alvaro Fernandez (nishinishi9999)

# License
GNU General License (GPL) 3.0 - https://www.gnu.org/licenses/gpl-3.0.en.html

# Contact mail
nishinishi9999 at gmail dot com
