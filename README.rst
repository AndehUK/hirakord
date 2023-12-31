hirakord
========

Easy to use command-line interface for building Discord bots in Python

**NOTE:** The helpers in this tool may not prove to be useful for everyone. You are welcome to open a PR if you notice any general improvements, bugs or want to contribute new helpers to this tool. **BOT TEMPLATES ARE CURRENTLY WORK IN PROGRESS!!**

Key Features
------------
- Modern Pythonic Interface
- Easy to use

Planned Features
----------------
- Web-based Documentation
- Bot templates

Helpers
-------
- `Cog <https://github.com/ExHiraku/hirakord/tree/main/hirakord/templates/helpers/cog.txt/>`__

  - Slightly builds on ``discord.ext.commands.Cog``.

- `Embed <https://github.com/ExHiraku/hirakord/tree/main/hirakord/templates/helpers/embed.txt/>`__

  - Slightly different approach to ``discord.Embed``.

- `Logger <https://github.com/ExHiraku/hirakord/tree/main/hirakord/templates/helpers/logger.txt/>`__

  - Custom logger class with colour-coded prefixes based on log type.

- `Tree <https://github.com/ExHiraku/hirakord/tree/main/hirakord/templates/helpers/tree.txt/>`__

  - Slightly builds on ``discord.app_commands.CommandTree``, adds a custom event for app command errors

- `UI <https://github.com/ExHiraku/hirakord/tree/main/hirakord/templates/helpers/ui.txt/>`__

  - Does some of the component set up for you such as optionally assigning custom_ids.
  - Comes packaged with SelectMenus for all supported Channel types as well!

Links
-----
- `PyPi Release <https://pypi.org/project/hirakord/>`__
- `My Website <https://andeh.uk/>`__
- `My Discord Server <https://discord.gg/ycCeBFjQeK>`__ ~ Support Available!

Installing
----------

**Python3.8 or higher is required**

To install the library without `discord.py <https://github.com/Rapptz/discord.py/>`__, run the following command

.. code:: sh

    # Linux / MacOS
    $ python3 -m pip install -U hirakord

    # Windows
    $ py -3 -m pip install -U hirakord

To install the library with `discord.py <https://github.com/Rapptz/discord.py/>`__, run the following command

.. code:: sh

    # Linux / MacOS
    $ python3 -m pip install -U hirakord[discord]

    # Windows
    $ py -3 -m pip install -U hirakord[discord]

Quick Example
-------------

.. code:: sh

    # Installing a helper (Linux / MacOS)
    $ python3 -m hirakord helper add logger

    # Installing a helper (Windows)
    $ py -3 -m hirakord helper add logger
